# Playbook wyszukiwania internetowego

Ten dokument opisuje operacyjną procedurę wyszukiwania informacji o torach wyścigowych w Internecie. Uzupełnia `docs/source-policy.md`: polityka źródeł mówi **jak oceniać źródła**, a ten playbook mówi **jak ich systematycznie szukać**.

Celem jest uzyskanie podobnej jakości badań niezależnie od tego, czy wykonuje je człowiek, ChatGPT, Codex, Claude, Gemini czy inny agent AI.

## Zasada podstawowa: nie zadawaj jednego szerokiego pytania

Nie należy próbować rozwiązać całego tematu jednym zapytaniem w rodzaju:

```text
Hockenheimring history name meaning
```

Badanie należy podzielić na osobne ścieżki, ponieważ różne fakty najlepiej potwierdzają różne rodzaje źródeł.

Podstawowe ścieżki badawcze:

```text
tor → aktualna oficjalna nazwa
tor → historia obiektu
nazwa toru → znaczenie językowe
miejscowość lub region → etymologia nazwy
patron → biografia i powód nadania imienia
sponsor → aktualna nazwa i relacja sponsorska
tor → historyczne nazwy
tor → aktualny i historyczny układ
tor → nazwy charakterystycznych elementów → pochodzenie nazw
tor → Wikimedia Commons SVG
```

Nie każda ścieżka doprowadzi do materiału publikacyjnego. W szczególności sprawdzenie nazw charakterystycznych elementów jest obowiązkowym etapem researchu, ale sekcja w gotowym wpisie powstaje tylko wtedy, gdy istnieje wartościowy i źródłowo potwierdzony materiał.

## Etap 1. Ustal dokładnie, czego szukasz

Przed wyszukiwaniem ustal:

- nazwę toru podaną przez użytkownika;
- kraj;
- miasto, region lub najbliższą miejscowość;
- możliwe warianty pisowni;
- nazwę w języku lokalnym;
- czy podana nazwa może być nazwą sponsorską, historyczną albo potoczną.

Jeżeli istnieją różne obiekty o podobnej nazwie, rozstrzygnij to przed gromadzeniem źródeł.

## Etap 2. Znajdź oficjalną domenę toru

Pierwszym celem wyszukiwania jest ustalenie oficjalnej strony toru lub operatora.

Przykładowe zapytania:

```text
"Nazwa toru" official
"Nazwa toru" official website
"Nazwa toru" circuit official
"Nazwa toru" racetrack official
```

W języku lokalnym warto używać odpowiedników słów takich jak:

- historia;
- o nas;
- tor;
- obiekt;
- aktualności;
- kontakt;
- nazwa;
- sponsor.

Po znalezieniu oficjalnej domeny należy przeszukiwać ją bezpośrednio. Szukaj podstron typu `History`, `About`, `Track`, `Circuit`, `Map`, `Press`, `News`, `Media`, `Timeline`, `Contact` i ich lokalnych odpowiedników.

## Etap 3. Zweryfikuj aktualną nazwę

Aktualna nazwa może być zmienna, dlatego wymaga źródła aktualnego na dzień opracowania.

Sprawdź co najmniej:

- nagłówek lub branding oficjalnej strony;
- stronę `About`, `Contact` lub informacje prawne;
- aktualne komunikaty prasowe;
- bieżące materiały organizatora najważniejszych zawodów, jeśli są potrzebne.

Osobno zanotuj:

- nazwę oficjalną;
- nazwę powszechną;
- nazwę sponsorską;
- nazwę historyczną.

Nie wyciągaj wniosku o aktualnej nazwie tylko z domeny, starego artykułu lub wyniku wyszukiwarki.

## Etap 4. Zbadaj historię toru

Szukaj przede wszystkim na stronie toru, w archiwach, materiałach władz lokalnych i źródłach serii wyścigowych.

Przykładowe zapytania:

```text
"Nazwa toru" history
"Nazwa toru" history official
"Nazwa toru" timeline
"Nazwa toru" opening
"Nazwa toru" founded
"Nazwa toru" renamed
```

Następnie wykonaj analogiczne zapytania w języku lokalnym.

W historii obiektu skupiaj się na faktach potrzebnych do wyjaśnienia nazewnictwa. Nie rozbudowuj wpisu o całą historię sportową, jeśli nie ma związku z nazwami.

