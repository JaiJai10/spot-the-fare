# 🚕 Spot the Fare — Sådan bruger du appen

Appen viser dagens events i København, hvor der er flest taxa-kunder, og hvor du skal stille dig.
Den henter selv alle data fra internettet — ingen opsætning, ingen Python, ingen nøgler.

## Sådan åbner du appen

**Mulighed 1 — Live-preview (her i chatten):** Åbn preview'et → appen er klar med det samme.

**Mulighed 2 — På din egen telefon/computer:** Download mappen **spot-the-fare** og åbn **`index.html`**
i din browser (Chrome/Safari). På telefonen: vælg "Tilføj til hjemmeskærm", så ligger den som en app.

> Tip: Appen skal bruge internet til at hente data (og kortet). Er du helt offline,
> viser den de sidst gemte data — og i værste fald eksempel-data med en besked.

## Hvad du ser

**I dag** (fane 1)
- Dagens events sorteret **tidligst først** (overståede events står nederst med OVRE-mærke)
- **Uge-linje øverst** — se hele ugen på én gang (tal = dagens bedste score). Tryk på en dag for at se den
- Skift sortering med sidste chip i rækken: **🕐 Tid** (standard) eller **🔥 Score** (0–100 = forventet efterspørgsel)
- **＋-knap (nederst til højre)** — tilføj dit eget event (fx privatfest) — det får mærket "DIN" og kan slettes igen
- Tryk på et event → detaljer: demand-kurve, pickup-steder (med "estimat"-mærke), kontekst og feedback-knap

**Kort** (fane 2)
- Rigtigt kort med **zoom** (træk, +/- eller scroll)
- **Pulserende markører** for dagens events (rød = høj score), **grå prik** = venue uden event i dag
- To lag du kan slå til/fra: **🚇 Metro-stationer** og **🚕 Taxi-stande**
- Tryk på en markør → detaljer

**Plan** (fane 3)
- En foreslået kørerute bygget omkring **let-out-tidspunkterne** (hvornår folk strømmer ud)
- Hvert stop viser: hvornår du skal være der, hvor (bedste pickup-spot), forventet indtjening og **"Forlad senest"** — hvornår du skal køre videre for at nå næste stop
- **✓ på et stop** = "færdig her" — planen lægger sig om
- **📍 Min position** — appen finder din position og viser afstand/tid til første stop
- Samlet forventet indtjening for dagen nederst

**🔔 Klokke-ikon** — advarsler (fx "slutter om X min" eller "regn i aften = +15 %")
**↻ Opdater-knap** — henter alt data på ny (app'en opdaterer også selv automatisk)
**☀️/🌙-knap** — skift mellem lys og mørk tilstand (lys er standard — bedst i dagslys)

## Sådan forstår du tallene

- **Score 85+** = meget travlt · **65–84** = godt · **under 50** = måske
- **Let-out-vindue** = hvornår folk strømmer ud — stil dig der 10–15 min før
- **Status:** `LIVE NU` (sker lige nu) · `I GANG` · `SNART` (inden for 2 t) · `SENERE` · `OVRE`

## Kilder (alt gratis)

Koncerter (10 spillesteder) · FCK-kampe i Parken · Københavns Kommunes eventkalender ·
krydstogtanløb · **lufthavnsankomster (CPH)** · vejrprognose · **konferencer og messer**
(Bella Center: TechBBQ, CIRSE, IBA, Bogforum, Digital Tech Summit…; hoteller: Tivoli Hotel,
Radisson Blu, Crowne Plaza, Comwell Portside, Falkoner, Odd Fellow — vælg dem i ＋-formularen) ·
**årets store begivenheder** (DHL Stafetten, Copenhagen Cooking, J-dag, Jul i Tivoli,
Nytårsaften) · plus indbyggede mønstre (Tivoli-fyrværkeri, Kødbyen-weekender, Fredagsrock).

> ✈️ **Lufthavnen:** ankomstbølger (mange fly der lander på samme tid) vises som events med
> score — jo flere fly, jo højere score. Taxirækken er ved Terminal 3. Lufthavnsdata hentes
> live når forbindelsen tillader det; ellers vises de indbyggede data for i dag.

---

*God jagt — og kør forsigtigt! 🚕*
