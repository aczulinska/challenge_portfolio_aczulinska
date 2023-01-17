# Task 1

### Subtask 1

7/10

### Subtask 3

Hej, jestem Aurelia :). Zdecydowałam się wziąć udział w challenge'u, ponieważ chcę zdobyć nowe umiejętności i eksplorować zawodowo nowe terytoria. Zdarzyło mi się pracować krótko jako testerka gier i dobrze się w tym odnajdowałam, więc liczę na to, że udział w projekcie pomoże mi rozwinąć się w tej dziedzinie i znależć pracę w branży testerskiej.

### Subtask 4

Na czym polega ta aplikacja? Do czego służy?
* Jest to baza graczy piłki nożnej. Służy do katalogowania graczy, ich danych i raportów z ich meczy

Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)
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

Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
* Wygląd jak wygląd, jest dosyć prosty. Nie wygląda zbyt profesjonalnie, ale nie jest też tragiczny
* Malutka i dosyć losowa uwaga, która mi przyszła do głowy (ale to chyba nie jest bug, tylko kwestia designu, więc piszę to pod tym pytaniem), to że byłoby fajnie, jakby przy przełączaniu między stronami listy była opcja przejścia do jej początku albo na koniec. Bo przy ponad tysiącu pozycji na liście przechodzenie na jej koniec oznacza dużo klikania :O

Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
* Nie wiem, czy domyśliłabym się natychmiast, że jak kliknę w pasek zawodnika na liście (w dowolnym miejscu), to przejdę do edycji zawodnika. Odkryłam to przez przypadek
* Opcja „dodaj język” przy edycji profilu gracza jest dziwna. Jest tylko sam kafelek, a po kliknięciu w niego pojawia się pasek. Z każdym kliknięciem pojawia się nowy pasek. Chyba byłoby lepiej, gdyby pusty pasek był widoczny od początku
* Jak kliknę enter albo submit przy edycji profilu gracza, pojawia mi się popup w prawym górnym rogu, że zapisane, ale zostaję na tej samej stronie, a chyba byłoby bardziej intuicyjnie, gdyby przenosiło mnie z powrotem na listę graczy
* W pewnym momencie przy próbie zapisania zmian w profilu gracza dostałam komunikat „Nie udało się zaktualizować gracza”, ale bez żadnych szczegółów. Powinno się coś podświetlić na czerwono, żebym wiedziała, gdzie jest błąd w formularzu
* Nie wiem, czy to się liczy do oceny intuicyjności, ale nie mam pojęcia, co powinno być wpisane w pola "General" i "Web match" w formularzu dodawania meczy
* Kiedy kliknę "Dodaj raport" na stronie z listą raportów, zostaję przeniesiona do listy meczy, co jest zupełnie nieintuicyjne. Domyślam się, że chodzi o to, że raport powinien być dodany do konkretnego meczu, ale w takim razie przycisk "Dodaj raport" nad listą raportów jest zbędny, bo i tak muszę potem kliknąć "Dodaj raport" przy konkretnym meczu
* Nie mam pojęcia, o co chodzi z ekranem „Tworzenie raportu XYZ dla meczu”, który pojawia się po kliknięciu "Dodaj raport" przy meczu - tym, w którym pojawia się ID gracza i ID meczu. Nic nie można edytować, przycisk „Clear” nic nie robi
* Tak jak już wcześniej wspomniałam, funkcjonalność "Rozpocznij mecz" jest dla mnie kompletnie nieintuicyjna i nie połapałam się do końca, o co w niej chodzi :O
* Dostęp do meczy i raportów jest dla mnie trochę dziwny. Nie podoba mi się, że na stronie głównej widoczna jest tylko zakładka z graczami, a po kliknięciu w konkretnego gracza zakładki z meczami i raportami pojawiają się w tym samym miejscu i w takim samym stylu - czuję, że powinno być jakoś zasygnalizowane, że są to jakby podzakładki, przypisane do strony konkretnego gracza
* Na stronie edycji profilu zawodnika linki do youtube dodaje się tak samo jak języki, ale nie ma to za bardzo sensu. Albo wszystkie tego typu rzeczy powinno się dodawać na tej zasadzie, albo żadne

Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)
* Wybór kolumn listy, filtry i przyciski „submit” i „clear” są po angielsku, a reszta strony po polsku
* Na ogół ma ograniczenia dla liczby znaków - jeśli np. wprowadzę bardzo długie imię zawodnika, to strona się rozszerza
* Po kliknięciu w pole „Waga” w ekranie tworzenia/edycji profilu zawodnika rozwija nam się lista jakichś bezsensownych liczb
* Jeśli wpiszę nieprawidłowy adres email w polu tworzenia/edycji zawodnika, nie mogę zapisać zmian, ale nie dostaję żadnej informacji, dlaczego. Powinien wyświetlać się jakiś komunikat typu „nieprawidłowy adres email” i pole powinno się podświetlić na czerwono
* W polu telefon mogę wpisywać litery i jakiekolwiek inne znaki - wszystko się zapisuje bez problemu 
* Kiedy klikam clear przy robieniu profilu gracza, cofa to zmiany wprowadzone w tej sesji, ale zostaje język. Czasem usuwa wszystkie otwarte przeze mnie pola „język”, a czasem żadnego. Nie wiem, to działa jakoś nieprzewidywalnie. Potem w edycji meczu też niektóre rzeczy usuwa, niektóre nie, niektóre potem wracają
* jak usunę dane z profilu gracza, zapiszę z sukcesem, a potem cofnę się do listy i kliknę tego gracza jeszcze raz, to usunięte przeze mnie dane wracają na miejsce i wcale się nie usunęły. Podobnie nieprzewidywalnie to działa z edycją meczy
* da się dodawać minusowe wartości wagi i wzrostu (i innych rzeczy – obczaj, jakich)
* da się dodawać daty meczy z przyszłości
* w symulacji meczu da się dodawać nieskończoną liczbę połów, a potem i tak ta informacja się nigdzie nie pojawia (chyba)
* przy przypomnieniu hasła w polu email można wpisać cokolwiek albo nawet nic, a po kliknięciu „wyślij” i tak dostajemy komunikat, że wiadomość została wysłana na podany adres email. W backlogu pojawia się za to komunikat o błędzie 400
* komunikaty o błędach na stronie logowania są po angielsku, nawet jeśli wybrany język to polski
* w polach wiek w filtrach można wpisywać litery i i tak dostajemy wyniki
* jeśli zastosujemy filtry na liście graczy, a potem je wyczyścimy je poprzez przycisk „reset”, nie wracamy już do pełnej listy – strona cały czas pokazuje nam przefiltrowaną listę
* język angielski w nagłówkach w raporcie
* po przejściu na offline nie dostajemy tylko komunikat „Wystąpił błąd! Error:Failed to fetch. Skontaktuj się z administratorem.” po próbie wejścia w zakładkę gracze, a dane na stronie głównej się zerują. Jeśli nie wiemy, że nie działa nam internet, nie mamy pojęcia, co jest źródłem błędu – powinno nas poinformować, że nie mamy połączenia
* przy wolnym połączeniu lista graczy wczytuje się baaaaaaardzo wooooooolno, ale po kliknięciu w zakładkę nic się nie dzieje – nie pokazuje się nic, co by wskazywało na to, że strona się ładuje i trzeba poczekać
* na wersji mobilnej strony, kiedy przechodzimy na następną stronę w liście graczy, nie zostajemy automatycznie przeniesieni na górę strony – musimy sami przescrollować
* listy meczy i raportów nie dostosowują się w żaden sposób w wersji mobilnej – trzeba przewijać stronę horyzontalnie, co jest trochę męczące. Raporty z meczy też nie dostosowują się w żaden sposób
* wizualizacja boiska rozciąga się w zależności od parametrów ekranu urządzenia (dotyczy to też kafelków, które pojawiają się po kliknięciu w boisko)
* W pewnym momencie pojawiła się informacja o niezapisanym meczu na stronie głównej. Jest przycisk „wróć do raportu”, ale nic się nie dzieje, jak w niego klikamy. W devtoolsach dostajemy za to komunikat: Uncaught (in promise) Error: The provided `as` value (/pl/players/63c689b24cff3d0bdc15293e/reports/start) is incompatible with the `href` value (/players/[id]/reports/start).

Mam jeszcze bardzo drobne, marginalne uwagi, które nie wiem, czy również powinny być przeze mnie jako testera zgłaszane:

* Błąd językowy – powinno być „liczba” zamiast „ilość”

*Aura*