## Etap 5. Badaj nazwę w języku lokalnym

Wyszukiwanie wyłącznie po angielsku jest niewystarczające.

Dla każdego toru ustal język lokalny i wykonaj część badań w tym języku. Jeżeli agent nie zna języka, może przygotować zapytania za pomocą tłumaczenia, ale powinien otwierać i oceniać źródła lokalne.

Przykładowe typy zapytań:

```text
"nazwa miejscowości" etymologia
"nazwa miejscowości" pochodzenie nazwy
"nazwa miejscowości" historia nazwy
"nazwa toru" historia nazwy
```

Dla innych języków należy użyć lokalnych odpowiedników pojęć takich jak pochodzenie nazwy, historia, znaczenie, nazwa miejscowa i etymologia.

## Etap 6. Oddziel znaczenie słowa od etymologii nazwy

Jeżeli nazwa zawiera zwykłe słowo, sprawdź jego współczesne znaczenie w autorytatywnym słowniku właściwego języka.

Osobno sprawdź historyczne pochodzenie nazwy własnej.

To są dwa różne pytania:

```text
Co dzisiaj znaczy dane słowo?
```

oraz:

```text
Dlaczego konkretny obiekt lub miejscowość nosi tę nazwę?
```

Nie wolno automatycznie wyprowadzać etymologii nazwy miejscowej ze współczesnego znaczenia podobnie brzmiącego słowa.

## Etap 7. Jeżeli tor przejął nazwę miejsca, zbadaj miejsce osobno

Dla nazw geograficznych utwórz oddzielną ścieżkę badań dotyczącą miasta, dzielnicy, jeziora, góry, regionu lub dawnej posiadłości.

Szukaj w:

- serwisach władz lokalnych;
- regionalnych leksykonach historycznych;
- archiwach państwowych i miejskich;
- bibliotekach cyfrowych;
- muzeach;
- publikacjach naukowych;
- słownikach nazw miejscowych i opracowaniach onomastycznych.

## Etap 8. Jeżeli tor nosi imię osoby, zbadaj patrona osobno

Ustal:

- pełne imię i nazwisko;
- kim była osoba;
- jaki miała związek z torem lub regionem;
- kiedy nadano obiektowi jej imię;
- dlaczego dokonano zmiany nazwy.

Preferuj oficjalną historię toru, źródła biograficzne, archiwa, federacje sportowe i oficjalne materiały serii.

## Etap 9. Jeżeli występuje sponsor, traktuj go jako informację zmienną

Szukaj:

```text
"Nazwa toru" sponsor
"Nazwa toru" naming rights
"Nazwa toru" partnership
"Nazwa toru" renamed sponsor
```

Preferuj oficjalny komunikat toru, sponsora lub organizatora zawodów. Zapisuj datę weryfikacji, jeżeli człon sponsorski jest częścią współczesnej nazwy.

## Etap 10. Szukaj dawnych nazw oddzielnie

Nie ograniczaj się do sekcji `History` na stronie toru.

Szukaj kombinacji:

```text
"Nazwa toru" former name
"Nazwa toru" old name
"Nazwa toru" renamed
"Dawna nazwa" "obecna nazwa"
```

Jeżeli znajdziesz dawną nazwę w źródle wtórnym, spróbuj znaleźć niezależne potwierdzenie w źródle pierwotnym, archiwalnym lub oficjalnym.

## Etap 11. Sprawdź nazwy charakterystycznych elementów toru

Dla każdego toru wykonaj osobną ścieżkę:

```text
tor → nazwy charakterystycznych elementów → pochodzenie nazw
```

### 11.1. Najpierw ustal współczesny układ

Znajdź oficjalną mapę lub opis aktualnej konfiguracji. Ustal, czy zakręty, proste, szykany, nawroty, sekwencje lub inne fragmenty mają utrwalone nazwy.

Nie zakładaj, że każdy numer zakrętu ma nazwę własną.

### 11.2. Zbadaj status każdej istotnej nazwy

Dla każdej potencjalnej pozycji sprawdź:

