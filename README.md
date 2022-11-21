# challenge_portfolio_Edyta

## TASK 1

### Subtask 1

10 punktów :) 


### Subtask 3

Cześć ! Nazywam się Edyta. Obecnie pracuję w firmie telekomunikacyjnej jako st.konsultant ds. reklamacji i obsł. kl. W pracy zdarzało mi się testować aplikacje webowe "na produkcji". Dzięki temu zainteresowałam się tematem. Wzięłam udział w projekcie, ponieważ chciałabym przebranżowić się na testera oprogramowania. Już od jakiegoś czasu o tym myślałam i w końcu odważyłam się zrobić pierwszy krok ! Nie ukrywam, że z teorią zapoznałam się trochę wcześniej. 

Wierzę, że udział w projekcie pozwoli mi wejść do świata IT. Oprócz suchej teorii, przydałoby się również trochę praktyki - dlatego między innymi tu jestem. Jeszcze długa droga przede mną, ale jak to mówią - małymi kroczkami do przodu :)

##### Edyta 

### Subtask 4

1. Aplikacja scouts-test.futbolkolektyw jest wersją testową aplikacji, w której możemy poćwiczyć swoje umiejętności. Umożliwia przeglądanie wskaźników, umiejętności i pozycje zawodników. Umożliwia zarządzanie graczami, meczami i pozwala tworzyć raporty. O funkcjonalnościach piszę niżej.

Aplikację uruchomiłam na urządzeniu: MacBookAir10,1; wersja oprogramowania: MacOS Monterey 12.2.1; przeglądarka: Safari.
Sprawdziłam również działanie aplikacji w przeglądarce Opera oraz jak wyświetla się strona na urządzeniach: iPhone SE, iPhone XR, iPhone 12 Pro, Pixel 5, Samsung Galaxy s8+, Samsung Galaxy s20 Ultra, iPad Air, iPad Mini, Surface Pro 7, Surface Duo, Galaxy Fold, Samsung Galaxy A51, Nest Hub Max - na wszystkich powyższych rozdzielczościach aplikacja uruchamia się bez zarzutu.

2. Funkcjonalności:

- logowanie do aplikacji;
- wylogowanie z aplikacji;
- dodanie nowego gracza/edycja;
- dodanie nowego raportu;
- zmiana języka;
- wyszukiwanie graczy;
- pobieranie pliku w formacie csv;
- drukowanie raportów;
- filtrowanie;
- dodawanie meczów/ edycja;
- tworzenie raportów/ edycja.

3. Błędy/uwagi:

