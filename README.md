# Meteo App Premium (PWA)

Questa è un'applicazione meteo moderna e reattiva progettata con un'interfaccia "Premium" in stile applicazione nativa, che supporta temi chiari e scuri e dispone di funzionalità per l'uso offline. Essendo una Progressive Web App (PWA), puoi installarla direttamente sul tuo dispositivo mobile eludendo i normali store di applicazioni (Google Play Store e Apple App Store).

Questa guida illustra i passaggi completi per ospitare l'applicazione gratuitamente su Internet (requisito per una PWA) e installarla sui tuoi dispositivi.

## 1. Ospitare l'Applicazione Online

Per poter funzionare correttamente ed essere installabile come PWA, la tua applicazione deve essere servita attraverso un protocollo sicuro (HTTPS). Fortunatamente, esistono vari servizi gratuiti che ti consentono di mettere online il tuo codice in pochi minuti.

Ecco come caricare i tuoi file (inclusi `index.html`, `manifest.json` e `sw.js`) usando uno dei seguenti metodi:

### Opzione A: GitHub Pages (Consigliato se hai un account GitHub)
1. Accedi a [GitHub](https://github.com/) e crea un nuovo repository pubblico (es. `meteo-app`).
2. Carica i file `index.html`, `manifest.json` e `sw.js` nella radice del repository.
3. Vai alle "Impostazioni" (Settings) del tuo repository.
4. Scorri in basso a sinistra e clicca su "Pages".
5. Alla voce "Source", seleziona il branch principale (es. `main` o `master`) e clicca su "Save".
6. Entro qualche minuto, la tua app sarà online su `https://tuo-username.github.io/meteo-app/`.

### Opzione B: Vercel (Molto semplice e veloce)
1. Vai su [Vercel](https://vercel.com/) e crea un account.
2. Scarica la Vercel CLI o utilizza l'interfaccia web per fare il deploy della tua cartella.
3. Se usi il web, trascina l'intera cartella contenente i tuoi tre file nel pannello "Drag and drop".
4. Vercel assegnerà automaticamente un URL sicuro (HTTPS) alla tua applicazione.

### Opzione C: Netlify
1. Vai su [Netlify Drop](https://app.netlify.com/drop).
2. Trascina la cartella contenente i tuoi tre file nell'area di trascinamento.
3. Attendi il caricamento e la tua app sarà subito disponibile con un dominio temporaneo sicuro (HTTPS), che potrai rinominare a piacimento.

---

## 2. Installazione su Android

Una volta che hai pubblicato l'app su un sito sicuro (HTTPS), segui questi passaggi per installarla su uno smartphone Android:

1. **Apri Chrome:** Apri il browser Google Chrome sul tuo dispositivo Android.
2. **Visita l'URL:** Inserisci l'indirizzo web dell'app che hai generato tramite GitHub Pages, Vercel o Netlify.
3. **Banner di installazione:** In molti casi, Chrome rileverà automaticamente la PWA e ti mostrerà un pop-up o un banner in basso con scritto "Aggiungi Meteo App alla schermata Home". Se lo vedi, toccalo.
4. **Installazione manuale:** Se non vedi il banner, tocca l'icona con i **tre puntini verticali** in alto a destra per aprire il menu del browser.
5. Scorri le opzioni e seleziona **"Aggiungi a schermata Home"** (o "Installa app", a seconda della versione di Chrome).
6. Conferma toccando "Aggiungi". L'icona dell'app apparirà ora sul launcher o sulla schermata iniziale del tuo telefono. Aprendola, l'app si avvierà a tutto schermo senza la barra di ricerca del browser.

---

## 3. Installazione su iOS (iPhone/iPad)

Su dispositivi iOS, l'installazione delle PWA avviene tramite il browser Safari. Non usare Chrome, poiché su iOS solo Safari supporta l'installazione completa delle PWA.

1. **Apri Safari:** Apri il browser Safari sul tuo iPhone o iPad.
2. **Visita l'URL:** Digita l'indirizzo web dell'app (generato con GitHub Pages, Vercel, ecc.).
3. **Apri il menu di condivisione:** Tocca l'icona di **condivisione** nella barra inferiore dello schermo (è un quadrato con una freccia che punta verso l'alto).
4. **Aggiungi alla schermata Home:** Scorri verso il basso l'elenco delle opzioni disponibili e seleziona **"Aggiungi alla schermata Home"** (l'icona è un quadrato con un segno più al centro).
5. **Conferma:** Apparirà una schermata in cui potrai confermare o modificare il nome dell'app. Tocca **"Aggiungi"** in alto a destra.
6. Torna alla tua schermata iniziale (Home): ora vedrai l'icona dell'app. Aprendola, sembrerà in tutto e per tutto un'applicazione nativa senza l'interfaccia del browser.
