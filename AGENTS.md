# Instrukcje dla agentów AI

Ten plik określa zasady pracy agentów AI w repozytorium `racing-circuit-names`.

## Przed rozpoczęciem pracy

Jeżeli zadanie dotyczy dodania, aktualizacji lub weryfikacji toru, najpierw przeczytaj:

1. `docs/methodology.md` – główna metodologia projektu, w tym zasady autorstwa i wykorzystania AI;
2. `docs/source-policy.md` – zasady oceny i doboru źródeł;
3. `docs/internet-research-playbook.md` – szczegółowa procedura wyszukiwania w Internecie;
4. `docs/circuit-entry-template.md` – struktura pojedynczego wpisu;
5. `docs/svg-accessibility-and-licensing.md` – zasady pracy z grafikami SVG.

Te dokumenty są źródłem prawdy dla projektu. Jeżeli instrukcje w tym pliku są skrócone, pierwszeństwo mają szczegółowe dokumenty w `docs/`.

## Gdy użytkownik podaje nazwę nowego toru

Nie twórz wpisu wyłącznie na podstawie pamięci modelu.

Wykonaj kolejno:

1. zidentyfikuj dokładnie tor i lokalizację;
2. wykonaj research zgodnie z `docs/internet-research-playbook.md`, rozdzielając wyszukiwanie na osobne ścieżki;
3. sprawdź aktualną oficjalną nazwę;
4. ustal nazwę powszechnie używaną;
5. zbadaj język i znaczenie nazwy;
6. zbadaj rzeczywistą etymologię;
7. sprawdź historię nazwy toru i miejsca;
8. rozdziel nazwy geograficzne, historyczne i sponsorskie;
9. sprawdź, czy współczesny lub historycznie istotny układ posiada utrwalone nazwy charakterystycznych elementów;
10. jeżeli takie nazwy istnieją, zbadaj osobno ich użycie, status, pochodzenie, warianty i historię;
11. znajdź źródła pierwotne, oficjalne, językowe lub historyczne;
12. znajdź odpowiedni wolno licencjonowany SVG, jeśli jest dostępny;
13. dodaj dostępnościowe metadane SVG zgodnie ze standardem projektu;
14. utwórz lub zaktualizuj `circuits/<slug>.md`;
15. zapisz grafikę w `assets/circuits/<slug>.svg`;
16. dodaj prawidłową stopkę redakcyjną wskazującą Mikołaja Rotnickiego oraz rzeczywiście użyte wsparcie AI;
17. zaktualizuj indeks w `README.md`;
18. wykonaj końcową kontrolę jakości.

## Nazwy charakterystycznych elementów

Sprawdzenie tej warstwy nazewnictwa jest obowiązkowe, ale jej publikacja jest warunkowa.

Mogą to być:

- zakręty;
- szykany;
- nawroty;
- proste;
- sekwencje zakrętów;
- większe sekcje;
- inne utrwalone nazwane fragmenty toru.

Zasady:

- nie ograniczaj researchu tylko do zakrętów;
- nie twórz sekcji z elementów oznaczonych wyłącznie numerami;
- odróżniaj potwierdzone użycie nazwy od potwierdzonego pochodzenia nazwy;
- ustalaj, czy nazwa jest oficjalna, tradycyjna, potoczna, komentatorska, sponsorska lub historyczna, jeśli ma to znaczenie;
- nie wymyślaj etymologii na podstawie brzmienia;
- przy nazwie osoby, miejsca, organizacji lub innego toru sprawdź także to źródłowe odniesienie;
- zachowuj warianty pisowni i niepewność, gdy źródła są niespójne;
- dla współczesnego układu preferuj kolejność przejazdu;
- brak odpowiednio udokumentowanych nazw jest prawidłowym wynikiem i nie wymaga tworzenia sekcji.

## Zasady badawcze

- Preferuj źródła oficjalne, pierwotne, archiwalne, urzędowe i językowe.
- Nie ograniczaj wyszukiwania do języka angielskiego; dla etymologii i historii miejsc używaj również języka lokalnego.
- Nie przedstawiaj domysłu jako etymologii.
- Nie wyprowadzaj znaczenia nazwy wyłącznie z podobieństwa do współczesnego słowa.
- Nie mieszaj źródeł odnoszących się do różnych miejsc o tej samej nazwie.
- Jeżeli wiarygodne źródła są sprzeczne, opisz niepewność.
- Nazwy sponsorskie i inne informacje zmienne sprawdzaj ponownie przy każdej aktualizacji.
- Zachowuj oryginalne znaki diakrytyczne nazw własnych.
- Nie kończ researchu na pierwszym sensownym artykule; zastosuj kryteria zakończenia wyszukiwań z playbooka.

## Zasady publikacji

- Jeden tor = jeden plik w `circuits/`.
- Jeden podstawowy schemat toru = jeden plik SVG w `assets/circuits/`.
- Nie twórz zbędnych dodatkowych wersji ani „opakowań” SVG.
- Obraz ma być osadzony bezpośrednio w Markdownie.
- Tekst alternatywny w Markdownie oraz `title` i `desc` w SVG są wymagane, jeśli grafika jest dodawana.
- Informacja o autorze, źródle, licencji i modyfikacji SVG ma znajdować się bezpośrednio pod grafiką.
- Sekcja `Nazwy charakterystycznych elementów toru` jest opcjonalna i powstaje tylko wtedy, gdy research wykazał utrwalone nazwy wnoszące wartość do projektu.
- Nie używaj tabeli jako domyślnej formy tej sekcji; preferuj nagłówki i krótkie bloki tekstu.
- Każdy nowy tor dodaj do sekcji `Opracowane tory` w `README.md`.

## Autorstwo i wsparcie AI

Koncepcja projektu, redakcja i nadzór merytoryczny są przypisane **Mikołajowi Rotnickiemu**.

Jeżeli opracowanie powstaje przy pomocy ChatGPT, stopka powinna zawierać:

```text
Redakcja: Mikołaj Rotnicki.
Wsparcie badawcze i redakcyjne: ChatGPT (OpenAI).
```

Jeżeli wykorzystano inny system AI lub dodatkowego współtwórcę, stopkę należy dostosować do rzeczywistego przebiegu pracy. Nie wolno przypisywać udziału narzędziu, które nie uczestniczyło w opracowaniu.

Podpis redakcyjny nie zastępuje atrybucji materiałów zewnętrznych. Autorzy i licencje SVG, fotografii i innych materiałów pozostają dokumentowani oddzielnie.

## Zasady zmian

Nie zmieniaj istniejących ustaleń tylko po to, aby ujednolicić styl. Jeżeli nowe źródło podważa wcześniejszy wpis:

1. sprawdź źródło;
2. popraw fakt;
3. popraw zależne od niego fragmenty;
4. zaktualizuj datę wpisu;
5. zachowaj przejrzystą historię zmian w Git.

## Brak dostępu do źródeł

Jeżeli nie możesz zweryfikować informacji wymagającej aktualnego lub zewnętrznego źródła, nie uzupełniaj jej z pamięci jako pewnego faktu. Oznacz brak możliwości weryfikacji albo pozostaw wpis nieukończony.

## Skill

Jeżeli środowisko obsługuje Agent Skills, procedura wykonawcza dla tego projektu znajduje się w:

`.agents/skills/racing-circuit-research/SKILL.md`