- Interfejs aplikacji jest nieprzyjemny dla oka, nieintuicyjny;
- logo znajduje się na środku strony, zamiast w lewym górnym rogu;
- "ilość meczy" -> powinno być "ilość meczów";
- w panelu bocznym przy wyborze języka polskiego informacje wyświetlane są w języku angielskim i odwrotnie. Przy ustawionym języku polskim widnieje "English",a przy angielskim "Polski";
- przy ustawionym języku na polski, niektóre elementy wyświetlają się w języku angielskim : na stronie głownej -> "Scouts Panel", w zakładce "Gracze" -> "Download CSV","Print","View Columns","Filter Tables", "Search". Przy edycji i tworzeniu gracza przyciski "Clear", "Submit";
- nie działa przycisk lupki w polu "Search". Możliwość wyszukania danej frazy poprzez kliknięcie w enter;
- po wpisaniu "]" w pole "Search" wyświetla się komunikat "Sorry, no matching records found" przy ustawionym języku polskim;
- po najechaniu na "Scouts Panel" kursor zmienia się na poziomą kreskę wprowadzania danych. Po kliknięciu w "Scouts Panel" nie przekierowuje do panelu;
- w zakładce gracze brakuje opcji "dodaj gracza";
- przy włączeniu okienka "dodaj gracza" pole data urodzenia jest od razu wypełnione z aktualną datą;
- możliwość dodania gracza po wypełnieniu pól "Imie", "Nazwisko", "Głowna pozycja" spacją - nie wypełniając pozostałych pól;
- przy tworzeniu nowego gracza, po kliknięciu "Submit" wyświetla się komunikat: "Nie udało się dodać gracza" bez informacji dlaczego, bez podświetlenia które pola zostały błędnie wypełnione;
- udało się dodać gracza z Imieniem "qwe123!@#" i Nazwiskiem "!QWE", udało się też zapisać Imie "1222333", Nazwisko "566777777555" ,z datą urodzeenia 01.02.2023 oraz 31.05.2026, telefon "kfjjf4", waga "0";"-8999", wzrost "0";"-90000000000888", Główna pozycja "-23456788";
- w edycji użytkownika, po kliknięciu w przycisk "clear" pozostaje wypełnione pole "Imie", "Nazwisko", "Data urodzenia", "Dominująca noga", "Główna pozycja";
- przy edycji gracza, po kliknięciu "Sybmit" wyświetla się komunikat "Nie udało się zaktualizować gracza" bez podświetlenia nieprawidłowo wypełnionych pól;
- udało się dodać gracza z wagą "-590", ze wzrostem "000999999", poziomem rozgrywek "-90", pozycją alternatywną "-49", klubem "chbcdj%$$#";
- w raporcie dla gracza "qwe123!@#" wiek jaki się wyświetla to "-3";
- przy dodawaniu meczu aplikacja umożliwia dodanie nazwy drużyny zawodnika " %$#", drużyny przeciwnej - "#$%", z datą "16-11-2022", czas gry "-10", kolor koszulki "100"; tutaj również nie działa przycisk "clear". Kliknięcie w przycisk powoduje, że nadal widoczna jest nazwa drużyny zawodnika, przeciwnika. Nadal pozostają również wypełnione pola "data", "kolor koszulki", "czas gry". Do tego przy ustawionym języku polskim wyświetla się "clear" i "submit" zamiast "wyczyść" i "zapisz";
- przy kliknięciu w przycisk "rozpocznij mecz" wyświetla się boisko i ikonki pozwalające rozpocząć mecz, zatrzymać mecz, zmienić połowę, cofnąć? ( klikając przycisk nic się nie zmienia), wysłać raport. Jest również koszyczek, po naciśnięciu którego nic się nie dzieje. Jest błąd w funkcji połowa. Powinny być 2 i ewentualnie dogrywka. Jest akceptowana nawet liczba "12000000000000" i "-2000";
- brak opisu górnych ikonek, przed kliknięciem nie do końca wiadomo co będzie się działo po kliknięciu;
- przy edycji raportu w lewym górnym roku wyświetla się "save" zamiast "zapisz" przy ustawionym języku polskim;

- Dane meczu:
"%$# vs #$%
0 : 0
2022-11-16
Czas gry: -10 min
Link do meczu:
Kolor koszulki: 100"
- raport jest bardzo nieczytelny;
- WSTĘP : "(dotyczy meczu i drużyn)Jakim systemem grała jego drużyna a jakim przeciwnicy? Co z tego wynikało? Ile minut grał zawodnik na jakich pozycjach?" niezrozumiały opis;
- I. INTELIGENCJA BOISKOWA
"Ustawienie na boisku//szukanie wolnej przestrzeni/ruch bez piłkiOcena podejmowanych decyzji (ryzykowne/bezpieczne?), co jest najczęstszym wyborem z piłką/bez piłki? Jakie wybory w kontekście podań, dryblingów, strzałów/inne? Czy podejmowane wybory są skuteczne? Jak porusza się po boisku? Gdzie szuka miejsca do gry? Czy jest aktywny bez piłki?" tutaj również nieprecyzyjny opis. Dodatkowo jest podwójny ukośnik po słowie "boisku". Brak odstępu pomiędzy "piłkiOcena";
- II. MENTALNOŚĆ - tutaj również nieprecyzyjny opis + brak kropki na końcu zdania;
- pod opisem jest pole do dodania komentarza "Enter some text" przy wybranym języku polskim;
- III. PODSUMOWANIE - brak znaku zapytania na końcu;
- pod opisem jest pole do dodania komentarza "Enter some text" przy wybranym języku polskim;
- brak zakładek "Mecze", "Raporty" w głownym panelu. Są widoczne dopiero po wejściu w edycję gracza;
- przy dodawaniu meczu (przy ustawionym języku polskim) są pola po angielsku: "Web match", "General";
- przy dodawaniu meczu jest wypełnione automatycznie pole z dzisiejszą datą. Nie edytowałam pola i przy wciśnięciu "Submit" wyświetla się komunikat aby wypełnić to pole - mimo, że jest wypełnione;
- w utworzonym raporcie, klikając w link meczu wyświetla się strona z błędem "404 - Page Not Found";
- przy dodawaniu komentarza do podpunktów, wybierając którąś z dostępnych funkcji np. pogrubienie, podkreślenie - zmienia kolejność liter np. chcąc napisać "mecz" powstaje słowo "zcem";
- będąc w zakładce "Raporty" po kliknięciu "+Dodaj Raport" przenosi do zakładki mecze;
- po pobraniu raportu w kolumnie "Mecze" i "Raporty" wyświetlają się "[object Object],[object Object],[object Object],[object Object]";
- dodać gracza można tylko ze strony głównej, korzystając z linku pomocnicznego "dodaj gracza", powinna być również taka możliwość z zakładki "Gracze".

