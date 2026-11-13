# Squarciagola by Sonar

Karaoke collettivo del **Sonar Lounge and Show Club**: dashboard sul PC e schermo con il testo per proiettore e TV.

L'app è un solo file (`index.html`): non c'è niente da installare né da configurare.

## Importante
- **Qui su GitHub non vanno caricati brani né testi.** Basi audio e testi restano nel browser del PC del locale e non escono mai da lì.
- Brani e testi si salvano nel browser **per indirizzo**: la libreria creata aprendo l'app da `https://...github.io/...` è diversa da quella creata aprendo il file dal disco.
- Fai ogni tanto il backup dalla scheda *Serata* (Backup della libreria).

## Pubblicazione
1. Su GitHub: **New repository** → nome `squarciagola` → **Public** → *Create repository*.
2. **Add file → Upload files** e trascina tutti i file di questa cartella (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `README.md`) → **Commit changes**.
3. **Settings → Pages** → *Build and deployment* → Source: **Deploy from a branch** → Branch: **main**, cartella **/ (root)** → **Save**.
4. Dopo uno o due minuti l'indirizzo è `https://TUOUTENTE.github.io/squarciagola/`.

## Uso nel locale
- Apri l'indirizzo con **Chrome o Edge** sul PC del locale.
- Per installarlo come app: icona di installazione nella barra dell'indirizzo, oppure menu → *Installa Squarciagola*.
- Dopo la prima apertura funziona anche senza internet.
- Premi **Apri schermo testo**, trascina la finestra sul proiettore e tocca per lo schermo intero.

## Aggiornare l'app
Carica il nuovo `index.html` sullo stesso repository (**Add file → Upload files**, stesso nome, *Commit*). Dopo un minuto ricarica la pagina due volte.
