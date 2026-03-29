# Fase 4 — Analisi Finanziaria e ROI

## 1. Struttura dei Costi del Progetto

### 1.1 Costi di Acquisizione

| Voce | Importo stimato | Note |
|---|---|---|
| Prezzo di acquisto immobile | **145.000 €** | Prezzo richiesto (Idealista); da negoziare |
| Prezzo al m² | **495 €/m²** | Su 293 m² commerciali |
| Imposta di registro (Prima Casa 2%) | _(da calcolare su valore catastale)_ | Su valore catastale rivalutato; minimo €1.000 |
| Imposte ipotecaria + catastale | €100 | Fisse Prima Casa |
| Onorario notaio | €1.500–€3.000 | Variabile con valore atto |
| Provvigione agenzia immobiliare | 2–3% del prezzo | Se acquisto tramite agenzia (~€2.900–€4.350) |
| Perizia banca (per mutuo) | €200–€400 | — |
| Istruttoria mutuo | €500–€1.500 | — |
| **Totale costi accessori acquisto** | **~€5.800–€9.500 (~4–6% del prezzo)** | — |

### 1.2 Costi di Ristrutturazione (lordi, prima degli incentivi)

| Voce | Importo lordo stimato | Bonus | Importo netto stimato |
|---|---|---|---|
| Cappotto termico | _(da preventivo)_ | Superbonus 65% | _(da calcolare)_ |
| Impianto riscaldamento (pompa di calore) | _(da preventivo)_ | Superbonus 65% | _(da calcolare)_ |
| Infissi e serramenti | _(da preventivo)_ | Superbonus trainato 65% | _(da calcolare)_ |
| Impianto fotovoltaico + accumulo | _(da preventivo)_ | Superbonus trainato 65% | _(da calcolare)_ |
| Rifacimento bagni e cucine | _(da preventivo)_ | Bonus Ristrutt. 50% | _(da calcolare)_ |
| Impianti elettrici e idraulici | _(da preventivo)_ | Bonus Ristrutt. 50% | _(da calcolare)_ |
| Pavimenti e finiture | _(da preventivo)_ | Bonus Ristrutt. 50% | _(da calcolare)_ |
| Frazionamento (pareti, ingressi) | _(da preventivo)_ | Bonus Ristrutt. 50% | _(da calcolare)_ |
| Spese tecniche (progetto, APE, asseverazioni) | _(da preventivo)_ | Detraibili | _(da calcolare)_ |
| **TOTALE RISTRUTTURAZIONE** | **_(da sommare)_** | — | **_(da sommare)_** |

### 1.3 Costi di Commercializzazione

| Voce | Importo stimato |
|---|---|
| Provvigione agenzia immobiliare (vendita) | 2–3% del prezzo di vendita |
| Spese notarili (vendita) | A carico acquirente (tipicamente) |
| Home staging e foto professionali | €500–€2.000 |
| Marketing digitale | €300–€1.000 |

---

## 2. Struttura dei Ricavi

### 2.1 Ricavi da Vendita

| Unità | Metratura stimata | Prezzo €/m² stimato | Ricavo totale stimato |
|---|---|---|---|
| Unità 1 | _(da definire)_ | _(da ricercare)_ | _(da calcolare)_ |
| Unità 2 | _(da definire)_ | _(da ricercare)_ | _(da calcolare)_ |
| Unità 3 | _(da definire)_ | _(da ricercare)_ | _(da calcolare)_ |
| **TOTALE** | — | — | **_(da sommare)_** |

> Consultare le quotazioni OMI (Osservatorio del Mercato Immobiliare) dell'Agenzia delle Entrate per i valori di mercato aggiornati della zona Quinto / Valpantena di Verona.
> Zona di riferimento OMI: cercare tramite https://www.agenziaentrate.gov.it/portale/web/guest/schede/fabbricatiterreni/omi

### 2.2 Ricavi da Locazione (scenario affitto)

| Unità | Canone mensile stimato | Canone annuo | Rendimento lordo |
|---|---|---|---|
| Unità da tenere in affitto | _(da ricercare)_ | _(da calcolare)_ | _(da calcolare)_ |

---

## 3. Analisi di Redditività

### 3.1 Plusvalenza (scenario vendita)

