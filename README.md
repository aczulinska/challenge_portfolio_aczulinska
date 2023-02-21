# Task 1

## Subtask 1

7/10

## Subtask 3

Hej, jestem Aurelia :). Zdecydowałam się wziąć udział w challenge'u, ponieważ chcę zdobyć nowe umiejętności i eksplorować zawodowo nowe terytoria. Zdarzyło mi się pracować krótko jako testerka gier i dobrze się w tym odnajdowałam, więc liczę na to, że udział w projekcie pomoże mi rozwinąć się w tej dziedzinie i znależć pracę w branży testerskiej.

## Subtask 4

**Na czym polega ta aplikacja? Do czego służy?**
* Jest to baza graczy piłki nożnej. Służy do katalogowania zawodników, ich danych i raportów z ich meczy

**Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)**
* logowanie
* wylogowanie
* przypomnienie hasła
* licznik graczy, meczy, raportów i akcji na stronie głównej
* dodawanie graczy (wprowadzanie danych gracza)
* link do kontaktu z dev teamem (przekierowuje na Slacka)
* lista ostatnich aktywności na stronie (dodani gracze itp.)
* lista graczy z ich danymi
* opcja drukowania listy graczy
* opcja pobierania listy graczy jako csv
* wybór kolumn, z których składać się ma lista graczy
* zawężanie pozycji na liście graczy poprzez filtry
* wyświetlanie i edycja profili graczy
* dodawanie meczy dla poszczególnych zawodników (wprowadzanie informacji na temat meczu, takich jak wynik itp.)
* edycja istniejących meczy
* tworzenie i edycja raportów z meczy (sprawozdanie z meczu i ocena, jak gracz w danym meczu się spisał)
* prosty edytor tekstu w edycji raportów (rozmiar fontu, pogrubienie, kursywa itp.)
* opcja „rozpocznij mecz” - symulacja meczu? Nie jestem pewna, do czego to służy i jak prawidłowo używać tej funkcjonalności. Jak dla mnie nie jest to intuicyjne
* zmiana języka strony na angielski (lub z powrotem na polski)

**Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**
* Wygląd jak wygląd, jest dosyć prosty. Szczerze mówiąc, nie wygląda zbyt profesjonalnie
* Malutka i dosyć losowa uwaga, która mi przyszła do głowy (ale to chyba nie jest bug, tylko kwestia designu, więc piszę to pod tym pytaniem), to że byłoby fajnie, jakby przy przełączaniu między stronami listy była opcja przejścia do jej początku albo na koniec. Bo przy ponad tysiącu pozycji na liście przechodzenie na jej koniec oznacza dużo klikania :O

**Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).**
* Nie wiem, czy domyśliłabym się natychmiast, że jak kliknę w pasek zawodnika na liście (w dowolnym miejscu), to przejdę do edycji zawodnika. Odkryłam to przez przypadek. Na pozostałych listach (meczy i raportów) jeśli chcę edytować daną pozycję, muszę kliknąć ikonkę po prawej
* Jeśli kliknę "Enter" albo "Submit" przy edycji profilu gracza, w prawym górnym rogu pojawia się informacja, że zmiany zapisane, ale zostaję na tej samej stronie. Chyba byłoby bardziej intuicyjnie, gdyby przenosiło mnie z powrotem na listę graczy
* W pewnym momencie przy próbie zapisania zmian w profilu gracza dostałam komunikat „Nie udało się zaktualizować gracza”, ale bez żadnych szczegółów. Powinno się coś podświetlić na czerwono, żebym wiedziała, gdzie jest błąd w formularzu
* Nie wiem, czy to się liczy do oceny intuicyjności, ale nie mam pojęcia, co powinno być wpisane w pola "General" i "Web match" w formularzu dodawania meczy
* Kiedy kliknę "Dodaj raport" na stronie z listą raportów, zostaję przeniesiona do listy meczy, co jest zupełnie nieintuicyjne. Domyślam się, że chodzi o to, że raport powinien być dodany do konkretnego meczu, ale w takim razie przycisk "Dodaj raport" nad listą raportów jest zbędny, bo i tak muszę potem kliknąć "Dodaj raport" z poziomu listy meczy
* Nie mam pojęcia, o co chodzi z ekranem „Tworzenie raportu XYZ dla meczu”, który pojawia się po kliknięciu "Dodaj raport" przy meczu - tym, w którym pojawia się ID gracza i ID meczu. Nic nie można edytować, przycisk „Clear” nic nie robi

