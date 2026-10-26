# Dipartimento di Composizione e Nuovi Linguaggi

**Conservatorio di Musica "Giuseppe Nicolini" di Piacenza**

## Finalità

Il presente repository è destinato alla condivisione e allo sviluppo collaborativo di codice, patch, progetti computazionali e relativa documentazione tecnica prodotti nell'ambito delle attività didattiche e di ricerca del Dipartimento.

I materiali didattici di altra natura, quali presentazioni, dispense e contenuti audiovisivi, sono distribuiti attraverso Discord o altre piattaforme istituzionali, fatta eccezione per le risorse direttamente necessarie al funzionamento dei progetti pubblicati.

## Linee guida per i contributi

Le presenti linee guida sono rivolte ai docenti del Dipartimento che partecipano al repository.

### Contenuti ammessi

- Codice sorgente, script e progetti computazionali.
- Patch per ambienti di programmazione visuale e testuale (Max, Pure Data, SuperCollider e simili).
- Workspace e patch di OpenMusic.
- File di progetto di Digital Audio Workstation (Reaper, Ableton Live, Logic Pro e simili), qualora costituiscano parte integrante di un progetto o ne documentino la realizzazione. In tal caso il `README.md` del progetto deve specificare la versione del software e i plugin richiesti; i file audio inclusi devono limitarsi a quelli effettivamente utilizzati.
- Documentazione tecnica relativa ai progetti pubblicati.
- Risorse indispensabili al funzionamento dei progetti (campioni audio, risposte all'impulso, immagini, dati), purché di dimensioni contenute.

### Contenuti esclusi

- Materiali didattici non connessi al codice, da distribuire attraverso i canali indicati nella sezione *Finalità*.
- Materiale coperto da diritto d'autore per il quale non si disponga dei diritti di distribuzione.
- Dati personali degli studenti, in assenza di esplicito consenso.
- Credenziali, chiavi di accesso e ogni altra informazione riservata.

### Cartelle dei corsi

Ciascun docente crea la cartella del proprio corso all'interno della sezione di competenza (`1-triennio/`, `2-biennio/` o `3-workshop/`), includendo un `README.md` con la descrizione del corso, il nome del docente e l'indice dei progetti. In caso di omonimia con una cartella esistente, al nome della cartella va aggiunto il cognome del docente.

### Progetti

- Ogni progetto è collocato in una sottocartella dedicata all'interno della cartella del corso di riferimento.
- I nomi di file e cartelle sono in caratteri minuscoli, con parole separate da trattino e privi di spazi, lettere accentate o caratteri speciali.
- Ogni progetto è accompagnato da un `README.md` che riporti: titolo e descrizione, autore e anno accademico, software e relative versioni, istruzioni per l'esecuzione.
- L'aggiunta di un progetto comporta l'aggiornamento dell'indice nel `README.md` del corso.

### File di grandi dimensioni

GitHub non accetta file superiori a 100 MB e ne sconsiglia l'uso oltre i 50 MB. Le risorse di dimensioni elevate (registrazioni estese, video, dataset) vanno pubblicate in formato compresso oppure ospitate su piattaforme esterne, indicandone il collegamento nel `README.md` del progetto.

### Procedura

Il branch `main` è protetto: ogni modifica avviene tramite Pull Request.

1. Creare un branch a partire da `main`.
2. Effettuare commit circoscritti, accompagnati da messaggi descrittivi.
3. Aprire una Pull Request verso `main`, illustrandone sinteticamente il contenuto, e procedere all'unione.

Gli interventi su cartelle di competenza di altri docenti richiedono la revisione del docente interessato.

È possibile operare anche dall'interfaccia web di GitHub (*Add file → Upload files*), selezionando al momento del commit l'opzione *Create a new branch and start a pull request*.

### Segnalazioni

Segnalazioni di errori, proposte di nuovi contenuti e richieste di modifica alla struttura del repository vanno presentate tramite Issue.

## Licenza

Salvo diversa indicazione nel `README.md` del singolo progetto, i contenuti del repository sono distribuiti con licenza [MIT](LICENSE).

## Referente

Prof. A. Anatrini
