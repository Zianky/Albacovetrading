# Alba Cove Trading – sito web

Sito aziendale di **Alba Cove Trading FZCO** (Dubai): una pagina statica in HTML/CSS/JS, senza build e senza dipendenze da installare.

## Contenuto del progetto

| File | Funzione |
| --- | --- |
| `index.html` | Il sito completo: Company, Trading, Products, Investments, Solutions, Network, Contact |
| `assets/logo-mark.png` | Simbolo (cerchio con la A), verde, sfondo trasparente |
| `assets/logo-full-teal.png` | Logo completo, verde, sfondo trasparente |
| `assets/logo-full-white.png` | Logo completo, bianco, per sfondi scuri (footer) |
| `.nojekyll` | Disattiva Jekyll: il sito viene servito così com'è |

## Sito online (GitHub Pages)

Indirizzo di prova: https://zianky.github.io/Albacovetrading/

In **Settings → Pages**: sorgente "Deploy from a branch", ramo `main`, cartella `/ (root)`.

## Foto

Le foto sono ancora collegate dall'indirizzo del vecchio sito (`framerusercontent.com`). Per renderle definitive, salvale in `assets/photos/` e sostituisci gli indirizzi nelle etichette `<img>` di `index.html`. Se il vecchio sito viene disattivato, le foto collegate smettono di caricarsi.

## Collegare il dominio www.albacovetrading.com

1. Aggiungi nella radice del repository un file `CNAME` che contenga una sola riga: `www.albacovetrading.com`.
2. Nel DNS del dominio crea un record **CNAME** `www` che punta a `zianky.github.io`.
3. In **Settings → Pages** inserisci il dominio in "Custom domain" e attiva **Enforce HTTPS** quando il certificato è pronto.

Finché il DNS punta al vecchio sito, il dominio continua a mostrare quello.

## Modifiche

Testi, colori e font sono in `index.html`; colori e font sono definiti all'inizio del file, nel blocco `:root`.
Prima di pubblicare in modo definitivo, controlla il numero di telefono nella sezione Contact (copiato dal sito precedente) e la misura del filo di nichel in Products.
