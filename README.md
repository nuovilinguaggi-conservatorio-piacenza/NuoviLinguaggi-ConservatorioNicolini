# Composizione e Nuovi Linguaggi — Conservatorio "G. Nicolini" di Piacenza

Repository del Dipartimento di Composizione e Nuovi Linguaggi del Conservatorio di Musica "Giuseppe Nicolini" di Piacenza.

## Finalità

Il repository GitHub del dipartimento è destinato alla condivisione e allo sviluppo collaborativo di **codice, patch, progetti computazionali e relativa documentazione tecnica**.

I materiali didattici di altra natura, quali presentazioni, dispense e contenuti audiovisivi, sono distribuiti attraverso **Discord** o altre piattaforme istituzionali, fatta eccezione per le risorse direttamente necessarie al funzionamento dei progetti pubblicati (ad esempio campioni audio, impulse response, immagini o file di dati richiamati dal codice).

## Struttura

```
.
├── 1-triennio/                  Corsi del Diploma accademico di primo livello
│   ├── campionamento-sintesi/
│   ├── informatica-musicale/
│   ├── multimedia/
│   └── sistemi-linguaggi/
├── 2-biennio/                   Corsi del Diploma accademico di secondo livello
│   ├── ambienti-esecutivi/
│   ├── sistemi-internet/
│   └── sistemi-linguaggi/
└── 3-workshop/                  Seminari, masterclass e workshop
```

Le cartelle dei corsi attualmente presenti sono quelle dei corsi del Prof. A. Anatrini. Ogni docente che desideri contribuire crea la cartella del proprio corso all'interno di `1-triennio/`, `2-biennio/` o `3-workshop/`, seguendo le convenzioni sui nomi indicate più sotto e corredandola di un `README.md` con la descrizione del corso, il nome del docente e l'indice dei progetti presenti. Se un corso con lo stesso nome è già presente, aggiungere al nome della cartella il cognome del docente (es. `sistemi-linguaggi-rossi/`).

## Regole per i contributi (docenti)

### Cosa pubblicare

- Codice sorgente, patch (Max/MSP, Pure Data, SuperCollider, ecc.), script e progetti computazionali.
- Workspace e patch di OpenMusic.
- File di progetto delle DAW (Reaper, Ableton Live, Logic Pro, ecc.), quando costituiscono parte integrante di un progetto o ne documentano la realizzazione. In questo caso è opportuno indicare nel `README.md` la versione del software e gli eventuali plugin necessari, e includere solo i file audio effettivamente utilizzati dal progetto.
- Documentazione tecnica: istruzioni di installazione e d'uso, dipendenze, note di implementazione.
- Risorse indispensabili al funzionamento dei progetti (audio, immagini, dati), purché di dimensioni contenute.

### Cosa non pubblicare

- Presentazioni, dispense, registrazioni delle lezioni e altri materiali didattici non legati al codice: vanno su Discord o sulle piattaforme istituzionali.
- Materiale protetto da diritto d'autore di cui non si detengono i diritti di distribuzione.
- Dati personali degli studenti (nomi completi, valutazioni, contatti) senza il loro consenso.
- Credenziali, chiavi API, password o file di configurazione contenenti dati sensibili.

### Organizzazione dei progetti

- Ogni progetto va inserito nella cartella del corso di riferimento, in una propria sottocartella.
- Nomi di file e cartelle: minuscolo, parole separate da trattino (`-`), senza spazi, accenti o caratteri speciali (es. `sintesi-granulare-max/`).
- Ogni progetto deve avere un proprio `README.md` che indichi almeno:
  - titolo e breve descrizione;
  - autore/i e anno accademico;
  - software e versioni necessari (es. Max 9, SuperCollider 3.13, Python 3.12);
  - istruzioni per l'avvio e l'uso.
- Dopo aver aggiunto un progetto, aggiornare l'indice nel `README.md` della cartella del corso.

### File di grandi dimensioni

- GitHub rifiuta file superiori a 100 MB e sconsiglia file oltre i 50 MB.
- Per risorse pesanti (audio lunghi, video, dataset) preferire formati compressi, oppure ospitarle esternamente e inserire il link nel `README.md` del progetto.

### Flusso di lavoro

1. Creare un branch dedicato a partire da `main` (es. `triennio/informatica-musicale/esercizi-fft`).
2. Effettuare commit piccoli e con messaggi descrittivi, in italiano o in inglese (es. `Aggiunge patch di esempio per la sintesi FM`).
3. Aprire una **Pull Request** verso `main` descrivendo brevemente il contenuto.
4. Le modifiche ai materiali di un corso spettano al docente titolare; per interventi su cartelle altrui è buona norma richiederne la revisione.

Chi preferisce non usare Git da riga di comando può caricare e modificare file direttamente dall'interfaccia web di GitHub (*Add file → Upload files*), scegliendo l'opzione *Create a new branch and start a pull request* al momento del commit.

### Segnalazioni e proposte

Per segnalare errori, proporre nuovi progetti o discutere modifiche alla struttura del repository, aprire una **Issue**.

## Licenza

Il contenuto del repository è distribuito con licenza [MIT](LICENSE), salvo diversa indicazione nel `README.md` del singolo progetto.

## Contatti

Responsabile del repository: Prof. A. Anatrini.
