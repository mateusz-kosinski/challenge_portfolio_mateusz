# challenge_portfolio_mateusz

# Task 1

## Subtask 1


* 6/10 punktow


## Subtask 3

Cześć, mam na imię Mateusz, zdecydowałem się wziąć udział w kursie ponieważ chciałbym zmienić pracę na nową. Aktualnie pracuję prawie od 10 lat jako programista - automatyk. Chciałbym przejść w świat IT, zmienić środowisko w którym pracuję oraz zdobyć nowe doświadczenie które mam nadzieję zaowocuje na następne lata.  

## Subtask 4

* _Na czym polega ta aplikacja? Do czego służy?_

Aplikacja pełni funkcję bazy danych z zapisanymi skautami, aplikacja służy do dodawania nowych graczy oraz przeglądania i filtrownia aktualnie zapisanych profili.

* _Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)_

Apliakcja posiada możliwość dodawnia nowych graczy do bazy danych jak i filtorowania oraz eksportu aktualnie zapisanych graczy. Każdy gracz posiada swoje indywiduane statystyki, nazwę drużycy, pozycję oraz informację o wieku. 


* _Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?_

Interfejs aplikacji jest prosty i czytelny, brakuje w nim ciemnego trybu wyświetlania. 

* _Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu)._

Aplikacja jest intuicyjna, wszystkie funkcje są czytelne i zrozumiałe, poprawy wymaga tłumaczenie interfejsu jak i okien pop-up. Szczególną uwagę należy również zwrócić na logikę danych zawartych w eksportowanym pliku CSV. Aktualnie formatowanie pliku należy wykonać ręczenie ponieważ wszystkie eksportowane kolumny są zapisane w jednej komórce. 

* _Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)_


Adres Strony: **https://scouts-test.futbolkolektyw.pl/pl**

Dostęp: **Niedziela, 15.01.2023** 

Przeglądarka: **Google Chrome** 

Wersja przeglądarki: **108.0.5359.125 (Oficjalna wersja) (64-bitowa)**

Zainstalowane wtyczki: **Adblock 5.3.3**

System operacyjny: **Windows 10 Enterprise**

Kompilacja systemu operacyjnego: **19045.2251**



<p align="center">========== STRONA GÓWNA ==========</>

1.  Po zmianie języka polski/angielski nazwa strony **'Scouts Panel'** nie jest przetłumaczony na język polski. 
* _Zalecenie:_ dodatnie tłumaczenia 'Scouts Panel' na 'Panel skautów'
2. Po zmianie języka polski/angielski tekst przycisku **'DEV TEAM CONTACT'** nie jest przetłumaczony na język polski. 
* _Zalecenie:_ dodatnie tłumaczenia 'DEV TEAM CONTACT' na 'Skontaktuj się z twórcami strony

<p align="center">========== STRONA DODAWANIA NOWEGO GRACZA ==========</>

1. Teskty ankiety **'Data urodzenia'** jest przetłuamczony na język angielski jako **'Age'**, tłumaczenie jest nie spójne. 
* _Zalecenie:_ zamiana angielskiego tłumaczenia na 'Date of birth'
2. Teskty ankiety **'Łączy nas piłka'** oraz **'90 minut'** w dolnej części ekarnu nie są przetłumaczone na język angielski: 
* _Zalecenie:_ zmiana tłumaczenia 'Łączy nas piłka' na 'Football connects us'
* _Zalecenie:_ zmiana tłumaczenia '90 minut' na '90 minutes'
3. Po rozwinięciu menu wyboru województwa tłumaczenia wyświetlają się błędne tłumaczenia na język angielski
* _Zalecenie:_ poprawa tłumaczeń na nazw województw na język angielski
4. Poniżej testów z poprzedniego punktu interaktywne przyciski **'SUBMIT'** oraz **'CLEAR'** również nie są przetumaczone na język polski
* _Zalecenie:_ dodanie tłumaczenia dla przysisku 'SUBMIT' na 'WYŚLIJ' 
* _Zalecenie:_ dodanie tłumaczenia dla przycisku 'CLEAR' na 'WYCZYŚĆ'
5. Uzupełnienie ankiedy dodawania nowego gracza - w przypadku nie podania wymaganej wartości wejściowej brak tłumaczenia czerwonego komenatarza **'Required'** na język polski
* _Zalecenie:_ dodanie tłumaczenia dla czerwonego komentarza 'Required' na 'Wymagane'
6. Uzupełnienie ankiedy dodawania nowego gracza - po podaniu nieprawidłowego adresu email wyświetla się oglny błąd **'Nie udało się dodać gracza'** 
* _Zalecenie:_ dodanie szczegółowego opisu przyczyny dla której nie możemy dodać gracza 'Podaj prawidłowy adres mailowy'
7. Uzupełnienie ankiedy dodawania nowego gracza - możliwość wpisania liter w oknie numeru telefonu 
* _Zalecenie:_ ograniczenie tylko do cyf 
8. Uzupełnienie ankiedy dodawania nowego gracza - brak ograniczeń logicznych podczas podawania wartoścli liczbowych - wiek, numer telefony, waga, wzrost
* _Zalecenie:_ ograniczenie tylko do przedziału wartości liczbowych które faktycznie mogą wystąpić 
*               wiek [0 - 99]
*               waga [5 - 199]
*               wzrost [5 - 199]
*               numer telefonu [000000000 - 999999999]
9. Uzupełnienie ankiedy dodawania nowego gracza - brak ograniczeń logicznych podczas podawania linków do mediów socjalnych: facebook oraz youtube.
* _Zalecenie:_ sprawdzanie czy wpisana wartość jest pusta lub posiada zakończenie '.www'
10. Uzupełnienie ankiedy dodawania nowego gracza - brak ograniczeń długości wprowadzanych wartości w ankiecie 
* _Zalecenie:_ ograniczenie ilości znaków wprowadzanych w poszczególnych polach ankiety

