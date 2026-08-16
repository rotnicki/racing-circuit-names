# Eksperyment: nazwy charakterystycznych elementów toru

## Status

**Status dokumentu:** eksperymentalny / roboczy  
**Data rozpoczęcia:** 16 sierpnia 2026  
**Pierwszy pilot:** Silverstone  
**Planowany drugi pilot:** tor o wyraźnie uboższym lub innym systemie nazw niż Silverstone  

Ten dokument **nie jest jeszcze obowiązującą metodologią projektu**. Służy do przetestowania nowej ścieżki badawczej, która pojawiła się w trakcie rozwijania repozytorium.

Dopóki pilotaż nie zostanie oceniony, nie należy na jego podstawie automatycznie zmieniać `docs/methodology.md`, `docs/source-policy.md`, `docs/internet-research-playbook.md`, `docs/circuit-entry-template.md`, `AGENTS.md` ani głównego skilla projektu.

## Skąd powstał pomysł

Podczas opracowania Silverstone pojawiła się informacja, że zakręt `Village` został nazwany od pobliskiej wsi Silverstone, która dała również nazwę całemu torowi. Zwróciło to uwagę na szersze zjawisko: wiele torów ma własne, historyczne lub kulturowo utrwalone nazwy zakrętów, prostych, szykan, sekcji i innych fragmentów obiektu.

Ponieważ repozytorium bada **pochodzenie i znaczenie nazw związanych z torami**, nazewnictwo takich elementów może być naturalnym drugim poziomem projektu.

## Hipoteza

Warto badać **nazwy charakterystycznych elementów toru**, jeżeli ich nazwy:

- są utrwalone w oficjalnym lub powszechnym użyciu;
- mają możliwe do zbadania pochodzenie;
- odnoszą się do geografii, historii, osoby, innego obiektu, wydarzenia lub funkcji;
- są kulturowo lub historycznie rozpoznawalne;
- pomagają lepiej zrozumieć sam tor i jego otoczenie.

Nie chodzi o techniczny katalog wszystkich numerów zakrętów.

## Robocza nazwa sekcji

Na czas pilotażu stosujemy:

```text
Nazwy charakterystycznych elementów toru
```

Nazwa jest celowo szersza od „nazw zakrętów”. Może obejmować m.in.:

- zakręty;
- szykany;
- proste;
- nawroty;
- całe sekwencje lub sekcje;
- inne utrwalone nazwane fragmenty toru.

## Tymczasowe kryterium wyboru elementów

Podczas pilotażu nie obowiązuje sztywny limit liczby pozycji.

Element kwalifikuje się do opracowania, jeżeli jego nazwa jest rzeczywiście używana i wnosi treść nazewniczą. Nie ma obowiązku uwzględniania elementów oznaczonych wyłącznie numerem.

Jeżeli tor ma wiele nazwanych elementów i dla większości istnieją wiarygodne informacje, można opracować możliwie pełny zestaw. Określenie „charakterystyczne” nie oznacza z góry wyboru np. pięciu najpopularniejszych nazw.

## Tymczasowa procedura researchu

Dla pilota należy oddzielić następujące pytania:

1. Jaki jest współczesny układ toru i kolejność przejazdu?
2. Które elementy mają utrwalone nazwy?
3. Czy nazwa jest oficjalna, tradycyjna, potoczna, komentatorska czy sponsorska?
4. Od kiedy można ją udokumentować?
5. Co oznacza nazwa językowo?
6. Od czego konkretnie pochodzi?
7. Czy element lub nazwa zmieniały się wraz z przebudową toru?
8. Czy ta sama nazwa była wcześniej przypisana do innego fragmentu?
9. Czy źródła podają konkurencyjne wersje pochodzenia?
10. Czy nazwę można potwierdzić w źródle oficjalnym, pierwotnym, historycznym lub specjalistycznym?

Nie należy automatycznie przyjmować, że nazwa obecna na mapie ma udokumentowaną etymologię.

