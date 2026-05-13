# Autentica EN — Brief di Handover per Claude Code

Documento di passaggio da chat web a Claude Code (terminale). Apri questo file nella root del repo `eraldoallgood/weareautentica` e chiedi a Claude di leggerlo come primo step.

---

## 🎯 Quick Reference — Decisioni chiave (già confermate da Eraldo)

| Aspetto | Decisione |
| :---- | :---- |
| **Target primario** | Wedding & private events stranieri (UK, US, Nord Europa, AU) |
| **Tono** | Evocativo, lifestyle, leggermente letterario — NON business |
| **Architettura** | Sottocartella `/en/` (non subdominio) |
| **Hero phrase EN** | "Your guests will remember how you made them feel." (eco Maya Angelou) |
| **Sezione wedding** | "Tuscany Weddings" (SEO-friendly) |
| **Variante EN** | Mix neutro, ortografia US (color, organize, favorite) |
| **Villa Huygens 1705** | Paragrafo dedicato \+ foto grandi nella sezione Tuscany Weddings |
| **Riprioritizzazione** | Weddings prima posizione (non Corporate come in IT) |
| **Nomi proprietari** | RistorOrto, Alla Serra, La Pedana, Valle Benedetta — INVARIATI |

---

## 1\. Cosa stiamo facendo

Lanciamo la versione inglese del sito **autentica.vallebenedetta.org** (attualmente solo in italiano), con focus strategico sul **mercato wedding & private events internazionale**.

Il sito italiano è in produzione, deploy via GitHub Pages, repo `eraldoallgood/weareautentica`. L'inglese deve coesistere senza rompere l'italiano e senza danneggiare la SEO esistente.

---

## 2\. Target & posizionamento (la cosa più importante)

**Pubblico primario:** coppie straniere (UK, US, Nord Europa, Australia) che cercano una destination wedding in Toscana, e clienti private events di fascia alta (anniversari, milestone birthdays, family reunions).

**Caratteristiche del target:**

- Cercano "Tuscany wedding venue" su Google in inglese  
- Sono saturi di immagini-cliché (cipressi, vigneti, pietra serena) — vogliono qualcosa di più personale e curato  
- Apprezzano: storytelling raffinato, sostenibilità autentica (non greenwashing), chef pedigree, intimità  
- Decidono in coppia, leggono molto prima di scrivere, fanno multiple comparison  
- Inviano la prima email mesi prima dell'evento

**Tono inglese:**

- Evocativo, lifestyle, leggermente letterario  
- NON business, NON markettaro, NON americano-iperentusiasta  
- Riferimenti stilistici: Cereal Magazine, Toast Magazine, Aman Resorts copy, Cabana Magazine  
- Frasi brevi, ritmo, spazio bianco semantico  
- "Show, don't tell" — concretezza sensoriale invece di aggettivi astratti

---

## 3\. Transcreation, non traduzione

Le frasi-chiave del sito italiano sono poesia. Vanno **ricreate**, non tradotte. Esempi:

### Hero

- IT: "I tuoi ospiti ricorderanno come li hai fatti sentire."  
- EN proposta: "Your guests will remember how you made them feel."  
- **Nota**: è già la frase di Maya Angelou (*"people will never forget how you made them feel"*). In inglese il pubblico la riconoscerà come citazione — possiamo lasciarla così (è onesto, è bella), oppure rilanciare con qualcosa di nostro. Decidere con Eraldo.

### Closing manifesto

- IT: "Qui non si diventa felici. Ci si ricorda di esserlo."  
- EN proposta: "You don't become happy here. You remember you already are."  
- Alternativa più lirica: "Happiness isn't found here. It's remembered."

### Sezione "A 10 minuti dalla città, in un altro mondo"

- EN: "Ten minutes from the city. A world away."  
- (Forma idiomatica inglese — "a world away" è perfetto)

### "Coltiviamo cibo, creatività e consapevolezza"

- EN: "We cultivate food, creativity, and presence."  
- (Nota: "consapevolezza" → "presence" funziona meglio di "awareness" o "mindfulness" per il pubblico wedding; "mindfulness" è da retreat)

### "Un altro mondo esiste già"

- EN: "Another world already exists."  
- (Letterale funziona — è poetico anche in inglese)

### RistorOrto

- **Mantenere il nome italiano** "RistorOrto" come termine proprietario, ma sottotitolare "Farm-to-Table Restaurant" la prima volta che appare. È un brand asset, non si traduce.

### Alla Serra

- **Mantenere il nome italiano**. Sottotitolare "The Farm Bar" o "Garden Bar" la prima volta.

### La Pedana

- **Mantenere "La Pedana"**. Sottotitolare "The Stage" o "The Wooden Stage".

### Glossario locations (decidere caso per caso)

