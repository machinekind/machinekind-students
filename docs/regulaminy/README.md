# Regulaminy kół naukowych: wzorce z Wrocławia

Status: szkic. Zebrane 19 października 2026.

Materiał, na którym wzorujemy [statut koła](../../kolo-naukowe/statut.md):
akty wrocławskich uczelni o kołach naukowych i regulaminy istniejących kół.
Procedurę rejestracji na PWr i UWr opisuje
[docs/rejestracja-kola.md](../rejestracja-kola.md).

**To są opracowania, nie kopie.** Każdy plik zawiera strukturę dokumentu,
kluczowe zapisy z numerami paragrafów, krótkie cytaty i link do oryginału.
Pełnych tekstów nie przechowujemy, z dwóch powodów: statuty kół są
utworami ich autorów, nie naszymi na licencji Apache-2.0; oryginały zawierają
dane kontaktowe, których to repo nie przechowuje. Przed cytowaniem w piśmie
do uczelni sprawdź oryginał.

## Akty uczelni

| Plik | Uczelnia i akt | Najważniejsze dla nas |
| --- | --- | --- |
| [uczelnia-uwr.md](uczelnia-uwr.md) | UWr, Zarządzenie 219/2023 | 6 wymaganych elementów statutu, min. 5 założycieli, opiekun tylko z UWr, sponsoring przez umowę z uczelnią |
| [uczelnia-pwr.md](uczelnia-pwr.md) | PWr, szablon regulaminu i informator DWAS | układ regulaminu, którego uczelnia oczekuje; sprawozdanie do 15 stycznia |
| [uczelnia-pwr-statut.md](uczelnia-pwr-statut.md) | PWr, Statut z 10.07.2025, § 47, 51, 52 | Rektor prowadzi tylko spis organizacji; nazwa i symbole PWr za zgodą |
| [uczelnia-umw.md](uczelnia-umw.md) | UMW, Zarządzenie 149/XVI R/2023 ze zmianami | siedziba poza uczelnią, drugi opiekun, rewers sprzętu, koło nie zawiera umów |
| [uczelnia-upwr.md](uczelnia-upwr.md) | UPWr, Zarządzenie 208/2021 ze zmianami (ost. 186/2025) | opiekun organizacyjny obok naukowego, coroczna ocena koła |
| [uczelnia-uew.md](uczelnia-uew.md) | UEW, Statut, § 95 | minimalny pakiet założycielski jako lista kontrolna |
| [uczelnia-awf.md](uczelnia-awf.md) | AWF, Regulamin STN 2025 | sprawozdanie jako dorobek, coroczny pokaz |

## Regulaminy i statuty kół

| Plik | Koło | Najważniejsze dla nas |
| --- | --- | --- |
| [kolo-pwr-solvro.md](kolo-pwr-solvro.md) | KN Solvro, PWr (WIT, AI) | członkowie nowi i aktywni, osoby spoza PWr z ograniczonymi prawami, oświadczenie o własności intelektualnej, sekcje |
| [kolo-pwr-automatyk.md](kolo-pwr-automatyk.md) | SNS Automatyk, PWr (Wydział Elektryczny) | rekrutacja przez zadanie i okres próbny, zasady sprzętu, funkcja od partnerów |
| [kolo-pwr-m3.md](kolo-pwr-m3.md) | KN M3, PWr (mikroinżynieria) | członkowie bierni (absolwenci), wykluczenie za bierność |
| [kolo-pwr-sisk.md](kolo-pwr-sisk.md) | KN SISK, PWr (WIT) | model silnego opiekuna, dwa podpisy przy finansach |
| [kolo-uwr-kbi.md](kolo-uwr-kbi.md) | Koło Badań Interdyscyplinarnych, UWr | jedyny znaleziony aktualny statut koła UWr; sekcje, walne zdalne, procedura wykluczenia |
| [kolo-umw-wzor-skn.md](kolo-umw-wzor-skn.md) | wzór regulaminu SKN, UMW | BHP jako obowiązek członka, kalendarz wyborów, pierwszeństwo przepisów uczelni |