## Tymczasowa hierarchia źródeł

Na czas eksperymentu stosujemy ogólną politykę źródeł projektu, ale dodatkowo zwracamy uwagę na:

1. oficjalne mapy i materiały operatora toru;
2. oficjalne materiały serii wyścigowych opisujące nazewnictwo;
3. materiały historyczne operatora, klubu lub właściciela;
4. źródła dotyczące konkretnego patrona, miejsca lub obiektu, od którego pochodzi nazwa;
5. wiarygodne źródła wtórne jako uzupełnienie.

Jeżeli jedno oficjalne opracowanie podaje historię wielu nazw, może być punktem wyjścia, ale pilotaż powinien sprawdzić przynajmniej część najbardziej istotnych lub problematycznych nazw w dodatkowych źródłach.

## Tymczasowa forma publikacji

Preferowana jest kolejność przejazdu współczesnego okrążenia.

Nie używamy tabeli jako formy domyślnej. Każdy istotny element może otrzymać krótki nagłówek i zwięzłe objaśnienie, np.:

```markdown
### Village

**Rodzaj:** zakręt.  
**Pochodzenie nazwy:** pobliska wieś Silverstone.  
**Objaśnienie:** ...
```

Forma może zostać uproszczona po pilotażu, jeżeli powtarzanie pól okaże się zbyt ciężkie.

## Pytania, które ma rozstrzygnąć pilotaż

Pilotaż ma odpowiedzieć m.in. na pytania:

- Czy słowo „charakterystyczne” daje właściwy filtr?
- Czy kolejność przejazdu jest zawsze najlepsza?
- Czy należy podawać numery zakrętów obok nazw?
- Czy proste i całe sekcje powinny być traktowane tak samo jak zakręty?
- Jak postępować z nazwami historycznymi nieobecnymi w obecnym układzie?
- Jak postępować z nazwami potocznymi lub komentatorskimi?
- Jak postępować z nazwami, których pochodzenia nie da się wiarygodnie ustalić?
- Czy jedna wspólna sekcja źródeł wystarcza, czy przy bardziej złożonych nazwach potrzebne są źródła przy konkretnych pozycjach?
- Jak głęboki research jest proporcjonalny do wartości informacyjnej pojedynczej nazwy?
- Czy pełna lista nazwanych elementów jest lepsza niż selekcja?
- Jak zapisywać warianty pisowni występujące nawet w oficjalnych materiałach?

## Pilot 1: Silverstone

### Dlaczego Silverstone

Silverstone jest dobrym pierwszym przypadkiem, ponieważ współczesne okrążenie ma bogaty i utrwalony system nazw. Nazwy odnoszą się do wielu różnych źródeł: lokalnej geografii, dawnych obiektów sakralnych, innych historycznych torów, lotniczej przeszłości Silverstone, instytucji motoryzacyjnych, kształtu zakrętu oraz konkretnej osoby.

### Wstępny zestaw elementów

W kolejności współczesnego okrążenia Grand Prix zidentyfikowano do zbadania:

- Hamilton Straight;
- Abbey;
- Farm;
- Village;
- The Loop;
- Aintree;
- Wellington Straight;
- Brooklands;
- Luffield;
- Woodcote;
- National Pits Straight;
- Copse;
- Maggotts;
- Becketts;
- Chapel;
- Hangar Straight;
- Stowe;
- Vale;
- Club.

### Pierwsze obserwacje metodologiczne

