# SVG: dostępność, licencjonowanie i sposób użycia

Ten dokument określa standard pracy ze schematami torów w repozytorium `racing-circuit-names`.

## Cel

Schemat toru ma być:

- przechowywany lokalnie w repozytorium;
- wyświetlany bezpośrednio w pliku Markdown danego toru;
- wektorowy, jeżeli odpowiedni SVG jest dostępny;
- używany zgodnie z licencją;
- możliwie dostępny dla użytkowników technologii asystujących.

## Lokalizacja plików

Schematy przechowujemy w:

```text
assets/circuits/
```

Nazwy plików powinny odpowiadać nazwom wpisów, np.:

```text
assets/circuits/interlagos.svg
assets/circuits/laguna-seca.svg
assets/circuits/hockenheim.svg
```

## Preferowane źródło

Preferowane są pliki z Wikimedia Commons, jeżeli strona konkretnego pliku jasno określa:

- autora;
- źródło;
- licencję;
- możliwość ponownego wykorzystania i ewentualnej modyfikacji.

Najlepiej wybierać pliki:

- oznaczone jako `own work` lub o równie jasnym pochodzeniu;
- objęte licencją Creative Commons pozwalającą na ponowne wykorzystanie albo znajdujące się w domenie publicznej;
- przedstawiające właściwy, współczesny lub świadomie wybrany historyczny układ toru.

Należy unikać plików, których opis licencyjny wygląda na sprzeczny ze wskazanym źródłem, np. gdy użytkownik oznaczył grafikę jako własną lub public domain, ale opis wskazuje na skopiowanie jej z komercyjnego źródła.

## Kopiowanie SVG

SVG jest formatem tekstowym XML. Plik można przechowywać w repozytorium jako zwykły plik tekstowy `.svg`.

Preferowana procedura:

1. pobrać lub odczytać oryginalną treść SVG;
2. zapisać ją lokalnie w `assets/circuits/`;
3. zachować geometrię i wygląd oryginału;
4. wprowadzić tylko świadome i udokumentowane modyfikacje;
5. sprawdzić wynik po zapisaniu.

Nie należy odrysowywać toru, jeżeli odpowiedni wolno licencjonowany plik już istnieje.

## Osadzanie w Markdown

Grafikę osadzamy jako zwykły obraz:

```markdown
![Schemat układu toru Interlagos](../assets/circuits/interlagos.svg)
```

Tekst pomiędzy `![` i `]` jest tekstem alternatywnym na poziomie dokumentu Markdown i powinien jasno określać, co przedstawia grafika.

Nie należy celowo opakowywać obrazu w dodatkowy link, chyba że istnieje konkretny powód funkcjonalny.

## Dostępność wewnątrz SVG

Oprócz tekstu alternatywnego w Markdownie dodajemy metadane dostępnościowe bezpośrednio do głównego elementu SVG.

Minimalny wzorzec:

```xml
<svg
  xmlns="http://www.w3.org/2000/svg"
  role="img"
  aria-labelledby="circuit-title circuit-desc">

  <title id="circuit-title">Schemat układu toru ...</title>
  <desc id="circuit-desc">Opis schematu toru ...</desc>

  ...
</svg>
```

### `title`

Powinien być krótki i identyfikować grafikę, np.:

```text
Schemat układu toru Hockenheimring
```

### `desc`

Powinien opisywać istotną zawartość grafiki. Może zawierać m.in.:

- nazwę toru;
- lokalizację;
- informację, że przedstawiono nitkę toru;
- kierunek jazdy;
- oznaczenie startu i mety;
- podpisane charakterystyczne zakręty;
- warianty toru, jeżeli są widoczne i istotne.

Opis nie powinien udawać pełnej audiodeskrypcji, jeżeli nie ma ku temu podstaw, ale powinien przekazywać więcej niż samo powtórzenie nazwy pliku.

## Relacja między `alt`, `title` i `desc`

Stosujemy oba poziomy dostępności:

1. tekst alternatywny w Markdownie;
2. `title` i `desc` wewnątrz SVG.

Nie traktujemy jednego z nich jako automatycznego zamiennika drugiego, ponieważ plik SVG może być używany w różnych kontekstach i przez różne interfejsy.

## Modyfikowanie plików z Creative Commons

Jeżeli licencja pozwala na tworzenie wersji zmodyfikowanych, można dodać metadane dostępnościowe.

Przy takiej modyfikacji należy:

- zachować wymagane wskazanie autora;
- podać źródło;
- podać właściwą licencję;
- zaznaczyć, że plik został zmodyfikowany;
- zachować warunki `ShareAlike`, jeżeli dana licencja ich wymaga.

Jeżeli zmiana ogranicza się do dostępności, warto zapisać to wprost, np.:

```text
W kopii przechowywanej w repozytorium dodano wyłącznie metadane dostępnościowe (`role`, `aria-labelledby`, `title` i `desc`); geometria i wygląd grafiki pozostają bez zmian.
```

Można również umieścić wewnątrz SVG komentarz techniczny, np.:

```xml
<!-- Accessibility metadata added 2026-08-16; geometry and visual appearance unchanged. -->
```

## Podpis licencyjny pod grafiką

Bezpośrednio pod obrazem w pliku toru należy umieścić informację o autorze, źródle, licencji i modyfikacji.

Przykład:

```markdown
*Schemat na podstawie [Autor, „Nazwa pliku.svg”, Wikimedia Commons](URL), licencja [CC BY-SA 3.0](URL_LICENCJI). W kopii przechowywanej w repozytorium dodano wyłącznie metadane dostępnościowe (`role`, `aria-labelledby`, `title` i `desc`); geometria i wygląd grafiki pozostają bez zmian. Zmodyfikowana wersja pozostaje na licencji CC BY-SA 3.0.*
```

Jeżeli plik jest w domenie publicznej, należy mimo to zachować informację o autorze i pochodzeniu jako dobrą praktykę dokumentacyjną.

## Niepewna licencja

Jeżeli status prawny grafiki jest niejasny:

- nie kopiować jej do repozytorium;
- poszukać alternatywnego SVG o jasnym pochodzeniu;
- w ostateczności opublikować wpis bez schematu.

Brak grafiki jest lepszy niż użycie pliku o niepewnym statusie prawnym.

## Kontrola przed publikacją

Przed zakończeniem wpisu sprawdź:

- czy SVG przedstawia właściwy tor i właściwy wariant;
- czy strona źródłowa pliku została zweryfikowana;
- czy autor i licencja są zapisani poprawnie;
- czy zmiany zostały wskazane;
- czy plik znajduje się w `assets/circuits/`;
- czy Markdown osadza grafikę bezpośrednio;
- czy Markdown ma sensowny tekst alternatywny;
- czy SVG ma `role="img"`;
- czy SVG ma `aria-labelledby`;
- czy istnieją powiązane `title` i `desc`;
- czy opis `desc` odpowiada rzeczywistej zawartości grafiki.
