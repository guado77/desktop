# Cross-Asset Wrap — 23/10/2026 (chiusura USA, dati Yahoo v8 al 23/10)

> Generato 23/10/2026 ~23:30 CEST (scarico Yahoo 23:20 CEST, dopo la chiusura USA). Fonti: Yahoo Finance chart v8 (live, 36/36 ticker al 23/10), CFTC Socrata TFF `gpe5-46if` e Disaggregated `72hh-3qpy` (report al **20/10**, pubblicato 23/10 21:30 CEST), flussi ufficiali da `data/flows_last_official.json` (BofA Flow Show 22/10 su EPFR, settimana al 21/10; LSEG Lipper via Reuters 23/10, settimana al 21/10). Nessun numero inventato: dove manca, è scritto.

## Regime in una riga
**Digestione, non capitolazione — ma il testimone passa dai tech ai finanziari**: NDX piatto (-0.00%) dopo il -2,90% di ieri, SPX -0.52%, però XLF -1.32% e IXG -0.89% a 128.68; azioni e bond giù insieme (TLT -0.49%, 10y 4.988%) → la duration non copre. VIX 19.45 con VIX9D 18.70 sotto (punta in contango), MOVE 103.3 (-3.30%) < 125, IXG > 125: checklist **non** in allarme, ma il margine IXG si accorcia a +3.68.

## Liquidità per asset class
Prezzo | 1g | 5g | volume vs media 20g (proxy liquidità/flussi)

| Asset | Ticker | Ultimo | 1g | 5g | Vol/Media20 |
|---|---|---|---|---|---|
| S&P 500 | ^GSPC | 7,623.68 | -0.52% | -0.47% | 0.53x |
| Nasdaq 100 | ^NDX | 28,957.53 | -0.00% | -0.79% | 0.13x |
| Russell 2000 | ^RUT | 2,775.90 | -0.29% | +2.00% | n.d. |
| Euro Stoxx 50 | ^STOXX50E | 6,068.22 | -0.31% | -2.19% | n.d. |
| DAX | ^GDAXI | 25,181.65 | -0.75% | -1.72% | n.d. |
| VIX | ^VIX | 19.45 | +2.21% | -2.70% | n.d. |
| VIX9D | ^VIX9D | 18.70 | -0.85% | -7.06% | n.d. |
| VVIX | ^VVIX | 109.70 | +1.63% | -0.19% | n.d. |
| SKEW | ^SKEW | 151.80 | -0.39% | -9.96% | n.d. |
| MOVE | ^MOVE | 103.31 | -3.30% | +2.19% | n.d. |
| UST 5y % | ^FVX | 4.805 | +0.78% | -1.92% | n.d. |
| UST 10y % | ^TNX | 4.988 | +0.71% | -2.16% | n.d. |
| UST 30y % | ^TYX | 5.315 | +0.53% | -2.23% | n.d. |
| DXY | DX-Y.NYB | 101.75 | +0.14% | -0.09% | n.d. |
| EURUSD | EURUSD=X | 1.120 | -0.15% | -0.19% | n.d. |
| WTI | CL=F | 103.44 | +3.99% | +2.00% | 1.10x |
| Brent | BZ=F | 111.66 | -1.33% | +1.64% | 1.04x |
| Heating oil | HO=F | 4.804 | -2.60% | -1.94% | 0.92x |
| Oro | GC=F | 4,010.00 | -1.24% | -4.09% | 1.17x |
| Rame | HG=F | 6.497 | +2.12% | -0.51% | 28.98x |
| Soia | ZS=F | 1,269.50 | +1.32% | +0.65% | 0.72x |
| TLT | TLT | 81.34 | -0.49% | +1.61% | 0.69x |
| IEF | IEF | 91.05 | -0.16% | +0.70% | 2.81x |
| LQD | LQD | 103.85 | -0.41% | +0.44% | 0.82x |
| HYG | HYG | 77.05 | -0.06% | +0.25% | 0.88x |
| EMB | EMB | 91.65 | -0.22% | +0.14% | 0.45x |
| BKLN | BKLN | 20.26 | -0.15% | -0.88% | 1.00x |
| SPY | SPY | 759.97 | -0.52% | -0.43% | 0.81x |
| QQQ | QQQ | 704.40 | -0.01% | -0.76% | 0.81x |
| IWM | IWM | 275.75 | -0.33% | +1.96% | 0.80x |
| RSP | RSP | 216.54 | -0.77% | +1.14% | 0.73x |
| XLK | XLK | 183.23 | +0.49% | -0.13% | 0.85x |
| XLF | XLF | 55.90 | -1.32% | +0.68% | 0.78x |
| IXG | IXG | 128.68 | -0.89% | -0.27% | 0.26x |
| EZU | EZU | 64.63 | -0.63% | -1.81% | 0.86x |
| EFA | EFA | 102.63 | -0.50% | -0.89% | 0.65x |

