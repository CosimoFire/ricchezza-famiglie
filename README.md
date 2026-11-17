# Ricchezza delle famiglie – dataviz Radar QN

Pagine pubblicate su GitHub Pages: https://cosimofire.github.io/ricchezza-famiglie/

| Dataviz | URL | Dati | Fonte |
|---|---|---|---|
| Di cosa è fatta la ricchezza delle famiglie italiane | https://cosimofire.github.io/ricchezza-famiglie/composizione/ | `data/composizione-ricchezza.csv` | Banca d'Italia, Conti distributivi della ricchezza, 1° trimestre 2026 |
| Quote di ricchezza nel tempo: Italia, Francia, Germania e Spagna | https://cosimofire.github.io/ricchezza-famiglie/quote-nel-tempo/ | `data/quote-ricchezza.csv` | Bce, Distributional Wealth Accounts |
| Cento anni di patrimoniali in Italia | https://cosimofire.github.io/ricchezza-famiglie/patrimoniali/ | `data/patrimoniali.csv` | Ricostruzione Radar – QN |
| Il 10% delle famiglie possiede il 60% della ricchezza | https://cosimofire.github.io/ricchezza-famiglie/famiglie-ricchezza/ | `data/famiglie-ricchezza.csv` | Banca d'Italia, Conti distributivi della ricchezza, 1° trimestre 2026 |

## Note sui dati

- `composizione-ricchezza.csv`: valori medi per famiglia in migliaia di euro. "Imprese non quotate" somma ricchezza finanziaria d'impresa (azioni non quotate e partecipazioni) e ricchezza non finanziaria d'impresa; "Azioni e fondi" somma azioni quotate e quote di fondi comuni. Le percentuali sono calcolate sul totale delle attività.
- `quote-ricchezza.csv`: quote della ricchezza netta in %, dati al 4° trimestre di ogni anno e al 1° trimestre 2026. La quota del "40% centrale" è calcolata come 100 meno la quota del 50% più povero e del 10% più ricco.

- `famiglie-ricchezza.csv`: quota delle famiglie e della ricchezza netta per gruppo; soglia di ingresso = 50° percentile (40% centrale) e 90° percentile (10% più ricco) della ricchezza netta familiare; quota del 40% centrale calcolata come differenza.

## Snippet per il CMS

Il codice pronto, con anteprime, è nella pagina indice: https://cosimofire.github.io/ricchezza-famiglie/
Ogni snippet è l'iframe seguito dallo script inline di `assets/embed.min.js` (altezza e tema). Se in un articolo ci sono più dataviz lo script può restare in ognuna: grazie al controllo `__radarQNv2` non si ripete il lavoro.
