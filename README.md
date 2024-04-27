ARCHINET

Il mio sito web permette a tutti gli appassionati del mondo dell'architettura e non solo di potersi informare sulle novità architettoniche. Il sito permetterà anche di avere delle consulenze da impiegati certificati per poter avere delle informazioni o degli aiuti nei campi in cui si hanno bisogno. Questo sito permette anche di poter pubblicizzare la propria attività grazie al proprio account, perché tutti gli utenti potranno fare una ricerca di aziende o piccole attività che possono essere competenti per il lavoro che si deve svolgere. Questa applicazione ci permette di risolvere il problema di non conoscere aziende edili che ci possono svolgere il lavoro.

COSA DI CUI DEVI AVER BISOGNO PER REGISTRARTI:

      Requisiti Funzionali Utente

           -Gli utenti, appena scaricata l’applicazione, si troveranno la classica schermata di registrazione dove inseriranno la propria email e password, con possibilità di cambiarla in caso di dimenticanza.
           -Ci sarà la possibilità di attivare anche l’autenticazione a due fattori, ovvero aggiungere una sicurezza in più per proteggere il tuo account.
            
      Requisiti Funzionali Sistema
           -Gestione accesso, registrazione, reset password e autenticazione a due fattori.

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Registrazione),(Registrazione)<(Autenticazione a Due Fattori)">

CHE TIPO DI UTENTE SEI:

    Requisiti Funzionali Utente
    
          -Utente normale
          -Utente lavoratore

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Accesso),(Utente Normale)^(Accesso),(Accesso Lavoratore)^(Accesso)">

A seconda della selezione utente che facciamo i campi che ci serviranno per creare un account saranno differenti:
1. UTENTE NORMALE:

         Requisiti Funzionali Utente
   
               -Nome Utente
               -Numero di Telefono

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Accesso),(Utente Normale)^(Accesso),(Utente Normale)>(Nome Utente),(Utente Normale)>(Numero Telefono)">
     
 2. UTENTE LAVORATORE:

          Requisiti Funzionali Utente
    
             -Nome dell'Azienda
             -Numero di Telefono
             -Tipo di azienda
             -Servizio che svolgo

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Accesso),(Utente Lavoratore)^(Accesso),(Utente Lavoratore)>(Nome dell'Azienda),(Utente Lavoratore)>(Numero di Telefono),(Utente Lavoratore)>(Tipo di Azzienda),(Utente Lavoratore)>(Servizio che Svolgono)">
MODELLO DI BUISINES:
Gli utenti base non hanno il piano di abbonamneto, gli utenti lavoratori dovranno scegliere tra 3 piani di abbonamento.
        UTENTE LAVORATORE:
        
                L'utente lavoratore avrà la possiblità di selezionare il livello di abbonamento che potrà essere: BASE - MEDIUM - SUPERIOR:
                L'abbonamneto BASE ha una durata di 3 mesi, permetterà all'azzineda di essere consigliata solo agli UTENTI NORMALI con lo stesso piano di abbonamento
                L'abbonamento MEDIUM ha una durata di 6 mesi, permetterà all'azzeinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE
                L'abbonamento SUPERIOR ha una durata di 12 mesi, prmetterà all'azzinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE ma ripestto al MEDIUM verranno messe in primo piano e consigliate come prima scelta

<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Primo Accesso),(Primo Accesso)<(Abbonamenti),(Abbonamenti)>(Paga),(Abbonamenti)>(Scegliere Abbonamento),(Abbonamenti)>(Aggiungere Carta),[Banca]-(Elaborazione),(Elaborazione)>(Invio Risultato di Conferma),[Sistema]-(Attivazione Abbonamento)">


