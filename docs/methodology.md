# Metodologia opracowania nazw torów wyścigowych

Ten dokument opisuje wspólną metodę przygotowywania wpisów w repozytorium `racing-circuit-names`. Jest źródłem prawdy dla ludzi i agentów AI pracujących nad projektem.

## Cel projektu

Każdy wpis ma wyjaśniać nie tylko, jak nazywa się tor, ale przede wszystkim:

- co oznacza jego nazwa;
- z jakiego języka pochodzi;
- czy nazwa odnosi się do miejsca, osoby, sponsora, obiektu geograficznego albo wydarzenia historycznego;
- jaka jest rzeczywista etymologia nazwy;
- jak najlepiej objaśnić jej sens po polsku;
- jak zmieniała się nazwa toru w czasie;
- jakie są aktualne nazwy oficjalne i sponsorskie.

## Podstawowe rozróżnienia

Przy każdym torze należy rozdzielać co najmniej cztery warstwy:

1. **nazwa własna** – forma używana jako nazwa obiektu;
2. **nazwa geograficzna lub historyczna** – jeśli tor przejął nazwę miejsca;
3. **nazwa sponsorska lub marketingowa** – jeśli stanowi część współczesnej nazwy;
4. **znaczenie i polskie objaśnienie** – tłumaczenie dosłowne oraz naturalne wyjaśnienie sensu.

Nie należy sztucznie tłumaczyć utrwalonych nazw własnych w zwykłym użyciu. Polskie tłumaczenie służy wyjaśnieniu etymologii.

## Minimalny zakres badań

Przed utworzeniem wpisu należy ustalić:

1. współczesną oficjalną nazwę toru;
2. powszechnie używaną nazwę, jeśli różni się od oficjalnej;
3. lokalizację;
4. język lub języki istotne dla nazwy;
5. dosłowne znaczenie nazwy, jeśli można je wiarygodnie ustalić;
6. rzeczywiste pochodzenie nazwy;
7. związek nazwy z miejscem, osobą lub sponsorem;
8. ważniejsze nazwy historyczne;
9. istotne zmiany nazwy;
10. wiarygodne źródła potwierdzające powyższe ustalenia.

## Zasada ostrożności etymologicznej

Etymologia musi wynikać ze źródeł, a nie z podobieństwa brzmienia.

Nie wolno:

- zgadywać pochodzenia nazwy na podstawie współczesnych słów;
- przedstawiać etymologii ludowej jako faktu;
- dopowiadać konkretnego imienia, osoby lub wydarzenia, jeśli źródło tego nie potwierdza;
- mieszać informacji o różnych miejscach o tej samej lub podobnej nazwie.

Jeżeli źródła są niejednoznaczne, wpis ma to jasno powiedzieć.

## Nazwy sponsorskie i informacje zmienne w czasie

Nazwy sponsorów i oficjalne nazwy marketingowe mogą się zmieniać. Dlatego:

- należy weryfikować je w źródłach aktualnych na dzień opracowania;
- w razie potrzeby podawać datę weryfikacji;
- nie należy traktować dawnej nazwy sponsorskiej jako ponadczasowej nazwy obiektu;
- przy późniejszej aktualizacji wpisu należy ponownie sprawdzić aktualny stan.

## Język polskiego opracowania

Treść podstawowa jest przygotowywana po polsku.

Należy:

- zachowywać oryginalną pisownię nazw własnych i znaki diakrytyczne;
- odróżniać tłumaczenie dosłowne od naturalnego polskiego objaśnienia;
- unikać tworzenia sztucznych polskich nazw własnych;
- pisać zwięźle, ale wystarczająco dokładnie, aby czytelnik rozumiał źródło nazwy.

## Autorstwo, redakcja i wykorzystanie AI

Koncepcja projektu, jego zakres, metodologia, decyzje redakcyjne i nadzór merytoryczny są przypisane **Mikołajowi Rotnickiemu**.

Narzędzia AI mogą być wykorzystywane do:

- wyszukiwania i porównywania źródeł;
- przygotowywania zestawień i syntez;
- redagowania wersji roboczych;
- kontroli spójności wpisów;
- pomocy technicznej przy utrzymaniu repozytorium.

Udział AI powinien być ujawniony w stopce konkretnego opracowania. Dla wpisów przygotowanych przy pomocy ChatGPT stosujemy:

```text
Redakcja: Mikołaj Rotnicki.
Wsparcie badawcze i redakcyjne: ChatGPT (OpenAI).
```

Jeżeli konkretne opracowanie powstanie przy istotnym wsparciu innego systemu AI albo innej osoby, stopkę należy dostosować do rzeczywistego przebiegu pracy. Nie należy automatycznie przypisywać udziału ChatGPT do materiału, przy którym nie był używany.

Podpis redakcyjny dotyczy opracowania tekstowego i procesu redakcyjnego. Nie obejmuje autorstwa materiałów zewnętrznych, takich jak schematy torów, fotografie lub inne pliki. Ich autorstwo i licencje dokumentuje się osobno.

## Struktura wpisu

Bazowy układ znajduje się w `docs/circuit-entry-template.md`.

W zależności od toru można dodawać lub pomijać sekcje, ale wpis powinien zachować logiczny porządek:

- podstawowe informacje;
- schemat toru;
- znaczenie nazwy;
- pochodzenie nazwy;
- związek nazwy z torem;
- historia nazw;
- polskie objaśnienie;
- źródła;
- stopka redakcyjna.

## Grafika toru

Jeżeli dostępny jest odpowiedni schemat SVG na licencji pozwalającej na ponowne wykorzystanie, należy dodać go do `assets/circuits/` i osadzić bezpośrednio w pliku Markdown toru.

Szczegółowe zasady wyboru, licencjonowania i dostępności SVG opisuje `docs/svg-accessibility-and-licensing.md`.

## Końcowa kontrola jakości

Przed zakończeniem opracowania należy sprawdzić:

- czy wpis odróżnia nazwę własną od tłumaczenia;
- czy aktualna nazwa została zweryfikowana;
- czy etymologia ma źródło;
- czy nie pomieszano źródeł dotyczących różnych miejsc;
- czy wszystkie ważne twierdzenia mają podstawę źródłową;
- czy linki prowadzą do właściwych dokumentów;
- czy SVG ma prawidłową licencję i informacje o autorze;
- czy grafika ma tekst alternatywny oraz metadane dostępnościowe;
- czy stopka wskazuje redakcję i rzeczywiste wsparcie AI;
- czy README zawiera nowy tor;
- czy data ostatniej aktualizacji wpisu jest poprawna.

## Zasada nadrzędna

Jeżeli szybkość opracowania koliduje z wiarygodnością, pierwszeństwo ma wiarygodność. Lepiej pozostawić dobrze opisany punkt niepewny niż uzupełnić go zgadywaną informacją.
