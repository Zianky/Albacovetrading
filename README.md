# Alba Cove Trading – sito web

Sito aziendale di **Alba Cove Trading FZCO** (Dubai): una pagina statica in HTML/CSS/JS, senza build e senza dipendenze da installare. Online su https://www.albacovetrading.com (GitHub Pages, ramo `main`, cartella root).

## Contenuto del repository

| File | Funzione |
| --- | --- |
| `index.html` | Il sito completo: Company, Trading, Products, Investments, Solutions, Network, Contact, informativa privacy e crediti |
| `404.html` | Pagina di errore, con reindirizzamento dei vecchi percorsi alla sezione giusta della home |
| `company/`, `about/`, `trading/`, `products/`, `investments/`, `solutions/`, `network/`, `contact/` | Pagine di rimando dai vecchi indirizzi alla sezione corrispondente della home (`noindex`, canonical alla home) |
| `robots.txt`, `sitemap.xml` | Indicizzazione: aggiornare `lastmod` quando cambiano i contenuti |
| `CNAME` | Dominio personalizzato `www.albacovetrading.com` |
| `.nojekyll` | Disattiva Jekyll: il sito viene servito così com'è |
| `assets/logo-*.png` | Logo: simbolo (verde), logo completo (verde e bianco) |
| `assets/og-image.jpg` | Anteprima per social e messaggistica (1200×630): logo bianco su fotogramma del porto |
| `assets/photos/` | Foto del sito (JPEG già ritagliati e compressi) |
| `assets/video/` | Video dell'hero (MP4 e WebM) |

## Foto e video

Il sito non dipende da servizi esterni. Foto da Unsplash (licenza Unsplash, uso commerciale consentito, citazione non obbligatoria ma riportata nel footer; nessuna immagine Unsplash+). Video e ritagli del video da Pexels.

| File | Sezione | Autore |
| --- | --- | --- |
| `hero-port-dusk-poster.jpg` | Hero (immagine iniziale del video), Trading, Products | willy one (Pexels) |
| `logistics-port.jpg` | Trading, Products (ritaglio del video) | willy one (Pexels) |
| `company-business-bay.jpg` | Company, Trading | Mohamed Reshad |
| `metals-laboratory.jpg` | Trading, Metals and minerals | Trnava University |
| `agriculture-wheat.jpg` | Trading, Agriculture | Edson Rosas |
| `investments-dubai-skyline.jpg` | Investments | Ahmed Galal |
| `solutions-burj-khalifa.jpg` | Trading (schede) | Wael Hneini |
| `network-desert-dunes.jpg` | Network | Faris Mohammed |
| `contact-dubai-creek.jpg` | Contact | Hatem Ramadan |

Per cambiare una foto, sostituisci il file mantenendo lo stesso nome e le stesse proporzioni. Se aggiungi una foto, aggiungi anche l'autore nel blocco «Credits and copyright» di `index.html`.

`assets/video/hero-port-dusk.mp4` è un loop di 12,5 secondi, senza audio, 1920×732, circa 2,4 MB; `hero-port-dusk.webm` è la copia per i browser senza H.264. Parte da solo e in silenzio, e si ferma per chi ha attivato la riduzione del movimento. Per sostituirlo: stessi nomi file, H.264 senza audio, sotto i 3 MB, e rigenera WebM, il poster e `og-image.jpg`.

## Privacy

Il sito non imposta cookie, non ha moduli, analisi o pubblicità e non fa richieste a servizi esterni (font di sistema). I link a Instagram, Facebook e LinkedIn sono normali link esterni. L'informativa è nel blocco `#privacy` di `index.html` e va fatta rivedere da un consulente legale. GitHub Pages può registrare l'indirizzo IP dei visitatori nei suoi log di sicurezza, e l'informativa lo dichiara.

## Dominio e DNS

DNS gestito dal pannello Webador: record CNAME `www` verso `zianky.github.io` e quattro record A su `@` verso 185.199.108.153, 185.199.109.153, 185.199.110.153 e 185.199.111.153. Il dominio personalizzato è impostato in **Settings → Pages**; attiva **Enforce HTTPS** quando il certificato è pronto.

## Modifiche

Testi, colori e dati strutturati sono in `index.html`; i colori sono definiti all'inizio del file, nel blocco `:root`. Dopo ogni modifica pubblicata, aggiorna `lastmod` in `sitemap.xml`. Contatti ufficiali: info@albacovetrading.com, +971 58 550 9345, licenza 62515.