- czy nazwa jest rzeczywiście używana;
- czy jest oficjalna, tradycyjna, potoczna, komentatorska, sponsorska lub historyczna;
- czy ma warianty pisowni;
- czy zmieniała się w czasie;
- czy zmiana nazwy nastąpiła bez zmiany geometrii.

### 11.3. Zbadaj pochodzenie osobno

Nie traktuj potwierdzenia użycia nazwy jako dowodu jej etymologii.

Szukaj m.in.:

```text
"Nazwa elementu" "Nazwa toru" history
"Nazwa elementu" "Nazwa toru" name origin
"Nazwa elementu" corner name
"Nazwa elementu" straight name
site:oficjalna-domena "Nazwa elementu"
```

Jeżeli nazwa pochodzi od:

- **miejsca** – zbadaj to miejsce;
- **osoby** – sprawdź osobę i powód upamiętnienia;
- **organizacji** – sprawdź relację organizacji z torem;
- **innego toru lub obiektu** – potwierdź ten związek;
- **kształtu lub funkcji** – znajdź źródło, które tak to objaśnia;
- **sponsora** – traktuj informację jako zmienną w czasie.

### 11.4. Kryterium publikacji

Sekcja `Nazwy charakterystycznych elementów toru` powstaje tylko wtedy, gdy research ujawni utrwalone nazwy wnoszące istotny kontekst.

Nie publikuj:

- listy zakrętów oznaczonych wyłącznie numerami;
- nazw wymyślonych na podstawie geometrii;
- pojedynczych przypadkowych określeń z forum lub komentarza;
- etymologii dopowiedzianej bez źródła.

Brak takiej sekcji jest prawidłowym wynikiem.

### 11.5. Domyślna kolejność

Dla współczesnego układu prezentuj elementy w kolejności przejazdu okrążenia. Numery zakrętów podawaj pomocniczo, jeżeli są jednoznacznie ustalone.

Dla materiału wyłącznie historycznego można zastosować porządek chronologiczny lub inny lepiej odpowiadający źródłom.

## Etap 12. Używaj wyników wtórnych jako mapy, nie jako końca badania

Wikipedia, encyklopedie internetowe, portale motorsportowe i wyniki wyszukiwarki mogą ujawnić inne warianty nazw, daty zmian, patronów, dokumenty albo potencjalne źródła pierwotne.

Jeżeli pojawia się istotne twierdzenie:

1. sprawdź przypis lub wskazane źródło;
2. otwórz źródło pierwotne, jeśli jest dostępne;
3. wyszukaj tę samą informację bezpośrednio w domenie instytucji;
4. dopiero wtedy użyj jej jako podstawy wpisu.

## Etap 13. Korzystaj z operatorów wyszukiwania, gdy są dostępne

Pomocne operatory:

```text
"dokładna fraza"
site:domena.example fraza
filetype:pdf fraza
"nazwa" historia PDF
"nazwa" archive
```

Jeżeli używane narzędzie wyszukujące nie obsługuje operatora, należy osiągnąć ten sam cel przez osobne wyszukiwanie domenowe lub bezpośrednie przeglądanie serwisu.

## Etap 14. Traktuj PDF-y, archiwa i skany jako pełnoprawne źródła

Warto aktywnie szukać:

- oficjalnych broszur historycznych;
- dokumentów miejskich;
- archiwalnych map;
- publikacji naukowych;
- rejestrów zabytków;
- materiałów muzealnych;
- dawnych map i programów zawodów, jeśli dotyczą nazewnictwa toru lub jego elementów.

Jeżeli dokument jest skanem lub PDF-em, sprawdź treść właściwego dokumentu i konkretną stronę, na której znajduje się istotna informacja.

## Etap 15. Zweryfikuj, że źródło dotyczy właściwego miejsca

Przed przyjęciem źródła porównaj co najmniej:

- kraj;
- region;
- miejscowość;
- daty;
- nazwę obiektu;
- kontekst historyczny.

To szczególnie ważne przy nazwach elementów pochodzących od innych torów, miejscowości lub budynków.

## Etap 16. Zbuduj macierz dowodową przed pisaniem

Przed utworzeniem finalnego wpisu agent powinien umieć przypisać źródło do każdego kluczowego twierdzenia.

Minimalna macierz:

