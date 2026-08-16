# Racing Circuit Names

Repozytorium poświęcone nazewnictwu torów wyścigowych z różnych części świata: znaczeniu, pochodzeniu, etymologii i historii nazw samych obiektów oraz — tam, gdzie istnieje wartościowy materiał źródłowy — nazw ich charakterystycznych elementów.

Celem projektu jest dokumentowanie odpowiedzi na pytania takie jak:

- co dosłownie oznacza nazwa toru;
- z jakiego języka pochodzi;
- dlaczego tor otrzymał właśnie taką nazwę;
- czy nazwa pochodzi od miejsca, osoby, obiektu geograficznego, sponsora albo wydarzenia historycznego;
- jak najlepiej wyjaśnić jej znaczenie po polsku, bez sztucznego tłumaczenia utrwalonej nazwy własnej;
- jakie inne nazwy tor nosił w przeszłości;
- czy tor posiada utrwalone nazwy charakterystycznych zakrętów, prostych, szykan, sekcji lub innych elementów i skąd te nazwy pochodzą.

## Autorstwo i wykorzystanie AI

**Koncepcja projektu, redakcja i nadzór merytoryczny:** Mikołaj Rotnicki  
**Wsparcie badawcze i redakcyjne dotychczasowych opracowań:** ChatGPT (OpenAI)

Projekt powstał z inicjatywy Mikołaja Rotnickiego. Narzędzia AI są wykorzystywane jako wsparcie w wyszukiwaniu i porównywaniu źródeł, porządkowaniu materiału, przygotowywaniu wersji roboczych tekstu oraz technicznej obsłudze repozytorium. Metodologia, zakres projektu, decyzje redakcyjne i sposób prezentacji opracowań są utrzymywane w samym repozytorium.

Podpis nie oznacza, że każda linia tekstu została napisana samodzielnie bez użycia AI. Ma transparentnie wskazywać rzeczywisty sposób powstawania opracowań. Jeżeli w przyszłości konkretne opracowanie powstanie przy istotnym wsparciu innego systemu AI lub innego współtwórcy, informacja w jego stopce powinna zostać odpowiednio zaktualizowana.

Autorstwo i licencje materiałów zewnętrznych, w szczególności schematów SVG z Wikimedia Commons, są dokumentowane oddzielnie i nie są objęte powyższym podpisem redakcyjnym.

## Zasada opracowania

Każdy tor ma osobny plik w katalogu `circuits/`. Wpis powinien w miarę możliwości zawierać:

1. pełną nazwę toru;
2. lokalizację;
3. język i dosłowne znaczenie nazwy;
4. pochodzenie nazwy;
5. objaśnienie po polsku;
6. historię nazw i nazw sponsorskich, jeśli jest istotna;
7. nazwy charakterystycznych elementów toru, jeżeli research wykaże utrwalone i warte objaśnienia nazewnictwo;
8. źródła;
9. bezpośrednio osadzony schemat toru, jeżeli dostępny jest odpowiedni plik na właściwej licencji.

Sprawdzenie nazewnictwa charakterystycznych elementów jest częścią standardowego researchu, ale sama sekcja jest opcjonalna. Nie tworzymy katalogu elementów oznaczonych wyłącznie numerami ani nie wymyślamy nazw tam, gdzie źródła ich nie potwierdzają.

Treść repozytorium jest obecnie tworzona po polsku. Angielska nazwa repozytorium pozostawia możliwość późniejszego dodania wersji anglojęzycznej bez zmiany nazwy projektu.

## Standard badawczy i publikacyjny

Metoda pracy jest zapisana w repozytorium, aby kolejne opracowania mogły powstawać według tego samego schematu niezależnie od tego, czy przygotowuje je człowiek, czy agent AI.

- [Metodologia opracowania](docs/methodology.md) – zakres badań, rozróżnienia nazw, zasady etymologiczne, nazwy charakterystycznych elementów, autorstwo i kontrola jakości.
- [Polityka źródeł](docs/source-policy.md) – hierarchia źródeł, ocena wiarygodności, weryfikacja i rozwiązywanie konfliktów, także dla nazw elementów toru.
- [Playbook wyszukiwania internetowego](docs/internet-research-playbook.md) – krok po kroku: jak rozdzielać ścieżki badawcze, jak badać nazwę toru i nazwy jego charakterystycznych elementów, używać języka lokalnego, przechodzić od źródeł wtórnych do pierwotnych i kiedy zakończyć research.
- [Szablon wpisu toru](docs/circuit-entry-template.md) – zalecana struktura pliku w `circuits/`, w tym opcjonalna sekcja nazw charakterystycznych elementów.
- [SVG: dostępność, licencjonowanie i sposób użycia](docs/svg-accessibility-and-licensing.md) – wybór, kopiowanie, osadzanie i dostosowanie schematów torów.
- [Instrukcje dla agentów AI](AGENTS.md) – skrócone reguły pracy w repozytorium.
- [Agent Skill: Racing Circuit Research](.agents/skills/racing-circuit-research/SKILL.md) – powtarzalna procedura badania, przygotowania i publikacji kolejnego toru.

Pliki w `docs/` stanowią neutralne źródło prawdy dla projektu. Instrukcje przeznaczone dla agentów odwołują się do nich zamiast powielać całą metodologię.

## Historia rozwoju metodologii

Rozszerzenie projektu o **nazwy charakterystycznych elementów toru** zostało najpierw przetestowane eksperymentalnie na dwóch kontrastowych przypadkach: bogato nazwanym Silverstone oraz Torze Poznań, dla którego w sprawdzonych oficjalnych materiałach nie znaleziono porównywalnego systemu utrwalonych nazw. Dokumentacja pilotażu pozostaje w `docs/experiments/` jako zapis procesu wypracowania reguły.

## Opracowane tory

- [Laguna Seca](circuits/laguna-seca.md)
- [Interlagos](circuits/interlagos.md)
- [Hockenheimring](circuits/hockenheim.md)
- [Kyalami](circuits/kyalami.md)
- [Tor Poznań](circuits/tor-poznan.md)
- [Silverstone](circuits/silverstone.md)
- [Silesia Ring](circuits/silesia-ring.md)
