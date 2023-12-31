ARCHINET 

Il mio sito web permette a tutti gli appassionati del mondo dell'architettura e non solo di potersi informare sulle novità architettoniche. Il sito permetterà anche di avere delle consulenze da impiegati certificati per poter avere delle informazioni o degli aiuti nei campi in cui si hanno bisogno.
Questo sito permette anche di poter pubbliccizare la propia attivita grazie al propio account, perchè tutti gli utenti potranno fare una ricerca di azziende o piccole attività che possono essere competenti per il lavoro che si deve svelgere. 
Questa applicazione ci permette di risolvere il probema di non conoscere aziede edili che ci possono svolgere il lavoro. 

COSA DI CUI DEVI AVER BISOGNO PER REGISTRARSI:

      Requisti Funzionali Utente

          - Gli utenti, appena scaricata l’applicazione, si troveranno la classica schermata di registrazione dove inseriranno la propria email e password, con possibilità di cambiarla in caso di dimenticanza.
          - Ci sarà la possibilità di attivare anche l’autenticazione a due fattori, ovvero aggiungere una sicurezza in più per proteggere il tuo account. * Requisti Funzionali Sistema
          - Gestione accesso, registrazione, reset password e autenticazione a due fattori.

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
     
 1. UTENTE LAVORATORE:

          Requisiti Funzionali Utente
    
             -Nome dell'Azienda
             -Numero di Telefono
             -Tipo di azienda
             -Servizio che svolgo

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Accesso),(Utente Lavoratore)^(Accesso),(Utente Lavoratore)>(Nome dell'Azienda),(Utente Lavoratore)>(Numero di Telefono),(Utente Lavoratore)>(Tipo di Azzienda),(Utente Lavoratore)>(Servizio che Svolgono)">
MODELLO DI BUISINES:

Ci saranno due piani di abbonamento a seconda del tipo di utente che sei:
         
        1. UTENTE NORMALE:
        
                L'utente normale avrà la possibilita di selezionare il livello di abbonamento che potrà essere: BASE - MEDIUM - SUPERIOR.
                L'abbonamneto BASE ha una durata di 3 mesi con l'accesso però non a tutte le azziende disponibili nel applicazione
                L'abbonamento MEDIUM ha una durata di 6 mesi con l'accesso a tutte le azziendi disponibili nel applicazione
                L'abbonamento SUPERIOR ha una durata di 12 mesi con l'accesso sempre a tutte le azziende disponibile ma rispetto al MEDIUM quando richiedermo un servizio ad un'azzinede registrata avrà la priorità rispetto
                agli altri utenti.
 <img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso),(Accesso)<(Abbonamenti),(Abbonamenti)>(Paga),(Abbonamenti)>(Scegliere Abbonamento),(Abbonamenti)>(Aggiungere Carta),[Banca]-(Elaborazione),(Elaborazione)>(Invio Risultato di Conferma),[Sistema]-(Attivazione Abbonamento)">               


        2. UTENTE LAVORATORE:
        
                L'utente lavoratore avrà la possiblità di selezionare il livello di abbonamento che potrà essere: BASE - MEDIUM - SUPERIOR:
                L'abbonamneto BASE ha una durata di 3 mesi, permetterà all'azzineda di essere consigliata solo agli UTENTI NORMALI con lo stesso piano di abbonamento
                L'abbonamento MEDIUM ha una durata di 6 mesi, permetterà all'azzeinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE
                L'abbonamento SUPERIOR ha una durata di 12 mesi, prmetterà all'azzinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE ma ripestto al MEDIUM verranno messe in primo piano e consigliate come prima scelta

<img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso),(Accesso)<(Abbonamenti),(Abbonamenti)>(Paga),(Abbonamenti)>(Scegliere Abbonamento),(Abbonamenti)>(Aggiungere Carta),[Banca]-(Elaborazione),(Elaborazione)>(Invio Risultato di Conferma),[Sistema]-(Attivazione Abbonamento)">


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
             

