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

Le foto sono salvate in `assets/photos/` (JPEG già ritagliati e compressi) e il sito non dipende più da servizi esterni. Provengono da Unsplash, che consente l'uso commerciale senza obbligo di citare l'autore.

| File | Sezione | Autore |
| --- | --- | --- |
| `hero-port-dusk.jpg` | Hero, porto al crepuscolo | Maik Winnecke |
| `company-business-bay.jpg` | Company | Mohamed Reshad |
| `metals-laboratory.jpg` | Trading, Metals | Trnava University |
| `energy-refinery.jpg` | Trading, Energy | Maksym Kaharlytskyi |
| `agriculture-wheat.jpg` | Trading, Agriculture | Edson Rosas |
| `products-silicon-wafer.jpg` | Products | Laura Ockel |
| `investments-dubai-skyline.jpg` | Investments | Ahmed Galal |
| `solutions-burj-khalifa.jpg` | Solutions | Wael Hneini |
| `network-desert-dunes.jpg` | Network | Faris Mohammed |
| `contact-dubai-creek.jpg` | Contact | Hatem Ramadan |

Per cambiare una foto, sostituisci il file mantenendo lo stesso nome e le stesse proporzioni (hero e Products 21:8, Contact 3:1, Company, Investments, Solutions e Network 4:3, Trading 3:2).

## Collegare il dominio www.albacovetrading.com

1. Aggiungi nella radice del repository un file `CNAME` che contenga una sola riga: `www.albacovetrading.com`.
2. Nel DNS del dominio crea un record **CNAME** `www` che punta a `zianky.github.io`.
3. In **Settings → Pages** inserisci il dominio in "Custom domain" e attiva **Enforce HTTPS** quando il certificato è pronto.

Finché il DNS punta al vecchio sito, il dominio continua a mostrare quello.

## Modifiche

Testi, colori e font sono in `index.html`; colori e font sono definiti all'inizio del file, nel blocco `:root`.
Prima di pubblicare in modo definitivo, aggiungi in Products la misura del filo di nichel (riga rimossa in attesa di conferma).
