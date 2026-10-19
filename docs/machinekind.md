# Machinekind

Status: szkic. Źródło: strona [machinekind.ai](https://machinekind.ai)
(strona główna i [podstrona projektu W01-TEK](https://machinekind.ai/wojtek/))
oraz publiczne repozytoria organizacji; sprawdzone 19 października 2026.
Szczegóły techniczne maszyn są poza zakresem tego repo; tutaj tylko to, co
dotyczy kolektywu jako organizacji.

## W jednym zdaniu

Machinekind to niezależny kolektyw inżynierów uczenia maszynowego, robotyków
i projektantów z Wrocławia, założony w 2025 roku. Hasło kolektywu:
**„Uczymy maszyny poruszać się w świecie ludzi.”** Opis ze strony: kolektyw
buduje warstwę inteligencji razem ze sprzętem, na którym da się ją
uruchomić.

## Pytanie założycielskie

Kolektyw powstał wokół jednego pytania: co musi się wydarzyć, żeby robot
kroczący przestał być demonstracją, a stał się narzędziem. Odpowiedź, którą
przyjął: trzeba go zbudować całego, u siebie.

## Trzy zasady

1. **Budujemy, nie doradzamy.** Każda domena kończy się czymś, co się
   uruchamia: siecią sterującą, ścieżką na maszynę, częścią, która wychodzi
   z obróbki. Kolektyw nie oddaje prezentacji.
2. **Inteligencja powstaje razem ze sprzętem.** Jeden zespół prowadzi całą
   drogę, od zamiaru po moment na wale. Model nie jest przerzucany „przez
   mur” do integracji, bo po drugiej stronie muru siedzą ci sami ludzie.
3. **Pierwsza maszyna już chodzi.** Czworonóg W01-TEK nie jest
   wizualizacją; jest bazą platformy, a kolejne wersje powstają na tej samej
   konstrukcji, nie od zera.

## Cztery domeny

Cały stos, jeden zespół: cztery domeny po dwie osoby, bez oddawania żadnego
odcinka na zewnątrz.

| Domena | Czym się zajmuje | Słowa klucze |
| --- | --- | --- |
| Locomotion AI | Chód uczony w symulatorze pełnej dynamiki i przenoszony na maszynę | sim-to-real, RL |
| World Models & VLM | Modele świata i modele wizyjno-językowe: co maszyna widzi, gdzie może stanąć, co z tego wynika dla następnego kroku | VLM, zamiar |
| Robotics Engineering & Manufacturing | Konstrukcja i napędy: napędy bezpośrednie, nogi o zamkniętym łańcuchu kinematycznym, sztywność ze struktury zamiast z masy | direct drive, closed-loop |
| Design & Program | Harmonogram, prowadzenie projektu i forma maszyny; forma wynika z obciążenia | program, design |

## Takt maszyny

Trzy warstwy sterowania, każda o rząd wielkości wolniejsza od poprzedniej:
im wyżej, tym bardziej o zamiarze niż o momencie na wale.

| Częstotliwość | Warstwa |
| --- | --- |
| 400 Hz | pętla momentu |
| 50 Hz | sieć lokomocyjna |
| 1 Hz | rozumienie przestrzeni |

## Nazwa i znak

Maszyny nie są osobnym gatunkiem. Są przedłużeniem tego, co ludzkie, a granica
przebiega dokładnie tam, gdzie stykają się dwie dłonie. Stąd znak kolektywu:
dwie dłonie, maszyny i człowieka.

## Zespół

Skład publiczny na stronie kolektywu: 8 osób, cztery domeny, po dwie na
domenę. Według strony część zespołu pracuje na co dzień w biznesie
i spółkach, część naukowo.

| Domena | Osoby |
| --- | --- |
| Locomotion AI | Michał Pogoda-Rosikoń, Marcin Wysocki |
| World Models & VLM | Grzegorz Piotrowski, Maciej Gruszczyński |
| Robotics Engineering & Manufacturing | Jakub Chmielewski, Stepan Yurtsiv |
| Design & Program | Przemysław Nowak, Grzegorz Borkowski |

## Projekt W01-TEK i współpraca z Politechniką Wrocławską

To najważniejszy fakt dla koła naukowego: kolektyw już współpracuje
z uczelnią. Na stronie projekt jest podpisany **„PWr × Machinekind”**.

- **W01-TEK („Wojtek”)**: czworonożny robot kroczący, „Projekt 01 ·
  aktywny”. Od szkicu do prototypu w rok, pierwszy krok w 2025, pełne
  sterowanie AI od 2026. Imię po niedźwiedziu Wojtku.
- **Miejsce powstania**: Politechnika Wrocławska, Wydział Mechaniczny,
  Laboratorium Mechatroniki i Robotyki (LMiR) Katedry Podstaw Konstrukcji
  Maszyn i Układów Mechatronicznych. Czworonóg jest rozszerzeniem
  prowadzonej tam linii robotów mobilnych i inspekcyjnych.
- **Własność**: „Maszyna jest własnością Politechniki Wrocławskiej.” Nie
  kolektywu.
- **Podział pracy** (strona): po stronie uczelni konstrukcja, mechanika
  i wykonanie; po stronie Machinekind warstwa AI, inżynieria robotyki,
  design i prowadzenie projektu.
- **Osoby po stronie uczelni** wymienione na stronie:

  | Jednostka PWr | Rola | Osoby |
  | --- | --- | --- |
  | Laboratorium Mechatroniki i Robotyki | kierownictwo naukowe | dr hab. inż. Jarosław Szrek, prof. uczelni |
  | Laboratorium Mechatroniki i Robotyki | konstrukcja i wykonanie | Jakub Delicat, Artur Muraszkowski, Błażej Dębogórski |
  | Katedra Sztucznej Inteligencji | kierownictwo naukowe | dr hab. inż. Tomasz Kajdanowicz |

- **Rodowód** (strona i repozytorium `w01-tek`): robot zaczynał jako
  4BarBot w LMiR; praca magisterska z 2025 r. *Comparative studies on
  walking control algorithms for the quadruped robot 4BarBot*. Etap 2026
  na osi czasu strony: „Pierwsza publikacja o maszynie”; czy publikacja się
  ukazała: do ustalenia.
- **Obecny etap** (strona): iteracje mechaniczne, przeróbki elementów
  i wydruki 3D nowych części.

Co z tego wynika dla koła, a czego strona nie rozstrzyga: patrz
[kolo-naukowe/README.md](../kolo-naukowe/README.md).

## Inne publiczne działania

- **Humanoid**: kolektyw prowadzi prace nad humanoidem (publiczne
  repozytoria `humanoid-lab`, setup treningu RL lokomocji humanoida,
  i `humanoid-construction`, dokumentacja budowy). Strona machinekind.ai
  go nie opisuje; własność i miejsce maszyny: do ustalenia.
- **Hackathon 18–19 września 2026**: projekt „Sortownia i Physical AI” na
  platformie Open Mercato (repozytorium `openmercato_garbagekind`). Nazwa
  i organizator hackathonu: do ustalenia, README ich nie podaje.
- **Materiał edukacyjny**: w repozytorium `w01-tek` jest notebook Colab
  „Wojtek: uczenie chodu krok po kroku”, prowadzący od symulacji do
  porównania własnej polityki z polityką z robota
  ([learning/wojtek_rl_course](https://github.com/machinekind/w01-tek/tree/main/learning/wojtek_rl_course)).
  Kandydat na materiał wstępny dla domeny Locomotion AI.
- **Generator kart „PRELEGENT”** na LinkedIna (repozytorium
  `karta-prelegenta`). Do jakich wydarzeń powstał i lista wystąpień
  kolektywu: do ustalenia.
- **Zaproszenie na pokaz**: strona zaprasza inwestorów, partnerów
  przemysłowych i media na pokaz maszyny we Wrocławiu.

## Kontakt i obecność

- Strona: [machinekind.ai](https://machinekind.ai) (Astro); dwie podstrony:
  główna i `/wojtek/`. Adres e-mail kontaktowy jest na stronie; tutaj go
  nie powielamy.
- GitHub: [github.com/machinekind](https://github.com/machinekind),
  organizacja założona 30 czerwca 2026; mapa repozytoriów w
  [repozytoria.md](repozytoria.md).
- Lokalizacja: Wrocław. Strona: „Niezależny kolektyw. Wrocław.”
- Formalna forma prawna kolektywu: do ustalenia; strona jej nie podaje
  (istotne dla umowy z uczelnią, issue
  [#3](https://github.com/machinekind/machinekind-students/issues/3)).

## Czego nie ma w źródłach

Strona i repozytoria nie podają: formy prawnej, NIP ani KRS, adresu
siedziby, profili w mediach społecznościowych (strona do żadnych nie
linkuje), finansowania, treści umowy
z PWr ani jej zakresu, listy publikacji i wystąpień. Wszystko to: do
ustalenia.
