# Veterinærverktøy for eierinformasjon

En enkel nettapp som genererer to deler etter konsultasjon:
- **DEL 1:** kort oppsummering for veterinær
- **DEL 2:** informasjon til dyreeier

Appen er laget som en statisk prototype og kan kjøres direkte i nettleseren uten Python, server eller database.

## Innhold i prosjektet

- `index.html` – selve nettsiden
- `css/styles.css` – design og layout
- `js/app.js` – logikk for skjema og generering
- `data/templates.js` – diagnosemaler og tekster

## Diagnoser i denne versjonen

- Urinveisinfeksjon hos hund
- Ørebetennelse hos hund
- Akutt mage-/tarmirritasjon hos katt

## Slik åpner du appen lokalt

1. Last ned alle filene.
2. Pakk ut mappen.
3. Åpne `index.html` i en nettleser.

## Slik legger du den i GitHub

### Metode 1: Last opp filene via nettleseren
GitHub lar deg opprette et nytt repository, og deretter laste opp filer via **Add file** → **Upload files**. Det er også mulig å opprette nye filer via **Add file** → **Create new file**. citeturn238782search0turn238782search9turn238782search13

1. Logg inn på GitHub.
2. Klikk **New repository**.
3. Gi repoet et navn, for eksempel `veterinar-tekstverktoy`.
4. Klikk **Create repository**.
5. Velg **Add file** → **Upload files**.
6. Last opp hele mappen eller alle filene.
7. Skriv en commit-melding, for eksempel `Første versjon av veterinærverktøy`.
8. Klikk **Commit changes**.

### Metode 2: Rediger direkte i GitHub
GitHub har både enkel filredigering i nettleseren og den web-baserte editoren `github.dev`, som kan åpnes direkte fra et repo. Dokumentasjonen beskriver `github.dev` som en lettvekts editor i nettleseren der du kan navigere i filer og committe endringer. citeturn238782search1turn238782search5turn238782search10

1. Åpne repoet ditt.
2. Trykk `.` på tastaturet for å åpne `github.dev`.
3. Opprett eller rediger filer.
4. Commit endringene fra editoren.

## Slik publiserer du appen med GitHub Pages
GitHub Pages kan publisere nettstedet ditt fra en branch eller annen publiseringskilde i repoet. citeturn238782search11turn238782search15

1. Gå til repoet ditt.
2. Åpne **Settings**.
3. Velg **Pages**.
4. Under publishing source velger du branchen du vil publisere fra, vanligvis `main`.
5. Velg rotmappen (`/root`) hvis prosjektet ligger i roten av repoet.
6. Lagre.
7. Etter kort tid får du en nettadresse til appen.

## Videre utvikling

Neste naturlige steg er å:
- legge til flere diagnoser i `data/templates.js`
- lage flere informasjonsnivåer
- legge til eksport til PDF
- legge til kvalitetssikring av språk og struktur
- eventuelt koble appen til en AI-modell senere

## Viktig

Innholdet i denne prototypen må faglig kvalitetssikres før bruk i klinisk drift. Det bør også lages en tydelig prosedyre for hvem som eier og vedlikeholder diagnosemalene.