| Twierdzenie | Preferowany rodzaj źródła |
|---|---|
| Aktualna oficjalna nazwa | oficjalna strona/operator |
| Lokalizacja | oficjalna strona lub władze lokalne |
| Znaczenie słów | autorytatywny słownik językowy |
| Etymologia nazwy miejsca | leksykon historyczny/onomastyczny/archiwum |
| Powód nazwania toru | oficjalna historia/archiwum |
| Patron | oficjalna historia + źródło biograficzne |
| Nazwa sponsorska | aktualny komunikat oficjalny |
| Dawna nazwa | oficjalne lub archiwalne źródło historyczne |
| Użycie nazwy elementu | oficjalna mapa/operator/seria |
| Pochodzenie nazwy elementu | oficjalne lub historyczne źródło odpowiednie dla konkretnego odniesienia |
| SVG | strona konkretnego pliku Wikimedia Commons |

## Etap 17. Kryterium zakończenia wyszukiwań

Można przejść do pisania, gdy:

- dokładnie zidentyfikowano tor;
- aktualna nazwa jest zweryfikowana;
- dla etymologii znaleziono źródło odpowiedniego rodzaju albo jasno ustalono, że pozostaje niepewna;
- historia nazwy jest oddzielona od historii sportowej;
- nazwa miejsca została zbadana osobno, jeśli jest potrzebna;
- ewentualny patron lub sponsor został zweryfikowany;
- sprawdzono, czy istnieją utrwalone nazwy charakterystycznych elementów;
- jeśli takie nazwy mają trafić do wpisu, oddzielono dowód użycia od dowodu pochodzenia;
- kluczowe daty mają źródła;
- potencjalne konflikty między źródłami zostały sprawdzone;
- wiadomo, które twierdzenia są pewne, a które wymagają zastrzeżenia.

Dodatkowe wyniki nie muszą być dalej przeglądane, jeżeli kolejne źródła jedynie powtarzają te same informacje i nie wnoszą nowej jakości dowodowej.

## Etap 18. Osobna procedura dla SVG

Po zakończeniu badań tekstowych wykonaj osobne wyszukiwanie grafiki.

Preferowana ścieżka:

1. wyszukaj nazwę toru w Wikimedia Commons;
2. znajdź pliki przedstawiające właściwy układ;
3. otwórz stronę konkretnego pliku;
4. sprawdź autora;
5. sprawdź pole źródła, np. `own work`;
6. sprawdź licencję;
7. sprawdź historię pliku i istotne późniejsze modyfikacje;
8. upewnij się, że przedstawiony wariant toru odpowiada wpisowi;
9. dopiero wtedy skopiuj SVG do repozytorium;
10. zastosuj `docs/svg-accessibility-and-licensing.md`.

Sama obecność pliku w Wikimedia Commons nie zwalnia z kontroli jego konkretnej strony i licencji.

## Czego agent nie powinien robić

Nie należy:

- opierać wpisu na jednym szerokim wyszukiwaniu;
- ograniczać badań do języka angielskiego;
- traktować fragmentu wyniku wyszukiwarki jako źródła, jeśli można otworzyć stronę;
- uznawać Wikipedii za końcowe źródło etymologii, gdy dostępne są źródła specjalistyczne;
- zakładać, że oficjalna strona toru jest autorytetem językowym dla etymologii nazwy miejscowości;
- kopiować atrakcyjnej etymologii bez sprawdzenia jej w źródle językowym lub historycznym;
- mylić aktualnej nazwy sponsorskiej z ponadczasową nazwą obiektu;
- mieszać źródeł dotyczących różnych miejsc o tej samej nazwie;
- tworzyć nazw elementów tam, gdzie istnieją tylko numery;
- traktować samego użycia nazwy zakrętu jako automatycznego dowodu jej pochodzenia;
- wymyślać brakujących faktów, gdy wyszukiwanie nie daje odpowiedzi.

## Relacja z pozostałą dokumentacją

Podczas pracy należy stosować łącznie:

- `docs/methodology.md` – co ma zawierać opracowanie;
- `docs/source-policy.md` – jak oceniać źródła;
- `docs/internet-research-playbook.md` – jak prowadzić wyszukiwanie;
- `docs/circuit-entry-template.md` – jak zbudować wpis;
- `docs/svg-accessibility-and-licensing.md` – jak pracować z grafiką.
