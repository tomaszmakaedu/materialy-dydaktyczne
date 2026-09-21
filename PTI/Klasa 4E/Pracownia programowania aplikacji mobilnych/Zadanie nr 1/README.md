# Mobilna lista notatek

Pracownia programowania aplikacji mobilnych

Celem pracy jest wykonanie prostej aplikacji mobilnej podobnej do zadań występujących w arkuszach INF.04. Przećwiczysz projektowanie interfejsu w XAML, obsługę przycisku, kolekcję danych oraz automatyczne odświeżanie listy. Pracę wykonujesz samodzielnie w C# i .NET MAUI.

## Pobranie i przygotowanie narzędzi

Podstawowym środowiskiem pracy jest Visual Studio Community. Jeżeli program i wymagane składniki są już zainstalowane na stanowisku, pomiń kroki instalacji i przejdź do sprawdzenia projektu.

Otwórz menu Start i wyszukaj Visual Studio. Jeżeli program działa, uruchom także Visual Studio Installer i przejdź do kroku 4. Jeżeli wymagane obciążenie jest już zaznaczone, przejdź do kroku 6.

Pobierz Visual Studio Community wyłącznie z oficjalnej strony Microsoftu: visualstudio.microsoft.com/vs/community/

Uruchom pobrany plik instalatora, zwykle `VisualStudioSetup.exe` albo `vs_community.exe`, i zaakceptuj pytanie Kontroli konta użytkownika.

W instalatorze zaznacz obciążenie `.NET Multi-platform App UI development` (`.NET MAUI`). Pozostaw zaznaczone domyślne składniki Android SDK i emulatora.

Kliknij Install albo Modify i poczekaj na zakończenie instalacji. Do tego etapu mogą być potrzebne uprawnienia administratora.

Uruchom Visual Studio, wybierz Create a new project, wyszukaj `.NET MAUI App` i sprawdź, czy szablon jest widoczny. Następnie w pasku Debug Target wybierz Android Emulators.

Przy pierwszym uruchomieniu emulatora zaakceptuj licencje i pozwól Visual Studio pobrać Android SDK oraz emulator. Szczegółowa instrukcja Microsoftu: learn.microsoft.com/dotnet/maui/get-started/first-app

Pobieranie Android SDK i emulatora nie jest wliczone w 2 godziny pracy nad zadaniem. Na zajęciach sprawdź gotowe środowisko; pełną instalację wykonaj wcześniej.

Instrukcja instalacji .NET MAUI firmy Microsoft: learn.microsoft.com/dotnet/maui/get-started/installation

## Rezultat końcowy

Aplikacja uruchamia się w emulatorze.

Na ekranie są trzy początkowe notatki.

Użytkownik wpisuje nową notatkę i dopisuje ją przyciskiem.

Nowa notatka pojawia się jako ostatni element listy bez ponownego uruchamiania aplikacji.

Interfejs ma układ pionowy oraz poziomy wiersz z polem i przyciskiem.

Aplikacja ma podstawowe formatowanie wymagane w zadaniach egzaminacyjnych.

## Plan pracy

## Instrukcja wykonania

1. Utwórz projekt typu .NET MAUI App. Nazwij go `NotatkiMobilne`.

2. W pliku interfejsu XAML zastosuj główny układ pionowy. W jego wnętrzu utwórz poziomy układ zawierający pole edycyjne i przycisk.

3. Dodaj tytuł aplikacji, na przykład `Moje notatki`.

4. Dodaj pole edycyjne z podpowiedzią `Nowy element`.

5. Dodaj przycisk z tekstem `DODAJ`.

6. Dodaj widok listy. Możesz użyć `ListView` albo `CollectionView`, ale lista musi prezentować elementy kolekcji tekstowej.

7. W kodzie C# utwórz kolekcję zawierającą trzy własne, znaczące notatki. Zastosuj kolekcję, która powiadamia interfejs o dodaniu elementu, na przykład `ObservableCollection<string>`.

8. Ustaw kolekcję jako źródło danych widoku listy.

9. Utwórz obsługę kliknięcia przycisku. Odczytaj tekst z pola edycyjnego, dodaj go na końcu kolekcji i wyczyść pole.

10. Przetestuj dodanie notatki `Urodziny Ali` oraz drugiej, własnej notatki. Obie muszą pojawić się na końcu listy.

