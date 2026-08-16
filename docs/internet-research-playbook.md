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
tor → Wikimedia Commons SVG
```

Nie każda ścieżka będzie potrzebna dla każdego toru.

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

Po znalezieniu oficjalnej domeny należy przeszukiwać ją bezpośrednio. Jeżeli wyszukiwarka obsługuje operator `site:`, używaj na przykład:

```text
site:example-circuit.com history
site:example-circuit.com name
site:example-circuit.com sponsor
site:example-circuit.com press release
```

Nie zakładaj, że strona główna zawiera najlepsze informacje. Szukaj podstron typu `History`, `About`, `Track`, `Press`, `News`, `Media`, `Timeline`, `Contact` i ich lokalnych odpowiedników.

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

W historii obiektu skupiaj się na faktach potrzebnych do wyjaśnienia nazwy. Nie rozbudowuj wpisu o całą historię sportową, jeśli nie ma związku z nazewnictwem.

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

W praktyce należy używać odpowiedników tych pojęć w języku danego kraju, na przykład:

- niemiecki: `Namensherkunft`, `Ortsname`, `Geschichte`, `Bedeutung`;
- włoski: `origine del nome`, `etimologia`, `storia`;
- portugalski: `origem do nome`, `etimologia`, `história`;
- hiszpański: `origen del nombre`, `etimología`, `historia`;
- francuski: `origine du nom`, `étymologie`, `histoire`.

Dla innych języków należy utworzyć analogiczne lokalne zapytania.

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

Przykładowe zapytania:

```text
"Nazwa miejsca" etymology
"Nazwa miejsca" name origin
"Nazwa miejsca" historical name
"Nazwa miejsca" local history
```

Następnie wykonaj odpowiedniki w języku lokalnym.

## Etap 8. Jeżeli tor nosi imię osoby, zbadaj patrona osobno

Ustal:

- pełne imię i nazwisko;
- kim była osoba;
- jaki miała związek z torem lub regionem;
- kiedy nadano obiektowi jej imię;
- dlaczego dokonano zmiany nazwy.

Preferuj oficjalną historię toru, źródła biograficzne, archiwa, federacje sportowe i oficjalne materiały serii.

Nie zakładaj, że osoba jest patronem tylko dlatego, że jej nazwisko występuje w nazwie obiektu — sprawdź akt lub historię nadania nazwy.

## Etap 9. Jeżeli występuje sponsor, traktuj go jako informację zmienną

Szukaj:

```text
"Nazwa toru" sponsor
"Nazwa toru" naming rights
"Nazwa toru" partnership
"Nazwa toru" renamed sponsor
```

oraz odpowiedników w języku lokalnym.

Preferuj:

- oficjalny komunikat toru;
- oficjalny komunikat sponsora;
- aktualną stronę obiektu;
- oficjalny komunikat organizatora zawodów.

Zapisuj datę weryfikacji, jeżeli człon sponsorski jest częścią współczesnej nazwy.

## Etap 10. Szukaj dawnych nazw oddzielnie

Nie ograniczaj się do sekcji `History` na stronie toru.

Szukaj kombinacji:

```text
"Nazwa toru" former name
"Nazwa toru" old name
"Nazwa toru" renamed
"Dawna nazwa" "obecna nazwa"
```

oraz odpowiedników lokalnych.

Jeżeli znajdziesz dawną nazwę w źródle wtórnym, spróbuj znaleźć niezależne potwierdzenie w źródle pierwotnym, archiwalnym lub oficjalnym.

## Etap 11. Używaj wyników wtórnych jako mapy, nie jako końca badania

Wikipedia, encyklopedie internetowe, portale motorsportowe i wyniki wyszukiwarki mogą ujawnić:

- inną pisownię nazwy;
- datę zmiany nazwy;
- nazwisko patrona;
- nazwę dawnego obiektu;
- nazwę dokumentu lub instytucji;
- potencjalne źródło pierwotne.

Jeżeli pojawia się istotne twierdzenie:

1. sprawdź przypis lub wskazane źródło;
2. otwórz źródło pierwotne, jeśli jest dostępne;
3. wyszukaj tę samą informację bezpośrednio w domenie instytucji;
4. dopiero wtedy użyj jej jako podstawy wpisu.

## Etap 12. Korzystaj z operatorów wyszukiwania, gdy są dostępne

Pomocne operatory:

```text
"dokładna fraza"
site:domena.example fraza
filetype:pdf fraza
"nazwa" historia PDF
"nazwa" archive
```

Przydatne zastosowania:

- `site:` – przeszukanie oficjalnej domeny;
- cudzysłów – historyczne warianty nazw i dokładne nazwy własne;
- `filetype:pdf` – raporty, broszury historyczne, dokumenty urzędowe i publikacje naukowe;
- połączenie nazwy z nazwą instytucji – zawężenie wyników do właściwego regionu.

Jeżeli używane narzędzie wyszukujące nie obsługuje operatora, należy osiągnąć ten sam cel przez osobne wyszukiwanie domenowe lub bezpośrednie przeglądanie serwisu.

## Etap 13. Traktuj PDF-y, archiwa i skany jako pełnoprawne źródła

Warto aktywnie szukać:

- oficjalnych broszur historycznych;
- dokumentów miejskich;
- archiwalnych map;
- publikacji naukowych;
- rejestrów zabytków;
- dokumentów nadań ziemskich;
- materiałów muzealnych;
- starych programów zawodów, jeśli dotyczą nazewnictwa.

Jeżeli dokument jest skanem lub PDF-em, agent powinien sprawdzić nie tylko wynik wyszukiwarki, ale treść właściwego dokumentu i stronę, na której znajduje się istotna informacja.

## Etap 14. Zweryfikuj, że źródło dotyczy właściwego miejsca

Przed przyjęciem źródła porównaj co najmniej:

- kraj;
- region;
- miejscowość;
- daty;
- nazwę obiektu;
- kontekst historyczny.

To szczególnie ważne przy powtarzalnych nazwach geograficznych.

Jeżeli źródło opisuje obiekt o tej samej nazwie w innym stanie, kraju lub regionie, należy je odrzucić, nawet jeśli treść brzmi wiarygodnie.

## Etap 15. Zbuduj macierz dowodową przed pisaniem

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
| SVG | strona konkretnego pliku Wikimedia Commons |

Nie trzeba publikować tej tabeli w każdym wpisie. Jest narzędziem kontroli researchu.

## Etap 16. Kryterium zakończenia wyszukiwań

Nie należy kończyć badania tylko dlatego, że znaleziono pierwszy sensowny artykuł.

Można przejść do pisania, gdy:

- dokładnie zidentyfikowano tor;
- aktualna nazwa jest zweryfikowana w aktualnym źródle;
- dla etymologii znaleziono źródło odpowiedniego rodzaju albo jasno ustalono, że pozostaje niepewna;
- historia nazwy jest oddzielona od historii sportowej;
- nazwa miejsca została zbadana osobno, jeśli jest potrzebna;
- ewentualny patron lub sponsor został zweryfikowany;
- kluczowe daty mają źródła;
- potencjalne konflikty między źródłami zostały sprawdzone;
- wiadomo, które twierdzenia są pewne, a które wymagają zastrzeżenia.

Dodatkowe wyniki nie muszą być dalej przeglądane, jeżeli kolejne źródła jedynie powtarzają te same informacje i nie wnoszą nowej jakości dowodowej.

## Etap 17. Osobna procedura dla SVG

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

## Przykładowy schemat researchu

Dla hipotetycznego toru `Example Ring` agent może wykonać serię wyszukiwań:

```text
"Example Ring" official
site:example-ring.de Geschichte
site:example-ring.de Name
"Example Ring" former name
"Example" Ortsname Herkunft
"Example" Namensherkunft
"Example Ring" sponsor
"Example Ring" Wikimedia Commons SVG
```

Następnie powinien otworzyć właściwe źródła i zweryfikować ich treść, zamiast budować wpis wyłącznie ze streszczeń wyników wyszukiwania.

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
- wymyślać brakujących faktów, gdy wyszukiwanie nie daje odpowiedzi.

## Relacja z pozostałą dokumentacją

Podczas pracy należy stosować łącznie:

- `docs/methodology.md` – co ma zawierać opracowanie;
- `docs/source-policy.md` – jak oceniać źródła;
- `docs/internet-research-playbook.md` – jak prowadzić wyszukiwanie;
- `docs/circuit-entry-template.md` – jak zbudować wpis;
- `docs/svg-accessibility-and-licensing.md` – jak pracować z grafiką.
