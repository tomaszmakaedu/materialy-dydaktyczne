# Klasa Notatka w aplikacji konsolowej

Pracownia projektowania obiektowego

Celem pracy jest przećwiczenie elementów, które regularnie występują w części konsolowej egzaminu INF.04: klasy, pola prywatne, konstruktor, metody, pole statyczne oraz testowanie obiektu w programie głównym. Wszystkie decyzje dotyczące nazw i treści notatek podejmujesz samodzielnie, o ile karta nie wskazuje inaczej.

## Pobranie i przygotowanie narzędzi

Podstawowym środowiskiem pracy jest Visual Studio Community. Jeżeli program i wymagane składniki są już zainstalowane na stanowisku, pomiń kroki instalacji i przejdź do sprawdzenia projektu.

Otwórz menu Start i wyszukaj Visual Studio. Jeżeli program działa, uruchom także Visual Studio Installer i przejdź do kroku 4. Jeżeli wymagane obciążenie jest już zaznaczone, przejdź do kroku 6.

Pobierz Visual Studio Community wyłącznie z oficjalnej strony Microsoftu: visualstudio.microsoft.com/vs/community/

Uruchom pobrany plik instalatora, zwykle `VisualStudioSetup.exe` albo `vs_community.exe`, i zaakceptuj pytanie Kontroli konta użytkownika.

W instalatorze zaznacz obciążenie `.NET desktop development` (`Programowanie aplikacji klasycznych .NET`). Jest ono potrzebne do projektu Console App w C#.

Kliknij Install albo Modify i poczekaj na zakończenie instalacji. Do tego etapu mogą być potrzebne uprawnienia administratora.

Uruchom Visual Studio, wybierz Create a new project i sprawdź, czy dostępny jest szablon Console App z językiem C#. Jeżeli tak, środowisko jest gotowe.

## Rezultat końcowy

Utworzysz projekt aplikacji konsolowej w języku C#.

Zaimplementujesz klasę `Notatka` przechowującą tytuł i treść notatki.

Przetestujesz działanie klasy w metodzie `Main`.

Dodasz komentarz dokumentacyjny nad definicją klasy.

Skompilujesz i uruchomisz projekt oraz wykonasz zrzut ekranu.

## Plan pracy

## Instrukcja wykonania

1. Utwórz nowy projekt typu Console App w języku C#. Nazwij go `NotatkiKonsola`.

2. Utwórz klasę o nazwie `Notatka`. Klasa ma zawierać: statyczny licznik utworzonych notatek, numeryczny identyfikator, tekstowy tytuł oraz tekstową treść.

3. Ustaw widoczność pól tak, aby były dostępne wyłącznie wewnątrz klasy. Pole identyfikatora i licznik mają być niewidoczne dla klas potomnych. Pola tytułu i treści mogą być dostępne dla klas potomnych.

4. Utwórz konstruktor przyjmujący tytuł i treść. Konstruktor ma najpierw zwiększyć licznik, następnie nadać obiektowi identyfikator równy licznikowi, a na końcu zapisać tytuł i treść.

5. Dodaj bezparametrową metodę wyświetlającą tytuł i treść notatki w czytelnej formie.

6. Dodaj bezparametrową metodę diagnostyczną. Ma wypisywać wszystkie pola obiektu, oddzielając je średnikami.

7. W metodzie `Main` utwórz co najmniej dwa obiekty z własnymi, znaczącymi danymi. Dla każdego obiektu wywołaj obie metody.

8. Sprawdź, czy pierwszy obiekt ma identyfikator 1, drugi 2, a licznik wskazuje liczbę utworzonych obiektów.

9. Nad definicją klasy dodaj komentarz zawierający nazwę klasy, opis, pola, metody i numer autora. Wpisz swój numer lub imię i nazwisko zgodnie z ustaleniami nauczyciela.

10. Uruchom program. Wynik powinien jednoznacznie pokazywać dane obu notatek, identyfikatory i działanie obu metod.

## Warunki techniczne

Nie umieszczaj operacji wejścia i wyjścia w konstruktorze ani w metodach klasy, jeżeli nie są do tego przeznaczone.

Nie twórz gotowego rozwiązania przez kopiowanie kodu z Internetu.

Nazwy pól, metod i zmiennych muszą być znaczące.

Program ma być czytelnie sformatowany.

Nie wystarczy samo utworzenie klasy - musi być widoczny test jej działania w `Main`.

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

folder `01_obiektowe`

archiwum `NotatkiKonsola.zip` z całym projektem

plik lub pliki źródłowe zmodyfikowane podczas pracy

zrzut ekranu `konsola1.png` pokazujący uruchomiony program oraz środowisko programistyczne lub terminal

## Wymagane zrzuty ekranu

`konsola1.png`: cały ekran, widoczny pasek zadań, wynik programu i kod lub terminal

[ ] projekt otwiera się w środowisku programistycznym

[ ] aplikacja kompiluje się bez błędów

[ ] aplikacja uruchamia się i pokazuje wymagany rezultat

[ ] w archiwum znajduje się pełny projekt

[ ] zrzuty ekranu są czytelne i mają właściwe nazwy

[ ] temat wiadomości ma wymagany format

| Imię i nazwisko: | ........................................ | Klasa: | .................... |

| --- | --- | --- | --- |

| Data wykonania: | 11.09.2026 | Przedmiot: | Pracownia projektowania obiektowego |

| Etap | Co wykonujesz | Czas |

| --- | --- | --- |

| 1 | Sprawdź środowisko, utwórz projekt konsolowy `NotatkiKonsola` i zapoznaj się z wymaganiami. | 10 min |

| 2 | Zaprojektuj klasę `Notatka`, jej pola oraz konstruktor. | 25 min |

| 3 | Dodaj metody wyświetlające dane i diagnostykę. | 25 min |

| 4 | Napisz program główny i wykonaj wymagane testy. | 25 min |

| 5 | Dodaj dokumentację, uruchom program i przygotuj pliki do oddania. | 15 min |

| Obszar | Warunek zaliczenia | Punkty |

| --- | --- | --- |

| Projekt i kompilacja | Projekt został utworzony, otwiera się i kompiluje bez błędów. | 10 |

| Pola klasy | Klasa ma wymagane cztery pola i właściwą widoczność. | 20 |

| Konstruktor | Licznik, identyfikator, tytuł i treść są ustawiane w prawidłowej kolejności. | 15 |

| Metody klasy | Działają metoda prezentacji i metoda diagnostyczna ze średnikami. | 25 |

| Test w Main | Utworzono dwa obiekty i wywołano obie metody dla każdego. | 20 |

| Dokumentacja i styl | Komentarz dokumentacyjny, znaczące nazwy i czytelne formatowanie. | 10 |
---

[Pobierz wersję DOCX tej karty pracy](01_pracownia_projektowania_obiektowego_github.docx)
