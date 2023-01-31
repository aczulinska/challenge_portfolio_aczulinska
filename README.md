# Task 1

### Subtask 1

7/10

### Subtask 3

Hej, jestem Aurelia :). Zdecydowałam się wziąć udział w challenge'u, ponieważ chcę zdobyć nowe umiejętności i eksplorować zawodowo nowe terytoria. Zdarzyło mi się pracować krótko jako testerka gier i dobrze się w tym odnajdowałam, więc liczę na to, że udział w projekcie pomoże mi rozwinąć się w tej dziedzinie i znależć pracę w branży testerskiej.

### Subtask 4

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

### Subtask 2

Podaję link do raportów z błędów: https://docs.google.com/spreadsheets/d/1SQ8akczTEGS-SMHvnShxcIH8RKwqRIZgGhY9cVQaJVg/edit?usp=share_link

Jako że w poprzednim tygodniu nie oddałam na czas zadania, dołączam jeszcze listę test casów - skończyłam ją po terminie: https://docs.google.com/spreadsheets/d/1HkJUW9s46fnfhBQDLqEdgb2HcbqpSUmJ7htnBapBnuA/edit?usp=share_link

### Subtask 3

Link do raportu z testów: https://docs.google.com/document/d/1pCv0uTS3OnQHTQ313bNToohSMSf6bqduno3BN3T-22c/edit?usp=share_link

*Aura*