Requisiti non funzionali di sistemi:
   
         Sicurezza:
            -Il sistema deve garantire la sicurezza dei dati dell'utente, compresi i dati dell'account e le informazioni del gioco.
         Performance:
            -Il sistema deve essere reattivo e garantire tempi di risposta rapidi.
         Scalabilità:
            -Il sistema deve essere in grado di gestire un numero crescente di utenti e dati di gioco.
         Usabilità:
            -L'applicazione deve essere intuitiva e facile da usare per gli utenti.
         Disponibilità:
            -Il sistema deve essere disponibile e accessibile in modo affidabile.


   Grafico: Work-breakdown-structure:
   
      Progetto Sito Web Architettura
        |-- Analisi e Pianificazione
        |   |-- Definizione Obiettivi Progetto
        |   |-- Identificazione Stakeholder
        |   |-- Analisi Requisiti Utenti e di Sistema
        |   |-- Pianificazione Tempistica
        |   |-- Budgetizzazione  
        |   
        |-- Sviluppo dell'Applicazione
        |   |-- Progettazione dell'Interfaccia Utente 
        |   |   |-- Schermata di Registrazione  
        |   |   |-- Schermata Principale 
        |   |   |-- Pannello Utente Normale
        |   |   |-- Pannello Utente Lavoratore
        |   |
        |   |-- Implementazione della Registrazione e Accesso 
        |   |   |-- Gestione Email e Password
        |   |   |-- Autenticazione a Due Fattori
        |   |
        |   |-- Gestione Profilo Utente
        |   |   |-- Modifica Profilo Utente Normale
        |   |   |-- Modifica Profilo Utente Lavoratore
        |   |
        |   |-- Sistema di Pubblicizzazione Aziendale
        |   |   |-- Creazione e Gestione Account Aziendale
        |   |   |-- Ricerca e Visualizzazione Aziende
        |   |
        |   |-- Implementazione del Sistema di Consulenze
        |       |-- Richiesta Consulenza Utente Normale
        |       |-- Gestione Consulenze Utenti Lavoratori
        |
        |-- Registrazione Utenti
        |   |-- Definizione Campi di Registrazione per Utente Normale
        |   |-- Definizione Campi di Registrazione per Utente Lavoratore
        |   |-- Implementazione Registrazione Utente Normale
        |   |-- Implementazione Registrazione Utente Lavoratore
        |
        |-- Sistema di Abbonamento
        |   |-- Progettazione Modello di Business
        |   |-- Implementazione Scelta Livello di Abbonamento
        |   |-- Gestione Abbonamenti Utente Normale
        |   |-- Gestione Abbonamenti Utente Lavoratore
        |
        |-- Requisiti Non Funzionali di Sistema
            |-- Sicurezza
            |   |-- Implementazione Crittografia Dati Utente
            |   |-- Gestione Accesso Sicuro
            |
            |-- Performance
            |   |-- Ottimizzazione Codice e Risposta dell'Ap
            |   |-- Monitoraggio Prestazioni
            |
            |-- Scalabilità
            |   |-- Architettura Scalabile del Sistema
            |   |-- Gestione Crescita Utenti
            |
            |-- Usabilità
            |   |-- Test Usabilità dell'App<
            |   |-- Feedback Utenti<
            |
            |-- Disponibilità
                |-- Backup e Ripristino Dati
                |-- Monitoraggio Disponibilità del Sistema

USER STORY:
   
      Sprint 1 (Settimane 1-3): Registrazione Utente e Gestione dell'Account
            Utente Normale:
               1. Come utente normale, voglio registrare un account per accedere alle informazioni architettoniche e ai servizi di consulenza → 8 ore
               2. Come utente normale, voglio inserire la mia email e creare una password per registrare un account → 5 ore
               3. Come utente normale, voglio avere l'opzione di attivare l'autenticazione a due fattori per aumentare la sicurezza del mio account → 8 ore
            Utente Lavoratore:
               1. Come utente lavoratore, voglio registrare un account aziendale per pubblicizzare la mia attività e fornire servizi di consulenza → 8 ore
               2. Come utente lavoratore, voglio inserire il nome della mia azienda, il numero di telefono e specificare il tipo di azienda e i servizi offerti → 5 ore
            Sviluppatori:
               1. Implementazione della schermata di registrazione per entrambi i tipi di utenti → 8 ore
               2. Creazione delle funzionalità di inserimento di email, password e attivazione dell'autenticazione a due fattori → 13 ore
               3. Sviluppo della schermata di registrazione aziendale e integrazione delle informazioni aziendali →8 ore
            Responsabili della Sicurezza:
               1. Verifica e implementazione dei meccanismi di sicurezza per la gestione delle password → 13 ore
               2. Implementazione dell'autenticazione a due fattori per garantire una maggiore sicurezza per gli utenti → 8 ore
         
      Sprint 2 (Settimane 4-6): Funzionalità Avanzate e Ottimizzazioni
            Utente Normale:
               1. Come utente normale, voglio selezionare il livello di abbonamento per accedere a diverse funzionalità del sito → 8 ore
               2. Come utente normale, voglio cercare aziende in base al tipo di servizio e alla competenza → 13 ore
               3. Come utente normale, voglio ricevere consulenze da impiegati certificati → 8 ore
            Utente Lavoratore:
               1. Come utente lavoratore, voglio selezionare il livello di abbonamento per aumentare la visibilità della mia azienda → 13 ore
               2. Come utente lavoratore, voglio essere consigliato agli utenti con livelli di abbonamento MEDIUM e SUPERIOR → 8 ore
               3. Come utente lavoratore, voglio fornire consulenze e assistenza agli utenti interessati → 8 ore
            Sviluppatori:
               1. Implementazione delle opzioni di abbonamento per utenti normali e lavoratori → 13 ore
               2. Sviluppo della funzionalità di ricerca avanzata basata su tipo di servizio e competenza → 21 ore
               3. Implementazione del sistema di raccomandazione per gli utenti lavoratori → 13 ore
            Responsabili della Sicurezza:
               1. Continuazione della revisione e miglioramento della sicurezza del sistema → 21 ore
               2. Verifica e implementazione di eventuali aggiornamenti per mantenere la sicurezza del sistema → 13 ore
         
            Note:
            Ogni user story è stimata in modo da occupare circa 10 ore di lavoro.
            La durata degli sprint è di 3 settimane ciascuno, con 40 ore di lavoro settimanali.
            Al termine di ogni sprint, è previsto un periodo di revisione e testing per garantire la qualità delle nuove funzionalità implementate.

