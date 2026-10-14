# Alba Cove Trading – sito web

Sito aziendale di **Alba Cove Trading FZCO** (Dubai), pagina unica statica in HTML/CSS/JS, senza build e senza dipendenze da installare.

## Contenuto del progetto

| File | Funzione |
| --- | --- |
| `index.html` | Il sito completo (Company, Trading, Investments, Solutions, Network, Contact) |
| `CNAME` | Dominio personalizzato per GitHub Pages (`www.albacovetrading.com`) |
| `.nojekyll` | Disattiva Jekyll, il sito viene servito così com'è |

## Pubblicazione su GitHub Pages

1. Crea un repository (es. `albacovetrading-website`) e carica questi file nel ramo `main`.
2. Vai in **Settings → Pages**, scegli **Deploy from a branch**, ramo `main`, cartella `/ (root)`.
3. Nel DNS del dominio `albacovetrading.com` imposta:
   - un record **CNAME** `www` che punta a `<tuo-utente-github>.github.io`
   - per il dominio senza `www` (apex), quattro record **A** verso gli IP di GitHub Pages indicati nella documentazione ufficiale (docs.github.com, sezione "Managing a custom domain for your GitHub Pages site")
4. In **Settings → Pages** attiva **Enforce HTTPS** quando il certificato è pronto.

Finché il DNS punta al vecchio sito (Framer), il sito attuale resta online: cambia i record solo quando sei pronto al passaggio.

## Modifiche

Tutti i testi sono in `index.html`. I colori e i font sono definiti all'inizio del file, nel blocco `:root`.
Il numero di telefono nella sezione Contact è copiato dal sito precedente: verificalo prima della pubblicazione.