### Subtask 5

Utworzyłam profil i dołączyłam do grupy w Jirze :) 


## TASK 2

[link] (https://drive.google.com/drive/folders/1d70nAwkZflf0LE3LhkISrp0RaWcEtXjZ?usp=share_link](https://drive.google.com/drive/folders/1-Ip2iEYpc06U6Bcf_xJW7KcLGV5YCdaN?usp=sharing)](https://drive.google.com/drive/folders/1-Ip2iEYpc06U6Bcf_xJW7KcLGV5YCdaN?usp=share_link)) .

[link](https://tinyurl.com/3mzjdbnz)



### Subtask 1 

[https://docs.google.com/spreadsheets/d/1L8VHX_Oax4xpdypKAVVo96CeOWiHQl01/edit?usp=share_link&ouid=117512314362310181270&rtpof=true&sd=true]

#### Subtask 2 

[link] (https://docs.google.com/spreadsheets/d/12WZgnENQNRZsqzPfuduiCYGvoIX2zDEb/edit?usp=share_link&ouid=117512314362310181270&rtpof=true&sd=true).

##### Subtask 3

##### Po co piszemy test case’y?

Przypadki testowe piszemy, aby udokumentować różne funkcje/ funkcjonalności w ramach danej aplikacji. Czym więcej dobrych przypadków testowych- tym lepiej. Dzięki temu nie pominiemy ważnych funkcjonalności podczas testowania. Po przejściu przez wszystkie przypadki testowe, możemy stworzyć z nich raporty z wykonanych testów. Pisanie przypadków testowych pomaga również uporządkować pracę. W przypadku rozbudowanej aplikacji jest wiele funkcjonalności do zweryfikowania i bez przypadków testowych możemy się pogubić, powtarzać niepotrzebnie wcześniej wykonane kroki. Test case'y są również bardzo pomocne dla osób bez doświadczenia, dla osób które nie znają aplikacji, ponieważ pozwalają na zapoznanie się z daną aplikacją. Przypadki testowe można również wykorzystać w kontekście testów akceptacyjnych w celu potwierdzenia działania aplikacji zgodnie z oczekiwaniami. Są również pomocne w przypadku konieczności wykonywania retestów i testów regresyjnych. Będąc przy testach akceptacyjnych, przypadki testowe przydają się do wprowadzenia automatyzacji testów. 

###### Subtask 4

https://docs.google.com/spreadsheets/d/1ZSJ13Idu7_jbhJk_n_AZDxfU_wxJWnXv/edit?usp=share_link&ouid=117512314362310181270&rtpof=true&sd=true

## TASK 3 

### Subtask 1

https://docs.google.com/document/d/10y-tki3Yc_We8FDzdB9Ga5c7VnFvSILq/edit?usp=sharing&ouid=117512314362310181270&rtpof=true&sd=true


#### Subtask 2 

https://docs.google.com/spreadsheets/d/1e_K7J8zxTyjAj58gIWcIpoUD4rI094B6/edit?usp=share_link&ouid=117512314362310181270&rtpof=true&sd=true

https://docs.google.com/spreadsheets/d/1P4pjpBDTZQsC0o24DI03N1t_eKpEcGlI/edit?usp=share_link&ouid=117512314362310181270&rtpof=true&sd=true


#### Subtask 3 

https://drive.google.com/file/d/1V2HByGCGo3UNeTr8_cCu6Pcbj3NLjxAm/view?usp=share_link


#### Subtask 4 

https://docs.google.com/document/d/1MaXYm1s3Fepox4qKDagmdWiVLOQeYKML/edit?usp=sharing&ouid=117512314362310181270&rtpof=true&sd=true


8. Testy eksploracyjne tour: Uważam, że jest to bardzo przydatna metoda. Pozwala poznać aplikację nie trzymając się tylko stworzonych przypadków testowych. Dzięki stosowaniu metod tour możemy znaleźć o wiele więcej błędów, które moglibyśmy przeoczyć trzymając się test case'ów. Dlatego poza realizacją przypadków testowych, warto poświęcić godzinę i poklikać po aplikacji, stosując różne rodzaje "rajdów" :) Jest większe prawdopodobieństwo, że unikniemy oddania aplikacji na produkcję, która będzie posiadać rażące błędy. Mamy pewność, że aplikacja jest dobrej jakości. Finalnie przenosi się to na zadowolenie użytkownia. 
