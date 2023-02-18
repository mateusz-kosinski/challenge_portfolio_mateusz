# challenge_portfolio_mateusz

# Task 1

## Subtask 1


* 6/10 punktow

## Subtask 2

https://github.com/mateusz-kosinski

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
  
# Task 4

## Subtask 1

https://docs.google.com/spreadsheets/d/1HoRgHtSxrdcjSbUgiMGEH2D69_pVYc2pnSgtjGQo7b0/edit#gid=1696890496

## Subtask 2

https://docs.google.com/spreadsheets/d/1XJRJpZql-bahwatOzSjSns5RILCO3IZR66O9nrQEihg/edit#gid=2123866427

## Subtask 3

Aplikacja służy do wystawiania ogłoszeń sprzedaży lub chęci kupna dóbr i usług. 

Końcowym użytkownikiem ma być każdy użytkownik który szuka konkurencyjnych ofert w Internecie.

Aplikacja jest przyjazna użytkownikowi, działa płynnie. Czcionka, wszystkie ikony oraz przyciski działają prawidłowo i są intuicyjne. Znaczna ilość wyskakujących powiadomień pop-up na głównym ekranie po każdorazowym uruchomieniu aplikacji opóźnia i pogarsza płynne rozpoczęcie wyszukiwania.

Dodał bym możliwość logowania przy użyciu samej aplikacji. Aplikacja wymusza po wybraniu opcji zaloguj przejścia do przeglądarki internetowej i zalogowania się na stronie internetowej w przeglądarce. Wymaga to posiadania przeglądarki oraz podawania w niej danych naszego logowania. Stwarza to np. zagrożenie przypadkowego zapisania danych logowania w przeglądarce jeśli tego nie chcemy.
  
# Task 5

## Subtask 1

https://www.kursysql.pl/szkolenie-sql-w-120-minut/
  
SELECT, FROM, WHERE, AS, AND, ORDER BY 

## Subtask 2

https://www.apachefriends.org/pl/index.html

## Subtask 3

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
  
  * SELECT * FROM `actors` ORDER BY `surname`;
  
  ![001](https://user-images.githubusercontent.com/122534305/218305229-bba7f7a1-fef2-490c-9e3b-760b099a7213.JPG)

  
2. Wyświetl film, który powstał w 2019 roku.
  
  * SELECT * FROM `movies` WHERE `year_of_production` = 2019;
  
  ![002](https://user-images.githubusercontent.com/122534305/218305240-b6221eab-6bc7-4de8-863f-a2b5fd717454.JPG)

  
3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
  
  * SELECT * FROM `movies` WHERE `year_of_production` > 1900 AND `year_of_production` < 1999;
  
  ![003](https://user-images.githubusercontent.com/122534305/218305248-61b65858-78bc-4880-939d-f526ae59909b.JPG)

  
4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
  
  * SELECT `title`, `price` FROM `movies` WHERE `price` < 7;
  
  ![004](https://user-images.githubusercontent.com/122534305/218305256-27965f7c-6beb-42fe-9fec-81586b3b706f.JPG)

  
5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
  
  * SELECT * FROM `actors` WHERE `actor_id` >= 4 AND `actor_id` <= 7;
  
  ![005](https://user-images.githubusercontent.com/122534305/218305270-8cbfa2f8-f5bf-4485-bf7f-d4d3af6b3715.JPG)
                                                                  
                                                                    
6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
  
  * SELECT * FROM `customers` WHERE `customer_id` = 2 OR `customer_id` = 4 OR `customer_id` = 6;
  
  ![006](https://user-images.githubusercontent.com/122534305/218305282-5d54ff7f-f28f-40cf-a68c-5b43e4a2f720.JPG)
                                                                                                                          
7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
  
  * SELECT * FROM `customers` WHERE `customer_id` IN (1,3,5);
  
  ![007](https://user-images.githubusercontent.com/122534305/218305297-c5f8dec9-3f6f-4017-bdc6-a57eda2f897b.JPG)
                                                                                                                               
8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
  
  * SELECT * FROM `actors` WHERE `name` LIKE 'An%';
  
  ![008](https://user-images.githubusercontent.com/122534305/218305308-e9057e04-50b9-47fa-898d-dd293c7baa6c.JPG)
                                                                                                                                     
9. Wyświetl dane klienta, który nie ma podanego adresu email.
  
  * SELECT * FROM `customers` WHERE `email` IS NULL;
  
 ![009](https://user-images.githubusercontent.com/122534305/218305314-185e65fb-4a86-4c9e-a0f2-c093a0374753.JPG)
                                                                                                                                     
10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

  * SELECT * FROM `movies` WHERE `price` > 9 AND `movie_id` IN (2,3,4,5,6,7,8);

![010](https://user-images.githubusercontent.com/122534305/218305326-1dc414ae-eafb-41f3-a123-eaa917734eaf.JPG)

# Task 5

##Subtask 1

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
  
  * UPDATE customers SET surname='Miler' WHERE customer_ID=3;
  
  ![image](https://user-images.githubusercontent.com/122534305/219851233-1ff18f7a-af68-4c61-99c4-ff1035ef4682.png)

  ![image](https://user-images.githubusercontent.com/122534305/219851245-06364c46-3876-45a8-afc1-ab81dbc0477d.png)

  
  12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
  
  
  
13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
  
  ![image](https://user-images.githubusercontent.com/122534305/219853028-2bc3394c-3561-4339-8ec2-8f289a3057be.png)

  ![image](https://user-images.githubusercontent.com/122534305/219853054-50fc5442-47f6-4cd9-b969-53de967b0a1e.png)

  
14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
  
  
  
15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag
  
  
  
16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.
  
  
  
17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)
  
  
  
18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).
  
  
  
19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał
  
  
  
20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa
  
  
##Subtask 2

##Subtask 3


