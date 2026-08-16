# Racing Circuit Names

Repozytorium poświęcone nazwom torów wyścigowych z różnych części świata: ich znaczeniu, pochodzeniu, etymologii i historii.

Celem projektu jest dokumentowanie odpowiedzi na pytania takie jak:

- co dosłownie oznacza nazwa toru;
- z jakiego języka pochodzi;
- dlaczego tor otrzymał właśnie taką nazwę;
- czy nazwa pochodzi od miejsca, osoby, obiektu geograficznego, sponsora albo wydarzenia historycznego;
- jak najlepiej wyjaśnić jej znaczenie po polsku, bez sztucznego tłumaczenia utrwalonej nazwy własnej;
- jakie inne nazwy tor nosił w przeszłości.

## Zasada opracowania

Każdy tor ma osobny plik w katalogu `circuits/`. Wpis powinien w miarę możliwości zawierać:

1. pełną nazwę toru;
2. lokalizację;
3. język i dosłowne znaczenie nazwy;
4. pochodzenie nazwy;
5. objaśnienie po polsku;
6. historię nazw i nazw sponsorskich, jeśli jest istotna;
7. źródła;
8. bezpośrednio osadzony schemat toru, jeżeli dostępny jest odpowiedni plik na właściwej licencji.

Treść repozytorium jest obecnie tworzona po polsku. Angielska nazwa repozytorium pozostawia możliwość późniejszego dodania wersji anglojęzycznej bez zmiany nazwy projektu.

## Standard badawczy i publikacyjny

Metoda pracy jest zapisana w repozytorium, aby kolejne opracowania mogły powstawać według tego samego schematu niezależnie od tego, czy przygotowuje je człowiek, czy agent AI.

- [Metodologia opracowania](docs/methodology.md) – zakres badań, rozróżnienia nazw, zasady etymologiczne i kontrola jakości.
- [Polityka źródeł](docs/source-policy.md) – hierarchia źródeł, wyszukiwanie, weryfikacja i rozwiązywanie konfliktów.
- [Szablon wpisu toru](docs/circuit-entry-template.md) – zalecana struktura pliku w `circuits/`.
- [SVG: dostępność, licencjonowanie i sposób użycia](docs/svg-accessibility-and-licensing.md) – wybór, kopiowanie, osadzanie i dostosowanie schematów torów.
- [Instrukcje dla agentów AI](AGENTS.md) – skrócone reguły pracy w repozytorium.
- [Agent Skill: Racing Circuit Research](.agents/skills/racing-circuit-research/SKILL.md) – powtarzalna procedura badania, przygotowania i publikacji kolejnego toru.

Pliki w `docs/` stanowią neutralne źródło prawdy dla projektu. Instrukcje przeznaczone dla agentów odwołują się do nich zamiast powielać całą metodologię.

## Opracowane tory

- [Laguna Seca](circuits/laguna-seca.md)
- [Interlagos](circuits/interlagos.md)
- [Hockenheimring](circuits/hockenheim.md)
