# Jak współtworzyć to repozytorium

Repozytorium jest dokumentacyjne: opisuje kolektyw Machinekind i zakładane
przy nim koło naukowe. Nie ma tu kodu ani dokumentacji technicznej robotów;
projekty sprzętowe mają własne repozytoria (lista w
[docs/repozytoria.md](docs/repozytoria.md)).

## Język i nazwy

- Piszemy po polsku, także w issue, pull requestach i opisach commitów.
- Nazwa organizacji to **Machinekind** (wielka litera, jedno słowo);
  w adresach i identyfikatorach `machinekind`.

## Jak zgłosić sprawę

Załóż issue z jednego z szablonów:

| Szablon | Kiedy |
| --- | --- |
| Pytanie do ustalenia | decyzja, której ktoś musi podjąć, zanim ruszymy dalej (etykieta `do-ustalenia`) |
| Propozycja zadania semestralnego | pomysł na zadanie do [program.md](kolo-naukowe/program.md) |
| Zgłoszenie do koła | chcesz dołączyć do koła |

Drobne poprawki (literówka, martwy link) możesz od razu zgłosić pull
requestem, bez issue.

## Jak zgłosić zmianę

1. Utwórz gałąź od `main`. Nie pushujemy bezpośrednio na `main`.
2. Wprowadź zmianę. Jeden pull request to jedna sprawa.
3. Sprawdź białe znaki:

   ```bash
   git diff --check
   ```

4. Otwórz pull request do `main`. W opisie napisz, co zmieniasz, skąd masz
   fakty i czego nie udało się potwierdzić. Jeśli PR zamyka issue, dopisz
   `Closes #numer`.

## Linia „Status:”

Każdy dokument w `kolo-naukowe/` zaczyna się (pod tytułem) linią `Status:`
z jedną z wartości:

| Status | Znaczenie |
| --- | --- |
| `szkic` | propozycja, można swobodnie zmieniać |
| `w uzgodnieniu` | treść jest dyskutowana z osobami, które muszą ją przyjąć (opiekun, uczelnia, kolektyw) |
| `przyjęty` | obowiązuje; zmiana wymaga nowej decyzji |

Zmiana statusu na `przyjęty` wymaga w tym samym pull requeście wpisu
w [kolo-naukowe/decyzje.md](kolo-naukowe/decyzje.md): data, co postanowiono,
dlaczego, kto. Dokumenty w `docs/` też mają linię `Status:`, choć ta zasada
ich nie obejmuje.

## Fakty i „do ustalenia”

- Fakty o Machinekind bierzemy ze strony [machinekind.ai](https://machinekind.ai)
  i z publicznych repozytoriów organizacji. Fakty o uczelniach: z ich aktów
  prawnych i oficjalnych stron, z linkiem do źródła.
- Nie dopisujemy dat, liczb ani nazwisk, których nie da się sprawdzić.
  Brak danych oznaczamy jawnie: `do ustalenia`. Rzecz, dla której nie
  znaleźliśmy źródła, oznaczamy jako `niepotwierdzone`.
- Decyzje należą do ludzi. Przy otwartej decyzji zostaw `do ustalenia`
  i załóż issue z szablonu „Pytanie do ustalenia”.

## Dane osobowe

Repozytorium i jego issue są publiczne. Nie zapisujemy w nich:

- adresów e-mail, numerów telefonów, numerów albumów, loginów, haseł;
- adresów prywatnej infrastruktury;
- danych osobowych innych niż te, które są już publiczne na stronie
  kolektywu.

Listy członków z danymi kontaktowymi, których wymagają uczelnie, idą
wyłącznie do uczelni, nie tutaj.

## Licencja

Nowe pliki są na licencji Apache-2.0 (patrz [LICENSE](LICENSE)), chyba że
autor wyraźnie zaznaczy inną.