1. **Nie tylko zakręty są istotne.** Hamilton Straight, Wellington Straight i Hangar Straight mają równie wyraźne historie nazw jak wiele zakrętów.
2. **Nazwy mogą zmieniać się bez przebudowy geometrii.** International Pits Straight została w 2020 roku przemianowana na Hamilton Straight dla uczczenia Lewisa Hamiltona.
3. **Nazwy mogą pochodzić od innych obiektów motorsportowych.** Aintree i Brooklands odwołują się do innych historycznych miejsc wyścigowych.
4. **Jedna sekwencja może zawierać kilka nazw o wspólnym kontekście.** Maggotts, Becketts i Chapel tworzą jedną słynną sekwencję, ale ich nazwy mają różne bezpośrednie źródła.
5. **Pochodzenie może być niepewne.** Dla `Vale` oficjalne materiały Formuły 1 podają więcej niż jedno możliwe wyjaśnienie; nie należy wybierać jednej wersji bez zastrzeżenia.
6. **Nazwa może być czysto opisowa.** `The Loop` odnosi się do kształtu zakrętu.
7. **Oficjalne materiały mogą mieć warianty pisowni.** W materiałach Silverstone można spotkać zarówno `Maggotts`, jak i `Maggots`; ten problem należy uwzględnić przy ustalaniu przyszłej zasady zapisu.
8. **Nie każda współczesna nazwa ma łatwo dostępny „akt nadania”.** `National Pits Straight` jest współcześnie używana przez operatora i ma oczywisty związek z dawną linią start/meta oraz układem National, ale pilotaż powinien odróżniać opis funkcjonalny od udokumentowanego momentu nadania nazwy.

### Źródła pilota Silverstone

- [Formula 1 – Explained: How every Silverstone corner got its name, 2026](https://www.formula1.com/en/latest/article/explained-how-every-silverstone-corner-got-its-name.idMlxFC2gfN2ApcPmifxN.idMlxFC2gfN2ApcPmifxN) – aktualne oficjalne opracowanie Formuły 1 dotyczące nazw zakrętów.
- [Formula 1 – What’s in a name? The history behind Silverstone’s iconic corners, 2015](https://www.formula1.com/en/latest/article/whats-in-a-name-the-history-behind-silverstones-iconic-corners.4Q3miKVCXBkz5rKtyYnL5z) – szczegółowe objaśnienia pochodzenia nazw zakrętów i prostych.
- [Silverstone – Silverstone Renames International Pits Straight In Recognition Of Lewis Hamilton’s Outstanding Achievements](https://www.silverstone.co.uk/news/silverstone-renames-international-pits-straight) – źródło pierwotne dla zmiany nazwy na Hamilton Straight w 2020 roku.
- [Silverstone – Formula 1 Hospitality](https://www.silverstone.co.uk/events/formula-1-british-grand-prix/hospitality) – współczesne użycie nazwy National Pits Straight i jej związek z pierwotną linią start/meta.
- [Silverstone – A lap through the ages](https://www.silverstone.co.uk/news/lap-through-ages-silverstone-celebrates-75-years-memorable-moments) – współczesne użycie nazw m.in. Hangar Straight i Hamilton Straight oraz historyczny kontekst elementów toru.

## Następny etap

Po zakończeniu publikacyjnej części pilota Silverstone należy wykonać **drugi test na torze kontrastowym**, gdzie system nazw jest uboższy, mniej formalny albo inaczej udokumentowany.

Dopiero po porównaniu co najmniej dwóch przypadków należy zdecydować:

- czy sekcja staje się standardowym elementem projektu;
- czy ma być obowiązkowo badana, ale opcjonalnie publikowana;
- jakie kryteria wyboru nazw są ostateczne;
- jak wygląda finalna struktura wpisu;
- jakie zmiany należy wprowadzić do metodologii, polityki źródeł, playbooka, szablonu, `AGENTS.md` i skilla.

## Kryterium formalizacji

Eksperyment można przenieść do głównej metodologii dopiero wtedy, gdy na podstawie pilotażu potrafimy odpowiedzieć przynajmniej na trzy pytania:

1. **co dokładnie badamy;**
2. **jak wiarygodnie to badamy;**
3. **jak prezentujemy wynik bez zamieniania repozytorium w techniczny katalog zakrętów.**

Do tego czasu ten dokument pozostaje świadomie roboczy.
