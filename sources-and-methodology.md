# VC & Consulting – Methodology and Sources

Questo documento descrive in modo sintetico:

1. la logica con cui sono stati costruiti i principali indicatori utilizzati nei paper della repository;
2. le fonti statistiche e i report di riferimento.

Tutti i paper fanno riferimento a questo file per la parte metodologica e bibliografica generale.

---

## 1. Principali indicatori

### 1.1 Macroeconomia

Per ciascun Paese considerato (Stati Uniti, Cina, Giappone, Germania, Regno Unito, Francia, Italia, Spagna, Svizzera) vengono utilizzati:

- **PIL nominale** (current USD) nell’ultimo anno disponibile (prevalentemente 2023–2024).
- **Popolazione totale**.
- **PIL pro capite** = PIL nominale / popolazione.

Questi dati sono usati per costruire:

- **VC/GDP** = (investimenti VC annui) / PIL nominale.
- **VC per capita** = (investimenti VC annui) / popolazione.
- **Consulting/GDP** = (ricavi del settore consulenza) / PIL nominale.

### 1.2 Venture Capital

Per il VC si utilizzano:

- **volumi annui** di investimenti (seed, early, growth, late stage) per Paese;
- **serie storiche** per la Svizzera (2015–2024);
- **quote** di VC europeo per singolo Paese.

Le cifre sono riportate come **ordini di grandezza** o **intervalli** (es. 13–33 miliardi USD per la Cina) per riflettere le differenze metodologiche tra le fonti.

### 1.3 Mercato della consulenza

Per la consulenza vengono considerate:

- stime di **ricavi annuali** per Paese;
- perimetri variabili (solo management consulting vs consulting + IT + outsourcing);
- **numero di imprese** e **addetti** quando disponibile (es. Germania, Spagna, Svizzera).

I rapporti consulenza/PIL sono da intendersi come **approssimazioni** basate su tali stime.

### 1.4 Struttura d’impresa e ricchezza

Per Stati Uniti e Cina si utilizzano statistiche su:

- numero di imprese totali;
- quota di micro-imprese senza dipendenti;
- distribuzione per classi di addetti;
- fatturato medio e mediano nelle piccole imprese.

Per la ricchezza si utilizzano:

- stime del numero di **millionaires (HNWI, net worth ≥ 1 milione USD)**;
- distribuzione geografica dei milionari per Paese/area.

---

## 2. Fonti statistiche e istituzionali

### 2.1 Macroeconomia

- **World Bank – World Development Indicators**  
  PIL nominale, popolazione e PIL pro capite per tutti i Paesi considerati.
- **International Monetary Fund (IMF) – World Economic Outlook Database**  
  Proiezioni e aggiornamenti su PIL e indicatori macro 2023–2024.
- **Uffici statistici nazionali** (es. Destatis per la Germania, INSEE per la Francia, ISTAT per l’Italia, Oficina Nacional de Estadística per la Spagna, Ufficio federale di statistica per la Svizzera)  
  Verifica puntuale di alcuni dati di popolazione e PIL in valuta locale.

### 2.2 Venture Capital – livello globale ed europeo

- **Dealroom / Invest Europe – European Venture Capital reports 2023–2024**  
  Volumi di VC per Paese europeo, totale VC europeo, quota percentuale di ciascun Paese.
- **KPMG – Venture Pulse 2023–2024**  
  Stime dei volumi globali di VC (inclusi gli Stati Uniti, la Cina e altre aree), distribuzione per macro-regione, focus su AI e mega-round.
- **PitchBook / altre piattaforme di dati VC**  
  Dati di controllo e intervalli per alcune nazioni extra-europee.

### 2.3 Venture Capital – Svizzera

- **Swiss Venture Capital Report (varie edizioni 2015–2024)**  
  - Serie storica degli investimenti VC in Svizzera per anno.  
  - Breakdown geografico per cantone (Zurigo, Zug, altri).  
  - Distribuzione settoriale (ICT/software, biotech/medtech, cleantech, ecc.).  
  - Dati su quantità di capitali raccolti da spin-off universitari (ETH, EPFL, ecc.).

### 2.4 Mercati della consulenza

- **Associazioni nazionali di consulenza e IT**  
  - **BDU – Bundesverband Deutscher Unternehmensberater (Germania)**: ricavi del settore, numero di imprese e addetti.  
  - **UK consultancy industry reports** (Management Consultancies Association e studi di settore) per il Regno Unito.  
  - **Rapporti nazionali affiliati FEACO** (Federation of European Consulting Associations) per Francia, Italia, Spagna.  
  - **Studi di mercato su management consulting in Svizzera** (rapporti settoriali e analisi di mercato locali).

- **Report di settore internazionali**  
  - IBISWorld, Mordor Intelligence, ecc., per ordini di grandezza su mercati extra-UE (Stati Uniti, Giappone, Cina).

### 2.5 Struttura d’impresa (PMI, micro-imprese)

- **United States Small Business Administration (SBA)**  
  Statistiche su:
  - numero di small businesses;
  - distinzione fra employer e non-employer firms;
  - fatturato medio delle small businesses.
- **US Census Bureau – Business Dynamics Statistics**  
  Dati su numero medio di addetti per impresa e per nuovo establishment.

- **National Bureau of Statistics of China e studi sulle PMI cinesi**  
  Dati su:
  - numero totale di entità registrate (imprese + household businesses);  
  - distribuzione per classi di addetti (senza dipendenti, 1–4, ecc.);  
  - fatturato medio/mediano per le micro e piccole imprese.

### 2.6 Ricchezza e HNWI

- **UBS / (ex) Credit Suisse – Global Wealth Report 2023–2024**  
  - Numero di adulti con patrimonio netto ≥ 1 milione USD per Paese.  
  - Distribuzione per regione (Nord America, Europa, Asia-Pacifico, Cina, ecc.).  
  - Stime della ricchezza media e mediana per adulto.

---

## 3. Uso dei dati nei paper

Tutti i paper della repository:

- **riassemblano e sintetizzano** i dati provenienti dalle fonti sopra elencate;
- riportano i valori come **intervalli** o **ordini di grandezza** quando le fonti non coincidono perfettamente;
- privilegiano **rapporti e indici** (VC/GDP, VC per capita, consulting/GDP, numero di milionari per milione di abitanti, ecc.) rispetto a valori assoluti isolati.

Per evitare violazioni di copyright:

- non vengono riprodotte tabelle o grafici completi di singoli report;
- i numeri sono rielaborati, combinati e presentati in tabelle originali costruite ad hoc per questa repository.

---

## 4. Copyright e riuso

© 2025 Andrea Trenti. Tutti i diritti riservati.

- I testi analitici, le tabelle e la struttura degli indicatori sono opere originali protette da copyright.
- I dati statistici di base restano di proprietà dei rispettivi enti (World Bank, IMF, associazioni di categoria, ecc.) e sono utilizzati esclusivamente a fini analitici e didattici.
- Non è concessa alcuna licenza open-source o Creative Commons per il riuso integrale dei testi; eventuali utilizzi sostanziali richiedono l’autorizzazione dell’autore.