<p align="center">========== STRONA DODAWANIE NOWEGO MECZU DLA ISTNIEJĄCEGO GRACZA ==========</>
  
1. Teskty ankiety **'Web Mech'** oraz **'General'** nie są przetłumaczone na język polski 
* _Zalecenie:_ dodanie tłumaczenia 'Web Mech' na 'Mecz w sieci'
* _Zalecenie:_ zmiana tłumaczenia 'General' na 'Ogólne'
  
2. Poniżej testów z poprzedniego punktu interaktywne przyciski **'SUBMIT'** oraz **'CLEAR'** również nie są przetumaczone na język polski
* _Zalecenie:_ dodanie tłumaczenia dla przysisku 'SUBMIT' na 'WYŚLIJ' 
* _Zalecenie:_ dodanie tłumaczenia dla przycisku 'CLEAR' na 'WYCZYŚĆ'
  
3. Uzupełnienie ankiedy dodawania nowego meczu - brak ograniczeń logicznych podczas podawania daty meczu
* _Zalecenie:_ ograniczenie możliwości podania daty tylko do takiej która faktycznie może wystąpić
  
4. Uzupełnienie ankiedy dodawania nowego meczu - brak ograniczeń długości wprowadzanych wartości w ankiecie 
* _Zalecenie:_ ograniczenie ilości znaków wprowadzanych w poszczególnych polach ankiety
  
5. Uzupełnienie ankiedy dodawania nowego meczu - brak czerwonego powiadomienia w przypadku próby zapisu przy jednoczensym braku wyboru jednej z 2 wymaganych opcji 'mecz domowy' lub 'mecz wyjazdowy'. 
* _Zalecenie:_ dodanie czerwonej inforamcji o konieczności wybrania jednej z dwóch opcji
  
6. Uzupełnienie ankiedy dodawania nowego meczu - brak ograniczeń logicznych podczas podawania wartoścli liczbowych - zdobyte gole, stracone gole, data, liga, czas gry, numer
* _Zalecenie:_ ograniczenie tylko do przedziału wartości liczbowych które faktycznie mogą wystąpić 
*               zdobyte gole [0 - 99]
*               stracone gole [0 - 99]
*               data [01.01.1999 - aktualna data]
*               liga [1 - 10]
*               czas gry [0 - 180]
*               numer [1 - 999]
* _Zalecenie:_ dodanie komentarzy po angielsku oraz polsku w przypadku wprowadzenia wartości poza zakresem

7. Okno ankiety **'Recenzja'** jest ograniczone od 0 do 5, w przypadku wprowadzenia wartości ujemnej lub większej niż 5 pojawia się jeden z dwóch komentarzy: **'Wartość nie może być mniejsza niż zero'** lub **'Wartość nie może być większa niż 5'**, komentarze te nie są przetłumaczone na język angielski. 
* _Zalecenie:_ dodanie tłumaczenia dla komenatrza na 'Wartość nie może być mniejsza niż zero' na język angielski 'Value can't be negative' 
* _Zalecenie:_ dodanie tłumaczenia dla komenatrza na 'Wartość nie może być większa niż 5' na język angielski 'Value can't be grater then 5' 

  
<p align="center">========== STRONA TWORZENIE RAPORTU MECZU DLA ISTNIEJĄCEGO GRACZA ==========</>  

1. Przycisk **'DODAJ RAPORT'** przenosi do okna dodawnia meczu a nie do okna dodawnia raportu
* _Zalecenie:_ poprawa akcji przycisku 'DODAJ RAPORT' na aktywację dodania nowego raportu

2. Przycisk **'SAVE'** nie jest przetłumaczony na język polski
* _Zalecenie:_ dodanie tłumaczenia dla przysisku 'SAVE' na 'ZAPISZ'

