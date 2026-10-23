# Testowanie i dokumentowanie aplikacji

Pracownia testowania i dokumentowania aplikacji

Celem pracy jest przeprowadzenie krótkiego testu aplikacji konsolowej i mobilnej oraz przygotowanie dokumentacji w formie wymaganej podczas egzaminu INF.04. Nie poprawiasz kodu za kolegę i nie opisujesz działania, którego nie sprawdziłeś. Każdy wynik wpisujesz na podstawie własnego uruchomienia programu.

## Pobranie i przygotowanie narzędzi

Do wykonania tej karty potrzebujesz Visual Studio do uruchamiania projektów oraz programu do przygotowania dokumentu `egzamin.docx`. Zrzuty ekranu i archiwum ZIP wykonasz narzędziami wbudowanymi w Windows.

Sprawdź w menu Start, czy masz Visual Studio Community. Jeżeli tak, otwórz je i przejdź do kroku 4.

Jeżeli Visual Studio nie jest zainstalowane, pobierz je wyłącznie z oficjalnej strony Microsoftu: visualstudio.microsoft.com/vs/community/

Uruchom instalator i zaznacz obciążenia `.NET desktop development` oraz `.NET Multi-platform App UI development`, aby móc otworzyć oba projekty z wcześniejszych kart. Pozostaw domyślne składniki.

Do przygotowania `egzamin.docx` użyj Microsoft Word, jeżeli jest dostępny. Jeżeli nie, pobierz LibreOffice z oficjalnej strony: www.libreoffice.org/download/

W instalatorze LibreOffice wybierz wersję dla Windows, uruchom program Writer i zapisuj dokument przez Save As jako Word 2007-365 (`.docx`).

Do zrzutów użyj wbudowanego Narzędzia Wycinanie albo klawisza `PrtSc`, a do ZIP użyj Eksploratora plików: prawy przycisk myszy, Send to, Compressed zipped folder.

Nie pobieraj programów z przypadkowych stron. Instalacja Visual Studio oraz Android SDK może trwać dłużej niż jedna lekcja, dlatego na zajęciach korzystaj z przygotowanego stanowiska.

## Rezultat końcowy

Wykonasz testy funkcjonalne obu aplikacji z dzisiejszych zajęć.

Udokumentujesz wynik testów: pozytywny, negatywny albo wymagający poprawy.

Sprawdzisz, czy kod zawiera komentarz dokumentacyjny klasy `Notatka`.

Przygotujesz plik `egzamin.docx` oraz zrzuty ekranu.

Skompletujesz pliki w archiwum gotowym do wysłania nauczycielowi.

## Plan pracy

## Instrukcja wykonania

1. Utwórz folder `03_testy_dokumentacja`.

2. W tym folderze przygotuj dokument `egzamin.docx`. Na pierwszej stronie wpisz imię i nazwisko, klasę, datę, nazwę systemu operacyjnego, środowisko programistyczne oraz język programowania.

3. W projekcie konsolowym odszukaj klasę `Notatka`. Sprawdź, czy nad klasą znajduje się komentarz zawierający nazwę klasy, opis, pola, metody i autora. Jeżeli komentarza nie ma, dodaj go samodzielnie.

4. Uruchom aplikację konsolową i wykonaj test utworzenia dwóch notatek. Sprawdź identyfikatory, licznik oraz działanie obu metod.

5. Uruchom aplikację mobilną. Sprawdź stan początkowy z trzema notatkami.

6. Wpisz `Urodziny Ali`, wybierz `DODAJ` i sprawdź, czy tekst pojawił się jako ostatni element listy.

7. Dodaj drugą, własną notatkę. Sprawdź, czy poprzednia notatka nie zniknęła.

8. W dokumencie `egzamin.docx` zapisz dla każdego testu: numer, czynność, oczekiwany rezultat, rzeczywisty rezultat oraz status `PASS` albo `FAIL`.

