# Koło naukowe przy Machinekind

Status: szkic.

## Cel

Stworzyć koło naukowe, w którym studenci pracują nad zadaniami z czterech
domen Machinekind (lokomocja, modele świata i VLM, konstrukcja i napędy,
prowadzenie projektu i forma) na zasadach kolektywu: każdy semestr kończy się
czymś, co się uruchamia, a nie prezentacją.

Cele koła (regulamin, § 2): rozwój zdolności w kierunku physical AI
w pełnym zakresie budowy humanoidów i czworonogów (AI, automatyka
i sterowanie, robotyka, mechanika, napędy, elektronika, wytwarzanie);
rozwój przedsiębiorczości przez tworzenie zespołów startupowych,
wspieranie startupów członków i łączenie ich z funduszami inwestycyjnymi
i venture builderami; badania naukowe. Koło pracuje jak startup, ale samo
nie prowadzi działalności zarobkowej: startupy działają poza kołem.

## Co koło daje studentom

- Realny sprzęt i realne dane zamiast zadań podręcznikowych.
- Mentoring od osób prowadzących daną domenę w kolektywie.
- Ścieżkę od projektu kołowego do pracy inżynierskiej lub magisterskiej.

## Co koło daje Machinekind

- Rekrutację: stały dopływ osób, które już znają stos i sposób pracy.
- Równoległe eksperymenty, na które zespół ośmiu osób nie ma czasu.
- Zakotwiczenie na uczelni: dostęp do laboratoriów, obróbki i promotorów.

## Punkt wyjścia: istniejąca współpraca z PWr

Według strony kolektywu Machinekind już pracuje z Politechniką Wrocławską
(„PWr × Machinekind”). Robot W01-TEK powstał w Laboratorium Mechatroniki
i Robotyki na Wydziale Mechanicznym, pod kierownictwem naukowym osób z tego
laboratorium i z Katedry Sztucznej Inteligencji, i jest własnością PWr.
Szczegóły w [docs/machinekind.md](../docs/machinekind.md).

To fakt, nie decyzja: wybór uczelni, jednostki i opiekuna zostaje otwarty
(#1, #2). Strona nie mówi, czy istnieje umowa o współpracy ani co
obejmuje: do ustalenia.

## Otwarte pytania

| Pytanie | Dlaczego ważne | Stan | Issue |
| --- | --- | --- | --- |
| Przy której uczelni i jednostce? | Koło musi mieć opiekuna naukowego i być zarejestrowane w uczelnianym rejestrze kół | postanowione: PWr, koło międzywydziałowe, wiodący Wydział Informatyki i Telekomunikacji (W4N), drugi Wydział Mechaniczny; czeka na zgody wydziałów | [#1](https://github.com/machinekind/machinekind-students/issues/1) |
| Kto jest opiekunem naukowym? | Warunek formalny rejestracji; osoba z uczelni, nie z kolektywu | postanowione: T. Kajdanowicz i J. Szrek; czekają zgody | [#2](https://github.com/machinekind/machinekind-students/issues/2) |
| Jaka forma prawna Machinekind? | Potrzebna do umowy o współpracy i do rozliczania sprzętu | do ustalenia | [#3](https://github.com/machinekind/machinekind-students/issues/3) |
| Kto jest właścicielem wyników? | Licencja Apache-2.0 jako domyślna, ale uczelnie mają własne regulaminy IP | do ustalenia | [#4](https://github.com/machinekind/machinekind-students/issues/4) |
| Gdzie fizycznie pracuje koło? | Sprzęt jest we Wrocławiu (W01-TEK w laboratorium PWr, własność uczelni); potrzebne miejsce, w którym studenci mogą go używać | postanowione: siedziba w Katedrze Sztucznej Inteligencji (W4N), bud. D-21, pok. 336 (tymczasowo); prace na sprzęcie w Laboratorium Mechatroniki i Robotyki (WM) | [#5](https://github.com/machinekind/machinekind-students/issues/5) |
| Jak wygląda rekrutacja? | Zadanie wstępne per domena czy otwarte spotkanie | postanowione: zadanie wstępne w sekcji | [#6](https://github.com/machinekind/machinekind-students/issues/6) |
| Budżet pierwszego roku? | Części, obróbka, GPU na trening; źródła: uczelnia, kolektyw, granty | do ustalenia | [#7](https://github.com/machinekind/machinekind-students/issues/7) |

Każde pytanie ma issue z etykietą `do-ustalenia`; dyskusja i decyzja idą
tam, a wynik trafia do tego dokumentu i do `decyzje.md`.

## Kolejne kroki

1. Wybrać uczelnię i jednostkę, znaleźć opiekuna naukowego.
2. Sprawdzić regulamin kół naukowych tej uczelni i dopasować do niego
   `statut.md`. Wymagania PWr i UWr są zebrane w
   [docs/rejestracja-kola.md](../docs/rejestracja-kola.md); statut ma
   warianty dla obu.
3. Spisać program pierwszego semestru w `program.md`: po jednym zadaniu na
   domenę, każde z jasnym kryterium „uruchamia się”.
4. Ustalić zasady IP i licencji z uczelnią, zapisać w `decyzje.md`.
5. Ogłosić rekrutację.