![tworzenie raportu](https://user-images.githubusercontent.com/122446669/212965353-d0b3880a-15ba-4c0b-be20-0cbffb57d4de.png)

* Tak jak już wcześniej wspomniałam, funkcjonalność "Rozpocznij mecz" jest dla mnie kompletnie nieintuicyjna i nie połapałam się do końca, do czego ona dokładnie służy :(
* Dostęp do meczy i raportów jest dla mnie trochę dziwny. Nie podoba mi się, że na stronie głównej widoczna jest tylko zakładka z graczami, a po kliknięciu w konkretnego gracza zakładki z meczami i raportami pojawiają się w tym samym miejscu i w takim samym stylu - czuję, że powinno być jakoś zasygnalizowane, że są to jakby podzakładki, przypisane do strony konkretnego gracza
* Na stronie edycji profilu zawodnika linki do Youtube i języki dodaje się w inny sposób niż pozostałe dane - nie dostajemy pojedynczego pola do wypełnienia, tylko możemy tworzyć dowolną ilość pól za pomocą dedykowanego przycisku. Wydaje się, że są np. "Osiągnięcia" też mogłyby być wprowadzane w ten sposób. Byłoby bardziej konsekwentnie

**Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)**
* Na ogół ma ograniczenia dla liczby znaków - jeśli np. wprowadzę bardzo długie imię zawodnika, to strona się rozszerza

https://user-images.githubusercontent.com/122446669/212934537-b3030c34-a39a-4a8c-8399-4c071852072e.mp4

* Po kliknięciu w pole „Waga” w ekranie tworzenia/edycji profilu zawodnika rozwija nam się lista jakichś przypadkowych liczb

![bug_waga](https://user-images.githubusercontent.com/122446669/212961149-3e7971bc-461e-4137-9cc0-b7c8b7caaf69.png)

* Jeśli wpiszę nieprawidłowy adres email w polu tworzenia/edycji zawodnika, nie mogę zapisać zmian, ale nie dostaję żadnej informacji, dlaczego. Powinien wyświetlać się jakiś komunikat typu „nieprawidłowy adres email” i pole powinno się podświetlić na czerwono

https://user-images.githubusercontent.com/122446669/212935302-a2e17352-81fd-42f6-8a5a-e824dfeacd2c.mp4

* W polu telefon mogę wpisywać litery i jakiekolwiek inne znaki - wszystko się zapisuje bez problemu 
* Przycisk "Clear" przy edycji profilu gracza wydaje się bardzo popsuty i działa nieprzewidywalnie - na ogół cofa zmiany wprowadzone w danej sesji, ale nie radzi sobie z wprowadzonymi językami. Czasem usuwa wszystkie otwarte przeze mnie pola „język”, a czasem żadnego. W edycji meczu też niektóre rzeczy usuwa, niektóre nie, niektóre potem wracają
* Jak usunę dane z profilu gracza, zapiszę z sukcesem, a potem cofnę się do listy i kliknę tego gracza jeszcze raz, to usunięte przeze mnie dane wracają na miejsce i wcale się nie usunęły. Podobnie nieprzewidywalnie to działa z edycją meczy

https://user-images.githubusercontent.com/122446669/212961789-d6867a2c-2a6c-4221-80d4-1a4663767ff1.mp4

* Da się dodawać ujemne wartości wagi i wzrostu
* Da się dodawać daty meczy z przyszłości
* W symulacji meczu da się dodawać nieskończoną liczbę połów
* Przy przypomnieniu hasła w polu email można wpisać cokolwiek albo nawet nic, a po kliknięciu „wyślij” i tak dostajemy komunikat, że wiadomość została wysłana na podany adres email. W backlogu pojawia się za to komunikat o błędzie 400

https://user-images.githubusercontent.com/122446669/212956160-fdfa0f05-3af6-4e01-9591-2984bc336107.mp4

* jeśli zastosujemy filtry na liście graczy, a potem wyczyścimy je poprzez przycisk „reset”, nie wracamy już do pełnej listy – strona cały czas pokazuje nam przefiltrowaną listę

https://user-images.githubusercontent.com/122446669/212956283-37c096ad-b667-479f-9651-e49539d51f62.mp4

* Wizualizacja boiska rozciąga się w zależności od rozmiarów ekranu urządzenia (dotyczy to też kafelków, które pojawiają się po kliknięciu w boisko)

https://user-images.githubusercontent.com/122446669/212958605-21a321b9-31f4-48e3-8c1e-6d1de37f8116.mp4

![bug_rozciągnięte kafelki](https://user-images.githubusercontent.com/122446669/212958633-4f1b94c3-8b15-4f0a-b684-dfb7a06aec3b.png)

* W pewnym momencie pojawiła się informacja o niezapisanym meczu na stronie głównej. Jest przycisk „wróć do raportu”, ale nic się nie dzieje, jak w niego klikamy. W devtoolsach dostajemy za to komunikat: Uncaught (in promise) Error: The provided `as` value (/pl/players/63c689b24cff3d0bdc15293e/reports/start) is incompatible with the `href` value (/players/[id]/reports/start)

https://user-images.githubusercontent.com/122446669/212958707-2d2fad0d-3fd0-465e-8d0c-80fb925aee05.mp4

* Zdarzyło się raz, że przy edytowaniu meczu licznik czasu zaczął błędnie wyświetlać sekundy - na zmianę wyświetlał prawidłową i powiększoną o 1 liczbę dziesiątek. Nie wiem jednak, co spowodowało ten błąd - nie udało mi się go wywołać ponownie

https://user-images.githubusercontent.com/122446669/212960396-4ed554dd-8454-4bf5-9ade-c01494a18308.mp4


Mam jeszcze bardzo drobne, marginalne uwagi, co do których mam wątpliwości, czy również powinny być przeze mnie jako testera zgłaszane:

* Błąd językowy – powinno być „liczba” zamiast „ilość” w licznikach na stronie głównej
* Literówka - "pozycja alternatywa" zamiast "alternatywna" w edycji profilu gracza

![bug_pozycja alternatywa](https://user-images.githubusercontent.com/122446669/212936022-6d3905ee-b60d-49a0-94e8-200bf2993d7f.png)

* Niektóre teksty na stronie są po angielsku, nawet jeśli wybrany język to polski: komunikaty o błędach na stronie logowania, przyciski "Submit" i "Clear", nagłówki w raporcie, "Dev team contact" na stronie głównej, podpisy do niektórych ikonek ("View Columns" i "Filter Table"), filtry, wybór kolumn
* W polach "Wiek" w filtrach można wpisywać litery
* Po utracie połączenia z internetem jedyne, co się dzieje, to pojawienie się komunikatu „Wystąpił błąd! Error:Failed to fetch. Skontaktuj się z administratorem.” po próbie wejścia w zakładkę gracze oraz wyzerowanie danych na stronie głównej. Jeśli nie zauważymy, że nie działa nam internet, nie mamy pojęcia, co jest źródłem błędu – wydaje mi się, że strona powinna nas poinformować, że nie mamy połączenia
* Przy wolnym połączeniu internetowym po kliknięciu w zakładkę "Gracze" nic się nie dzieje - nie zmienia się kursor, nie widać nigdzie żadnego sygnału, że strona się ładuje. Ostatecznie lista wczytuje się, ale myślałam już, że po prostu przestała działać - nie wiem, czy jest to coś do poprawy
* Na wersji mobilnej strony, kiedy przechodzimy na następną stronę w liście graczy, nie zostajemy automatycznie przeniesieni na górę strony – musimy sami przescrollować, co jest nieco uciążliwe, bo lista robi się bardzo długa
* Listy meczy i raportów nie dostosowują się w żaden sposób w wersji mobilnej – trzeba przewijać stronę horyzontalnie, co jest trochę męczące. Raporty z meczy też nie dostosowują się w żaden sposób

# Task 3

## Subtask 2

Podaję link do raportów z błędów: https://docs.google.com/spreadsheets/d/1SQ8akczTEGS-SMHvnShxcIH8RKwqRIZgGhY9cVQaJVg/edit?usp=share_link

Jako że w poprzednim tygodniu nie oddałam na czas zadania, dołączam jeszcze listę test casów - skończyłam ją po terminie: https://docs.google.com/spreadsheets/d/1HkJUW9s46fnfhBQDLqEdgb2HcbqpSUmJ7htnBapBnuA/edit?usp=share_link

## Subtask 3

Link do raportu z testów: https://docs.google.com/document/d/1pCv0uTS3OnQHTQ313bNToohSMSf6bqduno3BN3T-22c/edit?usp=share_link

# Task 4

## Subtask 2

Link do zgłoszonych błędów: https://docs.google.com/spreadsheets/d/1Vx_boYUfpGKla9xj5DWMIIp1GNEDuQhpBZNPPR-81eI/edit?usp=sharing

## Subtask 3

**Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?**

* Aplikacja ta służy do zamieszczania i wyszukiwania lokalnych ogłoszeń. Można za jej pośrednictwem sprzedawać i kupować przedmioty, zamieszczać i odpowiadać na oferty pracy, oferować i znajdować usługi itp.

**Kto ma być użytkownikiem końcowym aplikacji?**

* Użytkownikiem końcowym aplikacji mają być głównie osoby prywatne chcące coś sprzedać, kupić, znaleźć lokalne ogłoszenia, wymienić się usługami itp. Firmy również mogą zamieszczać i odpowiadać na ogłoszenia.

**Czy według Ciebie aplikacja jest user friendly?**

* Generalnie tak, chociaż niektóre kategorie i zakładki wydają mi się mało intuicyjne, np. oczekujące ogłoszenia

**Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?**

* Uprościłabym nieco formularz tworzenia ogłoszenia, ponieważ jak na razie jest nieco chaotyczny i łatwo pominąć jakiś podpunkt. Jest też w nim sporo błędów, które czynią cały proces nieco topornym. Dopracowałabym też sposób wyświetlania ogłoszeń w wyszukiwarce, aby layout był bardziej przejrzysty - przez różnice w rozmiarach kafelków i mieszanie zwykłych ogłoszeń z tymi wyróżnionymi (które nie reagują na szczegółowe filtry) można pogubić się w tym, które ogłoszenia już się oglądało.

**Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej a natywnej?**

* W przypadku aplikacji natywnych więcej zależy od urządzenia, na którym testujemy - wydaje się, że model urządzenia i system operacyjny odgrywają tu większą rolę niż w przypadku aplikacji internetowych, więc testowanie na wielu różnych urządzeniach staje się bardzo ważne
* Aplikacje natywne stwarzają więcej okazji do testowania, jak dana apka współpracuje z hardware'em urządzenia, np. korzystając z kamery
* Aplikacje natywne wydają się mniej stabilne

# Task 5

## Subtask 1

### Zapytania:
* SELECT X FROM Y - wyświetla kolumny ze wskazanej tabeli
* SELECT TOP - wyświetla 10 pierwszych wyników zgodnie z wybranym kluczem sortowania
* ORDER BY X - sortuje wyniki wg wybranej kolumny
* GROUP BY X - grupuje wyniki wg wskazanej kategorii
* WHERE X - filtruje wg wskazanej wartości
* X AS Y - nadaje alias wybranej nazwie
* GO - oddziela od siebie wsady

### Funkcje:
* GETDATE () - zwraca bierzącą datę
* DATEDIFF (HOUR/MONTH/DAY/YEAR, X, Y) - zwraca różnicę między datą X a datą Y
* UPPER(X) - wyświetla X wielkimi literami
* COUNT(X) - zlicza liczbę wierszy
* MIN(X) - zwraca minimalną wartość ze wskazanej kolumny
* SUM(X) - sumuje wartości ze wskazanej kolumny

### Operatory:
* JOIN - łączenie tabel
* IN
* OR
* AND
* LIKE
* IS (NOT) NULL
* BETWEEN X AND Y
* <,>,=,<>


## Subtask 3

**Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**
* SELECT * FROM actors ORDER BY surname

![T5S3_1](https://user-images.githubusercontent.com/122446669/218714536-b6623c87-6c36-457f-80a8-795972df28ef.png)

**Wyświetl film, który powstał w 2019 roku.**
* SELECT * FROM movies WHERE year_of_production = 2019

![T5S3_2](https://user-images.githubusercontent.com/122446669/218715286-9f79cdd2-e573-409c-8c63-185fea770fce.png)

**Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**
* SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999

![T5S3_3](https://user-images.githubusercontent.com/122446669/218715719-036f95c3-e83e-47a8-9244-b3de3d5c760a.png)

**Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$**
* SELECT title, price FROM movies WHERE price < 7

![T5S3_4](https://user-images.githubusercontent.com/122446669/218716309-afc46af5-c114-495c-a796-82d44ddeaf2a.png)

**Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**
* SELECT * FROM actors WHERE actor_id < 8 AND actor_id > 3

![image](https://user-images.githubusercontent.com/122446669/218717452-6d1b4970-cf7e-4a5c-ba48-039692fbdab0.png)

**Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**
* SELECT * FROM customers WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6

![T5S3_6](https://user-images.githubusercontent.com/122446669/218720748-d266b816-af31-4298-9964-0394e5878587.png)

**Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**
* SELECT * FROM customers WHERE customer_id IN (1,3,5)

![T5S3_7](https://user-images.githubusercontent.com/122446669/218718895-f875daf5-ea3d-4703-8adf-29fa3f59ccae.png)

**Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**
* SELECT * FROM actors WHERE name LIKE 'An%'

![T5S3_8](https://user-images.githubusercontent.com/122446669/218719164-318ca18c-61a8-482b-8e22-aacc47fbeaee.png)

**Wyświetl dane klienta, który nie ma podanego adresu email.**
* SELECT * FROM customers WHERE email IS NULL

![image](https://user-images.githubusercontent.com/122446669/218719577-ce3754bd-1132-486e-ba3c-350ff9bb3e37.png)

**Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**
* SELECT * FROM movies WHERE price > 9 AND movie_id BETWEEN 2 AND 8

![T5S3_10](https://user-images.githubusercontent.com/122446669/218720071-f7183fe1-04cd-42c0-94c5-8b1c330cec71.png)


# Task 6

## Subtask 1

**Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈**
* UPDATE customers

SET surname = 'Miler'

WHERE customer_id = 3

![T6S1_11](https://user-images.githubusercontent.com/122446669/220315209-fe09563e-ed77-4890-9a07-39e3f6ff7166.png)


**Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**
* SELECT * FROM customers

JOIN sale

ON customers.customer_id = sale.customer_id

(mail to katia@mail.com)

![T6S1_12](https://user-images.githubusercontent.com/122446669/220315432-1e63e8f5-864d-44b6-9de6-a3d7f9da0d27.png)


**Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**
* UPDATE customers

SET email = 'pati@mail.com'

WHERE customer_id = 4

![T6S1_13](https://user-images.githubusercontent.com/122446669/220315496-45adea20-39c7-44da-96f7-8c88cbde8ff3.png)


**Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**
* SELECT sale.customer_id, name, surname, sale.movie_id, title

FROM sale

INNER JOIN customers ON sale.customer_id = customers.customer_id

INNER JOIN movies ON sale.movie_id = movies.movie_id

![T6S1_14](https://user-images.githubusercontent.com/122446669/220315541-dd74ec53-b1db-4e40-8450-521f327e7a5c.png)


**W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag**
* ALTER TABLE customers ADD pseudonym char(3)

* UPDATE customers SET pseudonym = CONCAT(LEFT(name, 2), RIGHT(surname, 1))

![T6S1_15](https://user-images.githubusercontent.com/122446669/220315671-9a0ba58a-4ee3-4308-83ae-40bed884b79b.png)


**Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**
* SELECT DISTINCT title FROM movies

JOIN sale ON movies.movie_id = sale.movie_id

ORDER BY title

![T6S1_16](https://user-images.githubusercontent.com/122446669/220315708-5600f212-e2ef-4df7-9caa-b05f18e9235e.png)


**Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)**
* SELECT name FROM customers

UNION

SELECT name FROM actors

ORDER BY name

![T6S1_17](https://user-images.githubusercontent.com/122446669/220315761-78f2cabf-a472-49ed-b134-5a958469fb78.png)


**Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).**
* UPDATE movies

SET price = price+ 2.5

WHERE year_of_production > 2000

![T6S1_18](https://user-images.githubusercontent.com/122446669/220315796-fb78e215-cc7c-46c4-a445-0f3e32bd21da.png)


**Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał**
* SELECT name, surname, title FROM actors

JOIN cast ON actors.actor_id = cast.actor_id

JOIN movies ON movies.movie_id = cast.movie_id

WHERE actors.actor_id = 4

![T6S1_19](https://user-images.githubusercontent.com/122446669/220315823-85003066-d3c8-4047-b839-38edff7cb358.png)


**A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa**
* INSERT INTO customers (customer_id, name, surname, email, pseudonym)

VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')

![T6S1_20](https://user-images.githubusercontent.com/122446669/220315857-4d63290b-fa32-4363-9ede-e2aa330f1c44.png)


## Subtask 2

![T6S2](https://user-images.githubusercontent.com/122446669/220338729-a0933131-d258-493d-9019-4670548ff65a.png)

## Subtask 3

[Link do nowego repozytorium z porftolio](https://github.com/aczulinska/Portfolio/blob/a6b570592efba22922456ccf5e71fdfa5c36575b/README.md)

*Aura*