| IT | EN proposta | Note |
| :---- | :---- | :---- |
| Bar Agricolo | Farm Bar | "Agricultural Bar" suona da catasto |
| Sala Riunioni | Meeting Room (corporate) / Conference Hall | Per il pubblico wedding praticamente non rilevante |
| Dentro la Serra | Inside the Greenhouse | Letterale, evocativo |
| Cappella privata | Private chapel | Asset wedding fortissimo, valorizzare |
| Villa Sambuca | Villa Sambuca | Nome proprio, invariato |
| Villa Huygens 1705 | Villa Huygens, 1705 | Invariato, l'anno è asset |
| Valle Benedetta | Valle Benedetta | Nome proprio, MAI tradurre "Blessed Valley" |

---

## 4\. Riprioritizzazione contenuti per il target wedding

Il sito italiano dà uguale spazio a Corporate / Occasioni Speciali / Wellbeing. **Per la versione inglese, riprioritizziamo** (senza rimuovere niente, ma riordinando e ribilanciando):

**Ordine sezioni proposto per /en/:**

1. Hero (con focus visivo wedding-friendly)  
2. "Ten minutes from the city. A world away." (location \+ atmosfera)  
3. **Weddings** (sezione espansa, prima posizione tra i target — non terza come in IT)  
4. Private Celebrations (anniversaries, milestone birthdays)  
5. The Estate / Le Location (con Villa Huygens 1705 valorizzata fortemente — è il vero asset wedding)  
6. Chef Simone Cipriani (pedigree Michelin \= enorme leva per pubblico straniero)  
7. Corporate Retreats (presente, ma in coda)  
8. Wellbeing Experiences (in coda)  
9. Contatti

**Sezione Weddings da espandere con:**

- Capacity dettagliata (ceremony / reception / overnight)  
- Accommodation: 9 rooms in Villa Sambuca \+ partner villas (gli stranieri chiedono SEMPRE dove dormono ospiti)  
- "How to get here" — Pisa airport (20 min), Florence airport (1h30), Rome (3h)  
- Symbolic ceremony vs legal ceremony (gli stranieri sposano spesso simbolicamente in Italia e legalmente nel loro paese — chiarirlo subito risparmia ore di email)  
- Mention chapel (Villa Huygens 1705\)  
- Mention multilingual team

---

## 5\. Architettura tecnica

### Opzione consigliata: sottocartella `/en/`

```
/
├── index.html           (IT, invariato)
├── foto_web/            (condivise)
├── en/
│   └── index.html       (EN, nuova)
└── ...
```

**Perché sottocartella e non subdominio:**

- SEO equity condivisa con il dominio principale  
- Setup più semplice su GitHub Pages  
- Switcher lingua più pulito

### Lavori tecnici da fare

**A. SEO multilingua (hreflang)** Nell'`<head>` di entrambe le pagine:

```html
<!-- in index.html (IT) -->
<link rel="alternate" hreflang="it" href="https://autentica.vallebenedetta.org/" />
<link rel="alternate" hreflang="en" href="https://autentica.vallebenedetta.org/en/" />
<link rel="alternate" hreflang="x-default" href="https://autentica.vallebenedetta.org/" />

<!-- in /en/index.html (EN) -->
<link rel="alternate" hreflang="it" href="https://autentica.vallebenedetta.org/" />
<link rel="alternate" hreflang="en" href="https://autentica.vallebenedetta.org/en/" />
<link rel="alternate" hreflang="x-default" href="https://autentica.vallebenedetta.org/" />
```

**B. Meta tag EN — riscrivere completamente**

- `<title>`: "AUTENTICA · Tuscany Weddings & Private Events · Valle Benedetta, Livorno"  
- `<meta name="description">`: 155 caratteri max. Bozza: "Tuscany wedding venue near Livorno. Intimate destination weddings, private events, and farm-to-table dining at Valle Benedetta organic estate."  
- `<html lang="en">` (importante per Google)  
- Keywords primarie da inserire naturalmente nel copy: "Tuscany wedding venue", "destination wedding Italy", "private events Tuscany", "organic farm venue Italy"

**C. Open Graph EN**

- `og:title`, `og:description`, `og:locale="en_US"` (coerente con ortografia US scelta, e copre più mercati)  
- `og:image` con una delle foto wedding-friendly (es. `matrimoni-celebrazione-bucolica.jpg`)  
- `og:image:alt` in inglese

**D. Switcher lingua**

- Posizionarlo nell'header, top-right, discreto  
- "IT / EN" minimal, senza bandierine (le bandierine sono cringe nel settore lusso)  
- Stato attivo evidenziato

**E. Schema.org / JSON-LD (opzionale ma consigliato)** Aggiungere `EventVenue` \+ `LodgingBusiness` schema sulla pagina EN per Google rich results. Migliora moltissimo l'organic per "Tuscany wedding venue" query.

**F. Form contatti**

- Tradurre tutte le option del dropdown  
- Considerare un campo extra "Where are you traveling from?" (utile per follow-up sales)  
- Reply email può rimanere [autentica@vallebenedetta.org](mailto:autentica@vallebenedetta.org)

**G. Footer**

- Tradurre, ma mantenere link cross-brand (Valle Benedetta, Alla Serra) invariati come URL  
- I siti vallebenedetta.org e allaserra.it sono in IT — segnalare con note "(Italian version)" o lasciare e accettare che chi clicca arriva all'italiano

