# Polityka źródeł

Ten dokument określa sposób wyszukiwania, oceny i cytowania źródeł w repozytorium `racing-circuit-names`.

Szczegółowa procedura prowadzenia wyszukiwań internetowych znajduje się w `docs/internet-research-playbook.md`. Ten dokument określa przede wszystkim **jak oceniać źródła**, natomiast playbook opisuje **jak ich systematycznie szukać**.

## Hierarchia źródeł

W pierwszej kolejności należy szukać źródeł możliwie bliskich opisywanemu faktowi.

Preferowana kolejność:

1. **oficjalna strona toru lub jego operatora** – aktualna nazwa, historia obiektu, parametry, oficjalne komunikaty;
2. **źródła władz publicznych, archiwów, muzeów, bibliotek i instytucji naukowych** – historia miejsca, dawne nazwy, dokumenty archiwalne;
3. **autorytatywne źródła językowe i onomastyczne** – słowniki, akademie języka, leksykony nazw miejscowych;
4. **oficjalne źródła serii wyścigowych i organizatorów zawodów** – historia sportowa, nazwy używane w danym okresie;
5. **wiarygodne źródła wtórne** – renomowane media, publikacje historyczne i motorsportowe;
6. **Wikipedia i podobne opracowania zbiorowe** – przede wszystkim jako narzędzie orientacyjne do znalezienia źródeł pierwotnych, nie jako jedyna podstawa kluczowych twierdzeń.

## Procedura wyszukiwania

Dla każdego toru należy osobno szukać informacji dotyczących:

- współczesnej oficjalnej nazwy;
- historii toru;
- historii nazwy miejscowości lub obszaru, jeżeli nazwa toru jest geograficzna;
- znaczenia słów tworzących nazwę;
- patrona, jeżeli tor nosi imię osoby;
- sponsora, jeżeli częścią nazwy jest człon sponsorski;
- dawnych nazw obiektu;
- odpowiedniego schematu SVG i jego licencji.

Nie należy zakładać, że jedno źródło wiarygodnie odpowie na wszystkie te pytania.

Praktyczną kolejność wyszukiwań, wzorce zapytań, wyszukiwanie wielojęzyczne, użycie operatorów `site:` i `filetype:`, sposób przechodzenia od źródeł wtórnych do pierwotnych oraz kryteria zakończenia researchu opisuje `docs/internet-research-playbook.md`.

## Informacje aktualne i historyczne

Informacje mogą należeć do dwóch różnych kategorii:

### Informacje zmienne

Przykłady:

- współczesna nazwa sponsorska;
- operator obiektu;
- nazwa handlowa;
- aktualny układ lub długość toru.

Takie informacje należy weryfikować w aktualnych źródłach i w razie potrzeby odnotować datę sprawdzenia.

### Informacje historyczne

Przykłady:

- rok powstania toru;
- dawna nazwa miejscowości;
- pochodzenie nazwy;
- patron toru.

Preferowane są tutaj źródła archiwalne, historyczne, urzędowe i naukowe.

## Weryfikacja etymologii

Etymologia wymaga szczególnej ostrożności.

Należy:

- preferować słowniki etymologiczne, leksykony historyczne, opracowania onomastyczne i źródła urzędowe;
- oddzielać znaczenie współczesnego wyrazu od historycznego pochodzenia nazwy;
- rozróżniać etymologię potwierdzoną od hipotezy;
- zaznaczać rozbieżności pomiędzy wiarygodnymi źródłami;
- odrzucać atrakcyjne, ale niepotwierdzone etymologie ludowe.

## Konflikty pomiędzy źródłami

Jeżeli wiarygodne źródła podają różne wersje:

1. należy sprawdzić datę i charakter każdego źródła;
2. ustalić, czy źródła nie opisują różnych okresów lub wariantów obiektu;
3. preferować źródło pierwotne lub bardziej specjalistyczne;
4. jeśli konflikt pozostaje nierozstrzygnięty, opisać go wprost zamiast wybierać jedną wersję bez uzasadnienia.

## Ryzyko pomieszania miejsc

Przed wykorzystaniem źródła należy sprawdzić, czy dotyczy dokładnie tego samego toru, miasta lub obszaru.

Szczególną ostrożność należy zachować przy:

- miejscach o identycznych nazwach w różnych krajach lub regionach;
- nazwach ranch, dzielnic, jezior i innych obiektów powtarzających się geograficznie;
- dawnych i współczesnych torach o podobnych nazwach;
- źródłach automatycznie agregujących treści.

## Cytowanie

W plikach Markdown stosuje się zwykłe, opisowe linki.

Dobra forma:

```markdown
- [Oficjalna historia toru – nazwa strony](https://example.com/) – krótki opis tego, co źródło potwierdza.
```

Należy:

- linkować bezpośrednio do właściwej podstrony, a nie tylko strony głównej;
- krótko opisywać, do czego dane źródło zostało użyte;
- zachowywać oryginalny tytuł lub jednoznaczną nazwę dokumentu;
- unikać surowych URL jako samodzielnego tekstu linku.

## Minimalny standard źródłowy

Wpis nie powinien być publikowany jako ukończony, jeżeli:

- etymologia opiera się wyłącznie na zgadywaniu;
- aktualna nazwa obiektu nie została sprawdzona;
- główne twierdzenia historyczne nie mają wiarygodnego źródła;
- źródło dotyczy innego miejsca o tej samej nazwie;
- jedyną podstawą kluczowego twierdzenia jest niezweryfikowana treść agregatora.

## Wikipedia i Wikimedia Commons

Wikipedia może pomagać w orientacji i wyszukiwaniu źródeł, ale nie powinna zastępować źródeł pierwotnych tam, gdzie są dostępne.

Wikimedia Commons jest natomiast właściwym miejscem do pozyskiwania schematów torów, o ile każdorazowo sprawdzona zostanie strona konkretnego pliku, jego autor, źródło i licencja. Szczegółowe zasady znajdują się w `docs/svg-accessibility-and-licensing.md`.