PIVOT DEL PROGETTO:

      1. Identificazione delle tecnologie emergenti:
            Dopo un'attenta analisi delle ultime tendenze nel settore dell'architettura e della progettazione, abbiamo individuato alcune tecnologie emergenti che potrebbero essere integrate per migliorare l'esperienza degli utenti su ARCHINET.
      2. Valutazione dell'applicabilità:
            Abbiamo valutato come queste tecnologie possano essere integrate per migliorare la fruizione delle informazioni architettoniche, facilitare la consulenza e favorire la pubblicità delle aziende nel settore.
      3. Definizione dei requisiti:
            Abbiamo stabilito i requisiti funzionali e non funzionali per l'integrazione delle seguenti tecnologie emergenti:
      4. Sviluppo e integrazione:
            -Realta Aumentata (AR): Consente agli utenti di visualizzare modelli architettonici in AR direttamente attraverso l'app ARCHINET. Gli utenti possono esplorare dettagli architettonici in tempo reale, interagire con gli elementi e "posizionare" virtualmente progetti nella loro area di interesse.
            -Visualizzazione 3D interattiva: Implementiamo strumenti per permettere agli utenti di creare e manipolare modelli architettonici in 3D direttamente sulla piattaforma. Questo offre un'esperienza di progettazione più interattiva e consente agli utenti di esplorare diverse opzioni di design.
            -Machine Learning per la raccomandazione di aziende: Utilizziamo algoritmi di machine learning per analizzare i dati degli utenti e suggerire aziende edili o servizi di consulenza basati sulle esigenze e le preferenze specifiche di ciascun utente.
      5. Test e validazione:
            Condurremo test approfonditi per garantire che le nuove funzionalità integrate funzionino correttamente e offrano un'esperienza utente ottimale. Coinvolgeremo gli utenti beta per raccogliere feedback e identificare eventuali problemi o aree di miglioramento.
      6. Educazione degli utenti:
            Creeremo risorse educative, come guide utente e video tutorial, per aiutare gli utenti a familiarizzare con le nuove funzionalità basate sulle tecnologie emergenti. Forniremo inoltre supporto continuo agli utenti attraverso canali di comunicazione appropriati.
      7. Lancio e monitoraggio:
            Lanciaremo ufficialmente le nuove funzionalità integrate nella piattaforma ARCHINET, comunicando efficacemente agli utenti i benefici delle novità. Monitoreremo attentamente l'utilizzo e il feedback degli utenti per valutare l'efficacia delle nuove funzionalità e identificare eventuali aree di miglioramento.
      8. Iterazione e miglioramento continuo:
            Utilizzeremo i dati raccolti dal monitoraggio post-lancio per iterare sulle funzionalità esistenti e apportare miglioramenti basati sul feedback degli utenti. Continueremo a monitorare le tendenze e le innovazioni nel campo delle tecnologie emergenti per identificare opportunità future di miglioramento e sviluppo.