---

## 6\. Cose che NON cambiano

- Layout, CSS, struttura grid (massima coerenza visiva tra IT/EN)  
- Foto e percorsi `/foto_web/`  
- Link cross-ecosystem (Valle Benedetta, Alla Serra)  
- Indirizzo email contatti  
- Coordinate, indirizzo fisico (Livorno, Tuscany — non "Leghorn", per favore)

---

## 7\. Domini & DNS

**Stato attuale (da memoria precedente):** il dominio `autentica.vallebenedetta.org` punta a GitHub Pages, ma il DNS su Register.it richiedeva ancora setup. **Da verificare nel repo** se c'è un file `CNAME` e che valore contiene.

La pagina `/en/` userà lo stesso dominio — nessun lavoro DNS aggiuntivo necessario.

---

## 8\. Workflow di lavoro consigliato in Claude Code

**Step 1\.** Claude legge `index.html` (italiano), identifica struttura sezioni, e mi conferma che ha capito.

**Step 2\.** Creiamo `/en/index.html` come copia struttura, ma con contenuti in inglese. Lavoriamo sezione per sezione:

1. Head \+ meta \+ hreflang  
2. Header \+ nav \+ lingua switcher  
3. Hero  
4. Sezione "Valle Benedetta"  
5. Per chi è AUTENTICA (riprioritizzata: Weddings primo)  
6. Weddings (espansa)  
7. Private Celebrations  
8. The Estate (locations)  
9. Chef Simone  
10. Wellbeing  
11. Corporate  
12. Contact form  
13. Footer

**Step 3\.** Per ogni sezione, Claude propone EN, Eraldo legge e dà OK / chiede tweaks.

**Step 4\.** Una volta completata `/en/index.html`, aggiungere lo switcher lingua anche su `index.html` IT.

**Step 5\.** Commit \+ push. Verifica live.

**Step 6\.** Submit `/en/` a Google Search Console come property separata (utile per analytics di mercato).

---

## 9\. Decisioni già prese ✅

1. **Frase hero EN**: ✅ "Your guests will remember how you made them feel." — lasciamo l'eco di Maya Angelou. È onesta, è bella, il pubblico anglofono la riconoscerà come riferimento culturale positivo (Maya Angelou è universalmente amata). Non serve attribuzione esplicita — sarebbe pesante.  
     
2. **Naming sezione wedding**: ✅ **"Tuscany Weddings"**.  
     
   - Forte per SEO: è la query con maggior volume di ricerca da parte di coppie straniere  
   - H2: `## Tuscany Weddings`  
   - Anchor: `#tuscany-weddings`  
   - Title page deve includerla: "AUTENTICA · Tuscany Weddings & Private Events · Valle Benedetta, Livorno"  
   - Meta description deve includere "Tuscany wedding venue" come keyword principale

   

3. **Variante inglese**: ✅ **Mix neutro — vocabolario universale, ortografia US**.  
     
   - "color" non "colour", "organize" non "organise", "favorite" non "favourite"  
   - Ma evitare americanismi spinti (no "awesome", no "super cool", no "let's chat")  
   - Lessico universale che funziona per UK \+ US \+ AU \+ EU  
   - Date in formato lungo: "May 13, 2026" (US-friendly e universalmente leggibile)

   

4. **Villa Huygens 1705**: ✅ **Paragrafo dedicato \+ foto più grandi**.  
     
   - Posizionamento prominente nella sezione Tuscany Weddings (non solo in "The Estate")  
   - Almeno 2 foto grandi se disponibili (verificare in `/foto_web/`)  
   - Storytelling: 1705, private chapel, historic estate, restoration in progress, early access for 2027+ weddings  
   - CTA dedicato: "Request early access for 2027" o simile  
   - Per il pubblico anglosassone "1705" è esotico in modo positivo (loro hanno raramente date così antiche associate a wedding venues fuori UK)

   

5. **Testimonial Lorenzo e Caterina**: tradurre per ora la quote esistente. In parallelo, Eraldo farà un piano per raccogliere testimonial in inglese nei prossimi mesi.  
     
   - Traduzione EN della quote: "There's a moment at Valle Benedetta when you stop thinking about the schedule. You just stay. And you see everyone happy."  
   - Firma: "— Lorenzo and Caterina"

---

## 10\. Output finale atteso

- `/en/index.html` completo e production-ready  
- `index.html` IT aggiornato con hreflang e lingua switcher  
- Eventuale `CNAME` confermato  
- Commit pulito, messaggio descrittivo: `feat: add English version for international wedding & private events market`  
- Push su GitHub Pages  
- Test live di entrambe le versioni  
- Submit a Google Search Console (Eraldo lo fa, Claude prepara istruzioni)

---

**Quando apri Claude Code:**

"Leggi `AUTENTICA_EN_HANDOVER.md` nella root del repo. Poi facciamo Step 1 del workflow."

Buon lavoro 🌿  
