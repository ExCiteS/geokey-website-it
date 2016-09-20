---
layout: tutorial
title: "Creando un nuovo progetto"
---

I progetti sono il punto di partenza per le vostre attività di Community Maps. Se si desidera mappare i luoghi preferiti nella tua città o luoghi nel tuo quartiere che necessitano di miglioramento - abbiamo creato una interfaccia semplice per creare e gestire i progetti. In un progetto, è possibile definire quali tipi di dati verranno raccolti e quali utenti possono accedere, contribuire dati o moderare un progetto.

Questo documento descrive le fasi di creazione di un nuovo progetto: come creare categorie e campi e come utilizzare i gruppi di utenti (user groups) per concedere autorizzazioni per gli utenti.

### Creare un progetto

Per creare un nuovo progetto, iniziare selezionando l’opzione *Create new project*.

![Creare un progetto](images/how-to-create-project-01.png)

Nella pagina seguente, vi verrà chiesto di compilare un modulo con i seguenti campi:

- **Name** (nome): Scegliere un nome per il progetto. Il nome sarà utilzzato dagli utenti per identificare il progetto. Questo campo è obbligatorio.
- **Description** (descrizione): È possibile fornire informazioni più estese sul progetto qui.
- **Project visibility** (visibilità del progetto): Qui si può decidere - al livello del progetto intero - chi avrà accesso al progetto ed ai contributi.
    - Scegli *Private* (privato) se si desidera limitare l'accesso ad un gruppo selezionato di utenti. Progetti privati ??sono accessibili agli amministratori e membri dei gruppi di utenti (user groups) assegnati al progetto. È possibile configurare e gestire gruppi di utenti dopo aver creato il progetto.
    - Scegli *Public* (pubblico) se si desidera che il progetto sia pubblicamente disponibile. Gli utenti che desiderano accedere ai dati del progetto non devono essere registrata per visualizzare i contributi sulla mappa.
- **Project permissions** (le autorizzazioni di progetto): Qui si può decidere - sempre al livello progetto - chi puo contribuire al progetto. Le opzioni dipendono dal fatto che il progetto è privato o pubblico.

    **Public projects** (progetti pubblici)

    - Scegli *All users* (Tutti i gli utenti) e ogni utente può contribuire i dati al vostro progetto, anche se non e loggato.
    - Scegli *All authenticated users* (Tutti gli utenti autenticati) e tutti gli utenti che hanno effettuato l'accesso (fatto il login), possono contribuire i dati.
    - Scegli *Only members of contributor groups can cantribute* (Solo i membri di gruppi collaboratore possono contribuire), e solo gli utenti, che sono membri di gruppi specifici di utenti, che dispone di autorizzazioni collaboratore, saranno in grado di contribuire al progetto.

    **Private projects** (progetti privati)

    - Scegli *All users* (Tutti gli utenti) e tutti gli utenti che hanno accesso al progetto potranno contribuire anche i dati.
    - Scegli *Only members of contributor groups can cantribute* (Soltanto i membri di gruppi collaboratore possono contribuire), e solo gli utenti, che sono membri di gruppi specifici di utenti, che dispone di autorizzazioni collaboratore, saranno in grado di contribuire al progetto.

Finfine, fai clic su _Save_ (Salva) per creare il progetto. La pagina cambiera al project dashboard (la pagina per gestire il progetti), che fornisce i dettagli più importanti del progetto.

### Creare una categoria

Ora che abbiamo [creato un nuovo progetto](#creare-un-progetto), vogliamo configurare le categorie ed i loro campi per la raccolta dei dati.

Le categorie definiscono il tipo di dati di un contributo. I campi di una categoria definiscono gli attributi di un contributo tra i tipi di dati (ad esempio, testo, numero o una data).

Dalla project dashboard, selezionare _Create category_ (creare una categoria).

![Creare una categoria](images/how-to-create-project-02.png)

Nella pagina seguente, vi verrà chiesto di compilare un modulo con i seguenti campi:

- **Name** (nome): Scegliere un nome significativo per la categoria. Il nome sarà presentato a tutti gli utenti per identificare la categoria. Questo campo è obbligatorio.
- **Description** (descrizione): È possibile fornire informazioni estese sulla tua categoria qui.
- **Default status for new contributions** (stato predefinito per i nuovi contributi): ogni nuovo contributo ha uno status iniziale, qui si decide cosa quello stato dovrebbe essere:
    - *Pending* (In attesa): utilizzare questa opzione, se si desidera esaminare nuovi contributi prima della pubblicazione. Un moderatore del progetto avra bisogno di approvare il contributo prima che apparirà sulla mappa.
    - *Active* (Attivo): Il contributo sarà visibile sulla mappa immediatamente.

Fare clic su _Save_ (Salva) per creare la categoria. La prossima pagina vi data l’opporunita di aggiungere dei campi (fields) alla categoria.

### Creare i campi (fields)

Ogni categoria contiene una serie di campi che definiscono gli attributi di un contributo, il loro tipo di dati, nonché i vincoli per il campo.

Per creare un nuovo campo, clicca su _Create new field_ (Creare un nuovo campo).

Nella pagina seguente, vi verrà chiesto di compilare un modulo con i seguenti campi:

- **Name** (nome): Scegliere un nome significativo per il campo. Il nome sarà visibile a tutti gli utenti per identificare il campo. Questo campo è obbligatorio.
- **Description** (descrizione): È possibile fornire informazioni estese su vostro campo qui.
- **A value for this field is mandatory** (l’utente deve inserire un valore in questo campo): selezionare questa casella se si vuole garantire che un valore viene fornito dal contributori.
- **Type** (tipo): specifica il tipo di dati del campo.

Fare clic su _Save_ (Salva) per creare il campo.

#### Informazione Ulteriore

A secondo del tipo di campo che avete selezionato, è possibile fornire ulteriori proprietà per un campo.

##### Text field (campo di testo)

- **Display this field as textarea** (visualizza questo campo come textarea): Seleziona questa casella se il campo deve essere visualizzato come area di testo invece di un campo di input di una riga.
- **Maximum length** (lunghezza massima): Definire il numero di caratteri che sono accettati come input. Lasciare tge campo vuoto se non si desidera limitare la lunghezza.

##### Numeric field (campo numerico)

- **Minimum value** (valore minimo): il valore più basso accettato per il campo. Lasciare il campo vuoto se non si desidera impostare un valore minimo.
- **Maximum value** (valore massimo): Il più grande valore accettato per il campo. Lasciare il campo vuoto se non si desidera impostare un valore massimo.

##### Select field and multiple select field (selezionare dalla lista, selezionare pui valori dalla lista)

Si modifica l'elenco dei valori per questi campi dopo aver creato il campo.