11. Ustaw kolor tła przycisku Crimson (#DC143C) i biały kolor tekstu. Jeżeli używasz `ListView`, ustaw widoczny separator w kolorze Crimson.

12. Skompiluj aplikację i uruchom ją w emulatorze. Nie kończ pracy na samym widoku XAML.

## Samokontrola działania

Czy po uruchomieniu widoczne są dokładnie trzy początkowe notatki?

Czy pole ma podpowiedź `Nowy element`?

Czy kliknięcie `DODAJ` dopisuje tekst jako ostatni element?

Czy lista odświeża się bez restartu aplikacji?

Czy przycisk ma właściwy kolor i biały tekst?

Czy aplikacja działa również po dodaniu drugiej notatki?

## Punktacja

Maksymalnie można zdobyć 100 punktów. Liczba punktów jest jednocześnie wynikiem procentowym.

## Skala ocen

0-49% - niedostateczny

50-59% - dopuszczający

60-69% - dostateczny

70-79% - dobry

80-89% - bardzo dobry

90-100% - celujący

## Oddanie pracy

Pracę wykonujesz samodzielnie. Możesz korzystać z pomocy wbudowanej w środowisko programistyczne i oficjalnej dokumentacji, ale kod, testy i dokumentację tworzysz własnoręcznie.

Termin oddania: 18.09.2026, czyli w ciągu 7 dni od zajęć.

Adres e-mail: tomasz.maka.edu@gmail.com

Temat wiadomości: Nazwisko Imie Klasa PTI DD.MM.RR. W miejsce DD.MM.RR wpisz datę wysłania wiadomości.

Wyślij jeden plik ZIP o nazwie: Nazwisko_Imie_Klasa_PTI_11.09.2026.zip.

W archiwum umieść pełny projekt oraz pliki wymienione poniżej. Nie wysyłaj samego fragmentu kodu.

## Zawartość archiwum

folder `02_mobilne`

archiwum `NotatkiMobilne.zip` z całym projektem

zmodyfikowany plik XAML i plik z kodem C#

zrzut `mobilna1.png` - stan początkowy aplikacji

zrzut `mobilna2.png` - aplikacja po dodaniu nowej notatki

## Wymagane zrzuty ekranu

`mobilna1.png`: cały ekran z emulatorem i widocznym środowiskiem programistycznym

`mobilna2.png`: cały ekran po dodaniu notatki, z widocznym nowym elementem listy

[ ] projekt otwiera się w środowisku programistycznym

[ ] aplikacja kompiluje się bez błędów

[ ] aplikacja uruchamia się i pokazuje wymagany rezultat

[ ] w archiwum znajduje się pełny projekt

[ ] zrzuty ekranu są czytelne i mają właściwe nazwy

[ ] temat wiadomości ma wymagany format

| Imię i nazwisko: | ........................................ | Klasa: | .................... |

| --- | --- | --- | --- |

| Data wykonania: | 11.09.2026 | Przedmiot: | Pracownia programowania aplikacji mobilnych |

| Etap | Co wykonujesz | Czas |

| --- | --- | --- |

| 1 | Sprawdź emulator Android, utwórz projekt .NET MAUI i uruchom pustą aplikację. | 10 min |

| 2 | Zbuduj interfejs w XAML: tytuł, pole, przycisk i lista. | 25 min |

| 3 | Dodaj kolekcję trzech notatek i połącz ją z widokiem listy. | 20 min |

| 4 | Dodaj obsługę przycisku oraz automatyczne odświeżanie listy. | 25 min |

| 5 | Dodaj wygląd, uruchom testy i wykonaj zrzuty ekranu. | 20 min |

| Obszar | Warunek zaliczenia | Punkty |

| --- | --- | --- |

| Projekt i uruchomienie | Projekt został utworzony, skompilowany i uruchomiony w emulatorze. | 10 |

| Interfejs | Tytuł, pole, przycisk, lista oraz układy pionowy i poziomy są obecne. | 20 |

| Dane początkowe | Lista jest zasilona trzema notatkami przy uruchomieniu. | 15 |

| Kolekcja i powiązanie | Widok listy korzysta z kolekcji tekstowej jako źródła danych. | 15 |

| Obsługa przycisku | Tekst jest dopisywany na końcu listy, lista odświeża się, a pole jest czyszczone. | 25 |

| Wygląd i dowody | Kolor przycisku, czytelność interfejsu i wymagane zrzuty ekranu. | 15 |
---

[Pobierz wersję DOCX tej karty pracy](02_pracownia_programowania_aplikacji_mobilnych_github.docx)