Nota: volumi di indici, vol, tassi e FX n.d. su Yahoo; HG=F media 20g anomala (28.98x, cambio contratto), da non leggere. **WTI: probabile roll del contratto front-month** (CL=F +3.99% contro Brent -1.33% e heating oil -2.60%): la variazione giornaliera del WTI è sporcata dal cambio di scadenza, non leggerla come shock petrolifero. Profondità di book (ES, UST, Bund): **nessuna fonte pubblica**.

Lettura: volumi sotto media quasi ovunque (SPY 0.81x, QQQ 0.81x, HYG 0.88x) → venerdì di assorbimento, nessuna vendita forzata; unica eccezione IEF 2.81x su -0.16% → riposizionamento sulla parte intermedia della curva. BKLN 1.00x su -0.15%: i loan restano il punto debole del credito.

## Flussi US vs EU
**Ufficiale — stampe nuove, settimana al 21/10** (BofA Flow Show 22/10 su EPFR, da PDF di Andrea; LSEG Lipper, Reuters 23/10):

| mld $ | BofA/EPFR | LSEG Lipper |
|---|---|---|
| Azionario globale | +55.6 | +28.16 (prec. +19.88) |
| Azionario USA | +6.7 | +5.07 |
| Azionario Europa | -1.0 | +9.14 |
| Asia / EM | EM +33.5 (Cina +17.0, Giappone +6.0, Corea +5.8) | Asia +11.53; EM +6.28 |
| Tech | +18.8 | +5.05 |
| Obbligazionario | +12.1 | +9.44 |
| High yield | -0.5 | -1.68 |
| Monetari | +28.8 | +15.86 |
| Oro | +2.6 | +1.29 (preziosi) |

BofA Bull & Bear 7.2 (da 7.4). Record BofA: Consumi -2,1 mld: deflusso maggiore da feb 2014 (2° di sempre); Utilities -1,6 mld: maggiore da mar 2015 (2° di sempre); Tech +18,8 mld: maggiore da lug 2026; Cina +17,0 mld: maggiore da lug 2026. Lipper: Asia massimo almeno da dic 2022; 5ª settimana di afflussi per azionario e bond globali.

**USA vs Europa: le due fonti non concordano sull'Europa** — EPFR -1.0 contro Lipper +9.14 (universi e domicili diversi, non sommabili); entrambe dicono che il denaro nuovo va in Asia/EM e tech, non negli USA large cap (EPFR USA +6.7, Lipper +5.07). Obbligazionario USA/EU separato: non pubblicato.

**Proxy ETF (23/10, solo volumi/prezzo, NON creazioni/rimborsi):** US — SPY 0.81x, QQQ 0.81x, IWM 0.80x, RSP 0.73x; EU — EZU 0.86x (-0.63%), EFA 0.65x. Nessun segnale di uscita forzata su nessuna delle due sponde.

