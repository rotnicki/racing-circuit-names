# Instrukcje dla agentów AI

Ten plik określa zasady pracy agentów AI w repozytorium `racing-circuit-names`.

## Przed rozpoczęciem pracy

Jeżeli zadanie dotyczy dodania, aktualizacji lub weryfikacji toru, najpierw przeczytaj:

1. `docs/methodology.md` – główna metodologia projektu;
2. `docs/source-policy.md` – zasady wyszukiwania i oceny źródeł;
3. `docs/circuit-entry-template.md` – struktura pojedynczego wpisu;
4. `docs/svg-accessibility-and-licensing.md` – zasady pracy z grafikami SVG.

Te dokumenty są źródłem prawdy dla projektu. Jeżeli instrukcje w tym pliku są skrócone, pierwszeństwo mają szczegółowe dokumenty w `docs/`.

## Gdy użytkownik podaje nazwę nowego toru

Nie twórz wpisu wyłącznie na podstawie pamięci modelu.

Wykonaj kolejno:

1. zidentyfikuj dokładnie tor i lokalizację;
2. sprawdź aktualną oficjalną nazwę;
3. ustal nazwę powszechnie używaną;
4. zbadaj język i znaczenie nazwy;
5. zbadaj rzeczywistą etymologię;
6. sprawdź historię nazwy toru i miejsca;
7. rozdziel nazwy geograficzne, historyczne i sponsorskie;
8. znajdź źródła pierwotne, oficjalne, językowe lub historyczne;
9. znajdź odpowiedni wolno licencjonowany SVG, jeśli jest dostępny;
10. dodaj dostępnościowe metadane SVG zgodnie ze standardem projektu;
11. utwórz lub zaktualizuj `circuits/<slug>.md`;
12. zapisz grafikę w `assets/circuits/<slug>.svg`;
13. zaktualizuj indeks w `README.md`;
14. wykonaj końcową kontrolę jakości.

## Zasady badawcze

- Preferuj źródła oficjalne, pierwotne, archiwalne, urzędowe i językowe.
- Nie przedstawiaj domysłu jako etymologii.
- Nie wyprowadzaj znaczenia nazwy wyłącznie z podobieństwa do współczesnego słowa.
- Nie mieszaj źródeł odnoszących się do różnych miejsc o tej samej nazwie.
- Jeżeli wiarygodne źródła są sprzeczne, opisz niepewność.
- Nazwy sponsorskie i inne informacje zmienne sprawdzaj ponownie przy każdej aktualizacji.
- Zachowuj oryginalne znaki diakrytyczne nazw własnych.

## Zasady publikacji

- Jeden tor = jeden plik w `circuits/`.
- Jeden podstawowy schemat toru = jeden plik SVG w `assets/circuits/`.
- Nie twórz zbędnych dodatkowych wersji ani „opakowań” SVG.
- Obraz ma być osadzony bezpośrednio w Markdownie.
- Tekst alternatywny w Markdownie oraz `title` i `desc` w SVG są wymagane, jeśli grafika jest dodawana.
- Informacja o autorze, źródle, licencji i modyfikacji SVG ma znajdować się bezpośrednio pod grafiką.
- Każdy nowy tor dodaj do sekcji `Opracowane tory` w `README.md`.

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