<p align="center">========== STRONA Z LISTĄ GRACZY ==========</>

1. Opis interaktywnych przycisków nie jest przetłumaczony na język polski. 
* _Zalecenie:_ dodanie tłumaczenia dla opisu przysisku 'Download CSV' na 'Pobierz CSV' 
* _Zalecenie:_ dodanie tłumaczenia dla opisu przysisku 'Print' na 'Drukuj' 
* _Zalecenie:_ dodanie tłumaczenia dla opisu przysisku 'View Columnts' na 'Pokaż kolumny' 
* _Zalecenie:_ dodanie tłumaczenia dla opisu przysisku 'Filter Tables' na 'Filtruj tabelę' 

2. Dodatkowo po wybraniu 'View Columnts' w interaktywnym pop-up tekst **'Show Columns'** nie jest przetłumaczony na język polski.
* _Zalecenie:_ dodanie tłumaczenia dla opisu przysisku 'Show Columns' na 'Pokaż kolumny'

3. Oraz po wybraniu po wybraniu 'Filter Tables' w interaktywnym pop-up teksty **'Filter'**, **'Age'**, oraz **'Rate'**, nie są przetłumaczone na język polski.
* _Zalecenie:_ dodanie tłumaczenia dla 'Filter' na 'Filtruj'
* _Zalecenie:_ dodanie tłumaczenia dla 'Age' na 'Wiek'
* _Zalecenie:_ dodanie tłumaczenia dla 'Rate' na 'Recenzja'

4. Po zastosowanianiu filtów część z nich posiada opis a część ich nie posiada
* _Zalecenie:_ dodanie opisów i tłumaczeń po zastosowaniu filtów 

5. Po najechaniu myszą na dowolny elelemt sortujący tabelę wyskakujący pop-up **'Sort'** nie jest przetłumacziny na język polski
* _Zalecenie:_ dodanie tłumaczenia dla 'Sort' na 'Sortuj'


# Task 2

## Subtask 1

https://docs.google.com/spreadsheets/d/1R3ANkhl0O9SZR40VY1GDoAG7zKr1tzWREOYjkV97Qv8/edit?usp=share_link

## Subtask 2

https://docs.google.com/spreadsheets/d/1FtkVwebzX8ZETDHg50wVG3iLMW6tQMRduzTh_0jd_AI/edit?usp=share_link

## Subtask 3

Pisanie przypadków testowych służy zapewnieniu maksymalnego możliwego spełnienia wymagań klienta oraz upewnienia się o płynnym i stabilnym działaniu testowanej aplikacji.

[![IMAGE ALT TEXT](http://img.youtube.com/vi/cSh551cdIEY/0.jpg)](http://www.youtube.com/watch?v=cSh551cdIEY "Video Title")

## Subtask 4


# Task 3

## Subtask 1

https://drive.google.com/drive/u/0/folders/1ZnCo6U3HzSTGdUYYziAGEhvd0xWXvIsI

## Subtask 2

https://docs.google.com/spreadsheets/d/1Xnv2jcQOmDNjlzsVLvOnNHrBcMAPCUnXIQz2AyD2sTY/edit?usp=share_link

https://docs.google.com/spreadsheets/d/1SGlq0hse7BhK2VIibqDxfvlLoI9V7aunQT8vQW_7qus/edit?usp=share_link

## Subtask 3

https://docs.google.com/document/d/1wWPUudMm7A9zY6bA7yLL2TWSz84dIrl23fCEPduV-SY/edit?usp=share_link
  
## Subtask 4
  
# Task 4

## Subtask 1

https://docs.google.com/spreadsheets/d/1HoRgHtSxrdcjSbUgiMGEH2D69_pVYc2pnSgtjGQo7b0/edit#gid=1696890496

## Subtask 2

https://docs.google.com/spreadsheets/d/1XJRJpZql-bahwatOzSjSns5RILCO3IZR66O9nrQEihg/edit#gid=2123866427

## Subtask 3

Aplikacja służy do wystawiania ogłoszeń sprzedaży lub chęci kupna dóbr i usług. 

Końcowym użytkownikiem ma być każdy użytkownik który szuka konkurencyjnych ofert w Internecie.

Aplikacja jest przyjazna użytkownikowi, działa płynnie. Czcionka, wszystkie ikony oraz przyciski działają prawidłowo i są intuicyjne.

Dodał bym możliwość logowania przy użyciu samej aplikacji. Aplikacja wymusza po wybraniu opcji zaloguj przejścia do przeglądarki internetowej i zalogowania się na stronie internetowej w przeglądarce. Wymaga to posiadania przeglądarki oraz podawania w niej danych naszego logowania. Stwarza to np. zagrożenie przypadkowego zapisania danych logowania w przeglądarce jeśli tego nie chcemy.