## COT dealer / AM / lev (TFF, futures only, al 20/10, Δ vs 13/10)
| Contratto | Dealer L/S → netto | Asset Mgr L/S → netto | Lev Money L/S → netto |
|---|---|---|---|
| ES | 184,740/821,671 → **-636,931** (Δ -34,573) | 1,101,642/200,265 → **+901,377** (Δ -14,458) | 135,034/506,279 → **-371,245** (Δ +37,481) |
| TY | 119,383/801,611 → **-682,228** (Δ -49,415) | 3,675,600/750,184 → **+2,925,416** (Δ +26,854) | 567,553/2,674,777 → **-2,107,224** (Δ +98,713) |
| US | 36,715/219,421 → **-182,706** (Δ -3,407) | 1,087,469/699,462 → **+388,007** (Δ -3,527) | 169,144/331,901 → **-162,757** (Δ -8,737) |
| EUR | 57,445/213,163 → **-155,718** (Δ +9,045) | 499,827/309,406 → **+190,421** (Δ -9,497) | 124,951/193,791 → **-68,840** (Δ -839) |

**Disaggregated (al 20/10):**
| Contratto | Managed Money netto | Producer/Merchant netto | Swap dealer netto |
|---|---|---|---|
| CL | **+36,187** (Δ -4,387) | **+359,568** (Δ +6,425) | **-475,726** (Δ +2,752) |
| GC | **+104,206** (Δ -2,883) | **-14,783** (Δ +3,654) | **-220,799** (Δ +3,295) |
| HG | **+47,690** (Δ -13,368) | **-77,406** (Δ +13,060) | **+13,110** (Δ -719) |

Lettura: su ES i leveraged ricoprono (+37,481) mentre gli asset manager alleggeriscono (-14,458) → il calo del rischio è arrivato dal real money, non dai fondi in leva. Su TY il corto lev si riduce di 98,713 contratti con AM ancora in aumento (+26,854): basis trade ancora enorme (~2.11 mln contratti corti) ma in parziale chiusura, coerente con i rendimenti scesi sotto il 5%. Rame: managed money -13,368 in settimana.

## Canale vol → VaR → gamma → hedging
- VIX 19.45 (+2.21%), VIX9D 18.70 (-0.85%): punta di nuovo sotto il VIX a 1m → la domanda di copertura immediata rientra.
- VVIX 109.70 (+1.63%) resta sopra 100: la convessità sulla vol è ancora cara. SKEW 151.80 (-9.96% a 5g; dato CBOE, vedi lacune).
- MOVE 103.3 (-3.30%): vol dei tassi in calo, lontana da 125.
- **Correlazione azioni/bond tornata positiva** (SPX -0.52%, TLT -0.49%): oggi la duration non copre → VaR dei bilanciati e dei risk-parity in salita marginale; è il canale da sorvegliare se il 10y (4.988%) torna sopra 5%.
- Gamma dealer / CTA / vol-control: **nessuna fonte pubblica verificabile** → non stimati.

## Checklist MOVE 125 / IXG 125
| Soglia | Livello | Stato |
|---|---|---|
| MOVE ≥ 125 (stress funding/tassi) | 103.312 | 🟢 sotto soglia (distanza +21.7) |
| IXG ≤ 125 (finanziari globali rotti) | 128.68 | 🟢 sopra soglia (margine +3.68, +2.9%) — in calo da 129,83 |
| Combinato | — | nessun allarme sistemico; Hartnett: "IXG >$125 dice che il macro è a posto" |

## Fonti non rispondenti / lacune
- Yahoo v8: 36/36 ticker hanno risposto, tutti con data 23/10. Volumi n.d. su indici, vol, tassi, FX.
- **SKEW**: indicato come dato a rischio di ritardo (CBOE pubblica lo SKEW in differita); Yahoo dà 151.80 al 23/10 (152,39 il 22/10), da ricontrollare.
- **UST 2 anni mancante**: non c'è nella lista Yahoo (solo 5y/10y/30y) → niente spread 2s10s.
- **WTI CL=F**: probabile roll di scadenza, variazione 1g non confrontabile.
- CFTC Socrata: OK, report al 20/10.
- EPFR diretto: a pagamento; usati Flow Show (PDF) e Lipper (Reuters). Lipper Europa vs EPFR Europa in contrasto, vedi sopra.
- Profondità di book, gamma dealer, posizionamento CTA/vol-control/risk parity: nessuna fonte pubblica.