9. Dodaj do dokumentu podpisane zrzuty ekranu. Zrzuty powinny pokazywać cały ekran, pasek zadań oraz kod i wynik działania, a w przypadku aplikacji mobilnej także emulator.

10. Zapisz dokument i sprawdź, czy można go ponownie otworzyć.

## Przypadki testowe

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

folder `03_testy_dokumentacja`

plik `egzamin.docx`

folder `zrzuty` zawierający zrzuty `konsola1.png`, `konsola2.png`, `mobilna1.png`, `mobilna2.png` lub większą liczbę, jeżeli jest potrzebna

archiwum `testy_dokumentacja.zip` zawierające dokument i zrzuty

w archiwum głównym także foldery `01_obiektowe` i `02_mobilne` z projektami z pozostałych kart

## Wymagane zrzuty ekranu

`konsola1.png` i `konsola2.png`: wynik testów konsolowych oraz kod lub terminal

`mobilna1.png` i `mobilna2.png`: stan początkowy i stan po dodaniu notatki

| Imię i nazwisko: | ........................................ | Klasa: | .................... |

| --- | --- | --- | --- |

| Data wykonania: | 11.09.2026 | Przedmiot: | Pracownia testowania i dokumentowania aplikacji |

| Etap | Co wykonujesz | Czas |

| --- | --- | --- |

| 1 | Sprawdź narzędzia, przeczytaj kryteria i przygotuj folder testów. | 5 min |

| 2 | Wykonaj testy aplikacji konsolowej i zapisz rzeczywiste wyniki. | 15 min |

| 3 | Wykonaj testy aplikacji mobilnej i zapisz rzeczywiste wyniki. | 15 min |

| 4 | Przygotuj dokument `egzamin.docx` oraz komentarz do kodu, jeśli go brakuje. | 15 min |

| 5 | Wykonaj zrzuty, spakuj pliki i przeprowadź kontrolę końcową. | 10 min |

| Nr | Czynność | Oczekiwany rezultat | Rzeczywisty rezultat | Status |

| --- | --- | --- | --- | --- |

| 1 | Uruchom konsolę i utwórz pierwszą notatkę. | Dane notatki są wyświetlone, a identyfikator wynosi 1. | Wpisz po wykonaniu | PASS / FAIL |

| 2 | Utwórz drugą notatkę i uruchom obie metody. | Drugi obiekt ma kolejny identyfikator, a obie metody działają. | Wpisz po wykonaniu | PASS / FAIL |

| 3 | Sprawdź licznik utworzonych notatek. | Licznik odpowiada liczbie utworzonych obiektów. | Wpisz po wykonaniu | PASS / FAIL |

| 4 | Uruchom aplikację mobilną. | Widoczne są trzy początkowe notatki. | Wpisz po wykonaniu | PASS / FAIL |

| 5 | Dodaj `Urodziny Ali`. | Tekst pojawia się jako ostatni element listy. | Wpisz po wykonaniu | PASS / FAIL |

| 6 | Dodaj drugą własną notatkę. | Lista zawiera wcześniejsze elementy i nowy wpis. | Wpisz po wykonaniu | PASS / FAIL |

| Obszar | Warunek zaliczenia | Punkty |

| --- | --- | --- |

| Testy konsolowe | Wykonano testy 1-3 i zapisano rzeczywiste wyniki. | 20 |

| Testy mobilne | Wykonano testy 4-6 i zapisano rzeczywiste wyniki. | 25 |

| Dokument `egzamin` | Zawiera dane ucznia, narzędzia, język, przypadki testowe i statusy. | 25 |

| Zrzuty ekranu | Zrzuty pokazują wymagane stany, cały ekran i środowisko pracy. | 15 |

| Kompletność oddania | Prawidłowy ZIP, pełne projekty, właściwe nazwy i temat wiadomości. | 15 |
---

[Pobierz wersję DOCX tej karty pracy](03_pracownia_testowania_i_dokumentowania_github.docx)