```
Plusvalenza = Ricavi vendita - (Costo acquisto + Costi ristrutturazione netti + Costi accessori)
```

**Fiscalità sulla plusvalenza:**
- Se l'immobile è stato adibito ad **abitazione principale** per la maggior parte del periodo di possesso → **esente da tassazione**.
- Se venduto entro 5 anni dall'acquisto (senza aver abitato come prima casa) → tassazione al **26%** (imposta sostitutiva) o concorso a tassazione IRPEF.
- Dopo 5 anni → **esente da tassazione** per persone fisiche.
- Novità 2024: le plusvalenze su immobili che hanno beneficiato del Superbonus sono **tassate al 26%** anche dopo 5 anni se i lavori sono stati ultimati nei 5 anni precedenti la cessione (verificare la normativa aggiornata con il commercialista).

### 3.2 Rendimento da Locazione

```
Rendimento lordo = (Canone annuo / Valore immobile) × 100
Rendimento netto = Rendimento lordo - (IMU + gestione + manutenzione + sfitto stimato)
```

Parametri tipici per la zona Verona/hinterland:
- IMU seconda casa: aliquota deliberata dal Comune (tipicamente 1,06%)
- Tasso di sfitto: 5–10% per affitto tradizionale; 15–20% per affitto breve
- Manutenzione ordinaria: ~1% del valore annuo

---

## 4. Modello Finanziario — Template

### Input (da completare con preventivi reali)

```
ACQUISTO
  Prezzo acquisto:                    €145.000
  Costi accessori acquisto (~4%):     €5.800  (stima minima)
  Acconto personale (30%):            €43.500
  Importo mutuo (70%):                €101.500
  Tasso mutuo (fisso):                2,85%
  Durata mutuo:                       30 anni
  Rata mensile mutuo (indicativa):    €420

RISTRUTTURAZIONE
  Costo lordo lavori:                 €________ (da preventivo)
  Detrazioni fiscali totali:          €________ (da calcolare)
  Costo netto lavori:                 €________ (da calcolare)
  Durata lavori:                      ________ mesi

TOTALE INVESTIMENTO NETTO:            €________ (145.000 + 5.800 + costo netto lavori)

MONETIZZAZIONE
  Ricavo da vendita unità 1:          €________
  Ricavo da vendita unità 2:          €________
  Canone annuo unità in affitto:      €________
  Valore finale portafoglio:          €________

OUTPUT
  Plusvalenza lorda:                  €________
  Tasse su plusvalenza:               €________
  Plusvalenza netta:                  €________
  ROI totale:                         ________%
  Rendimento annuo da locazione:      ________%
  Payback period:                     ________ anni
```

---

## 5. Scenari di Analisi

### Scenario Conservativo
- Prezzi di mercato -10% rispetto alle stime
- Costi di ristrutturazione +15% per imprevisti
- Tassi di sfitto 15%
- Nessuna cessione del credito disponibile

### Scenario Base
- Prezzi di mercato allineati alle quotazioni OMI correnti
- Costi nei preventivi ± 5%
- Tassi di sfitto 8%
- Detrazioni fruite direttamente in dichiarazione redditi

### Scenario Ottimistico
- Prezzi di mercato +10% grazie a qualità della ristrutturazione
- Cessione del credito parziale disponibile
- Tassi di sfitto 3–5%
- Affitto breve con rendimento 10%+

---

## 6. Cash Flow del Progetto (Timeline)

```
Anno 0    Acquisto: uscita acconto + costi → [–€]
Anno 0–1  Lavori: uscita rate mutuo + SAL lavori → [–€]
Anno 1–2  Fine lavori + commercializzazione → attesa entrate
Anno 2    Vendita unità 1 → [+€] (rientro investimento)
Anno 2+   Canoni affitto mensili → [+€] (rendita)
Anno 5–7  Eventuale vendita unità in affitto → [+€] (plusvalenza esente)
```

---

## 7. Indicatori Chiave da Monitorare

| KPI | Soglia minima accettabile | Target |
|---|---|---|
| ROI totale progetto | > 15% | > 25% |
| Rendimento netto da affitto | > 3,5% | > 5% |
| Copertura rata mutuo con canoni | > 120% | > 150% |
| Payback period | < 10 anni | < 7 anni |
| Plusvalenza netta su vendita | > 20% del costo netto | > 35% |
