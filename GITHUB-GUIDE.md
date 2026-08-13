# 🚕 Spot the Fare — kom på GitHub (gratis, fast adresse)

Når appen er på GitHub Pages, får du et fast link (fx `ditnavn.github.io/spot-the-fare`)
som altid virker — på telefon og computer, med HTTPS (så "Min position" i Plan også virker).

---

## Trin 1 — Opret et repository (5 min)

1. Log ind på **github.com**
2. Klik på **+** øverst til højre → **New repository**
3. **Repository name:** skriv `spot-the-fare` (små bogstaver)
4. Vælg **Public** (gratis — privat koster penge)
5. Lad resten stå → klik **Create repository**

## Trin 2 — Upload filerne (5 min)

1. Download **`spot-the-fare.zip`** (fra chatten) og pak det ud — du får en mappe med:
   - `index.html`
   - `data/` (med `app_data.json` indeni)
   - `vendor/` (med `leaflet.js` + `leaflet.css` indeni)
   - `BRUGSVEJLEDNING.md`
2. På din nye repo-side: klik **Add file** → **Upload files**
3. **Træk hele indholdet ind** (eller brug "choose your files") — altså:
   `index.html`, mappen `data`, mappen `vendor`, `BRUGSVEJLEDNING.md`
4. Klik **Commit changes** (grøn knap)

> 💡 Trækker du selve mappen ind, er det også fint — GitHub laver mapperne automatisk.

## Trin 3 — Slå GitHub Pages til (2 min)

1. På repo-siden: klik på **Settings** (fanen øverst)
2. I venstre menu: klik **Pages**
3. Under **Build and deployment**:
   - **Source:** vælg `Deploy from a branch`
   - **Branch:** vælg `main` og `/ (root)`
4. Klik **Save**

## Trin 4 — Åbn din app! 🎉

- Vent **1–2 minutter** (GitHub bygger siden)
- Åbn: **`https://DIT-BRUGERNAVN.github.io/spot-the-fare/`**
  (skift `DIT-BRUGERNAVN` til dit brugernavn — det står i adressen når du er logget ind)

**På telefonen:** åbn linket i Chrome → menu (⋯) → **"Tilføj til hjemmeskærm"** → app-ikon på din startskærm. Åbn den derfra, så virker den som en rigtig app (med fuld skærm).

---

## Sådan opdaterer du appen senere

**Opdater data (fx nye lufthavnstal):**
1. Download den nye `app_data.json` fra chatten
2. På repo-siden: klik ind i mappen `data` → `app_data.json`
3. Klik blyanten (✏️ Edit) → **Upload new file** → vælg den nye fil → **Commit changes**
4. Vent 1 minut → appen er opdateret (hold ↻ nede / opdater siden)

**Opdater hele appen:** samme fremgangsmåde som trin 2 — bare træk de nye filer ind igen.

---

## Ofte stillede spørgsmål

**"Siden findes ikke / 404"?**
Vent 1 minut og prøv igen. Tjek også at adressen er `.../spot-the-fare/` med præcis samme navn som repoet.

**Jeg kan ikke finde "Pages" i Settings?**
Det ligger i venstre side-menu — rul lidt ned. (Kræver at du er ejer af repoet — det er du.)

**Virker "Min position" (📍)?**
Ja — på GitHub Pages er der HTTPS, så position virker nu (den virkede ikke fra en lokal fil).

**Vil jeg have dataene offentligt?**
Repoet er public, men der er ingen personlige oplysninger i appen — kun offentlige event-data.
(Hvis du vil have den helt privat, kræver det GitHub Pro.)
