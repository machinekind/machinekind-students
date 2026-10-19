# Przewodnik dla agentów

To repozytorium jest kontekstem dla studentów pracujących z kolektywem
Machinekind i miejscem, w którym powstaje koło naukowe. Jest w całości
dokumentacyjne.

## Zakres

- Treść dotyczy wyłącznie Machinekind jako organizacji i koła naukowego:
  misja, zespół, domeny, statut, program, decyzje.
- Nie wprowadzaj tu kodu, modeli, konfiguracji ani dokumentacji technicznej
  robotów kolektywu. Projekty sprzętowe mają własne repozytoria; tutaj można
  do nich najwyżej odesłać linkiem w `docs/repozytoria.md`.
- Pisz po polsku. Nazwa organizacji to **Machinekind** (wielka litera, jedno
  słowo), w adresach i identyfikatorach `machinekind`.

## Zasady edycji

- Każdy dokument w `kolo-naukowe/` zaczyna się linią `Status:` z jedną
  z wartości: `szkic`, `w uzgodnieniu`, `przyjęty`. Zmiana statusu na
  `przyjęty` wymaga wpisu w `kolo-naukowe/decyzje.md`.
- Fakty o kolektywie bierz ze strony machinekind.ai i z publicznych
  repozytoriów organizacji. Nie dopisuj dat, liczb ani nazwisk, których nie da
  się tam sprawdzić; brak danych zaznaczaj jawnie jako `do ustalenia`.
- Repozytorium jest publiczne. Nie zapisuj danych osobowych poza tymi, które
  są już publiczne na stronie kolektywu, ani adresów e-mail, numerów
  telefonów, loginów, haseł i adresów prywatnej infrastruktury.
- Nowe pliki są na licencji Apache-2.0, chyba że autor wyraźnie poprosi
  o inną.

## Walidacja

```bash
git diff --check
```

Nic więcej nie trzeba uruchamiać: nie ma tu testów ani budowania.