Publicznych regulaminów kół robotycznych PWr (np. KoNaR, Robocik) ani kół
informatycznych i fizycznych UWr nie znaleźliśmy; jeśli ktoś je zdobędzie
od samych kół, warto dopisać opracowanie.

## Co przejąć do naszego statutu

Propozycje, nie decyzje. Każdą trzeba przyjąć w PR do `statut.md`.

| Propozycja | Skąd | Gdzie w statucie / issue |
| --- | --- | --- |
| Sekcje odpowiadające czterem domenom, z prowadzącym sekcji odpowiedzialnym za cele semestru | Solvro, KBI | nowy paragraf po § 5 |
| Członkostwo dwustopniowe: nowy → aktywny po wykonaniu zadania, które się uruchamia | Solvro, Automatyk | § 4, [#6](https://github.com/machinekind/machinekind-students/issues/6) |
| Rekrutacja przez zadanie wstępne i okres próbny zakończony pokazem | Automatyk | § 4, [#6](https://github.com/machinekind/machinekind-students/issues/6) |
| Członkowie wspierający lub bierni bez prawa wyborczego: absolwenci, mentorzy z kolektywu (jeśli uczelnia dopuści) | Solvro, M3, szablon PWr | § 4 |
| Oświadczenie o własności intelektualnej przy przyjęciu, treść uzgodniona z działem prawnym uczelni | Solvro | § 7 pkt 3, [#4](https://github.com/machinekind/machinekind-students/issues/4) |
| Zasady BHP i korzystania ze sprzętu jako obowiązek członka; naruszenie jako powód wykluczenia | wzór UMW, Automatyk | § 4 ust. 5–6 |
| Rewers przy wypożyczeniu sprzętu, rozliczenie sprzętu przy odejściu i po kadencji | UMW, Automatyk, Solvro | § 3 ust. 4 |
| Ubezpieczenie NNW przy pracy ze sprzętem i wyjazdach | UMW, UWr § 39 | § 4 ust. 5 |
| Drugi termin walnego z kworum obecnych | szablon PWr, KBI | już w § 5 ust. 6 |
| Walne zdalne z głosowaniem przez konta uczelniane | KBI | § 5 |
| Skarbnik jako osobna funkcja; dwa podpisy przy decyzjach finansowych | KBI, SISK, M3 | § 5 ust. 9, § 3 ust. 3 |
| Członek zarządu od współpracy z partnerami (w tym z Machinekind) | Automatyk | § 5 ust. 9, § 7 |
| Opiekun organizacyjny lub drugi opiekun obok naukowego | UPWr, UMW | § 6, [#2](https://github.com/machinekind/machinekind-students/issues/2) |
| Siedziba lub miejsce pracy poza uczelnią zgłoszone przez partnera | UMW § 3 | § 1 ust. 4, [#5](https://github.com/machinekind/machinekind-students/issues/5) |
| Plan i podsumowanie kadencji; sprawozdanie jako dorobek (co działa), nie tylko finanse | Solvro, AWF | § 8 |
| Rozdzielenie mienia przy rozwiązaniu: uczelni wraca do uczelni, sprzęt Machinekind do kolektywu | KBI, Automatyk | już w § 10 ust. 5 |

Czego nie przejmować:

- działalności odpłatnej koła (M3, SISK): UWr jej zabrania, na PWr
  niepotwierdzone;
- rozwiązania po sześciu miesiącach bezczynności (KBI): ostrzejsze niż
  przepisy uczelni;
- organów bez opisanych kompetencji (sąd koleżeński i komisja rewizyjna
  w SISK);
- regulaminu bez Walnego Zgromadzenia (Automatyk): szablon PWr go wymaga.

## Czego nie udało się potwierdzić

Każdy plik ma własną sekcję „Niepotwierdzone”. Najważniejsze:

- zarządzenie Rektora PWr o rejestracji kół: dwa wyszukiwania, brak;
- daty uchwalenia regulaminów Automatyka, SISK i M3 oraz to, czy są to
  wersje złożone na uczelni;
- treść oświadczenia o własności intelektualnej Solvro;
- czy PWr przyjął zapis Solvro o członkach spoza uczelni;
- aktualność statutu UEW (BIP wymaga logowania) oraz numer i data
  regulaminu STN AWF.
