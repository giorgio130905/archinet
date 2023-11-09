# archinet

Il mio sito web permette a tutti gli appassionati del mondo dell'architettura e non solo di potersi informare sulle novità architettoniche. Il sito permetterà anche di avere delle consulenze da impiegati certificati per poter avere delle informazioni o degli aiuti nei campi in cui si hanno bisogno.
Questo sito permette anche di poter pubbliccizare la propia attivita grazie al propio account, perchè tutti gli utenti potranno fare una ricerca di azziende o piccole attività che possono essere competenti per il lavoro che si deve svelgere. 
Questa applicazione ci permette di risolvere il probema di non conoscere aziede edili che ci possono svolgere il lavoro. 

COSA DI CUI DEVI AVER BISOGNO PER REGISTRARSI:

    * Requisti Funzionali Utente

    - Gli utenti, appena scaricata l’applicazione, si troveranno la classica schermata di registrazione dove inseriranno la propria email e password, con possibilità di cambiarla in caso di dimenticanza.
    - Ci sarà la possibilità di attivare anche l’autenticazione a due fattori, ovvero aggiungere una sicurezza in più per proteggere il tuo account. * Requisti Funzionali Sistema
    - Gestione accesso, registrazione, reset password e autenticazione a due fattori.

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Registrazione),(Registrazione)<(Autenticazione a Due Fattori)">

CHE TIPO DI UTENTE SEI:

    * Requisiti Funzionali Utente
    -Utente normale
    -Utente lavoratore

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Accesso),(Utente Normale)^(Accesso),(Accesso Lavoratore)^(Accesso)">

A seconda della selezione utente che facciamo i campi che ci serviranno per creare un account saranno differenti:
1. UTENTE NORMALE:

         *Requisiti Funzionali Utente
          -Nome Utente
          -Numero di Telefono

<img src="http://yuml.me/diagram/scruffy/usecase/[UTENTE]-(Accesso),(Utente Normale)^(Accesso),(Utente Normale)>(Nome Utente),(Utente Normale)>(Numero Telefono)">
     
 1. UTENTE LAVORATORE:

          *Requisiti Funzionali Utente
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
                
<img src="http://yuml.me/diagram/scruffy/usecase/ [Utente]-(Accesso),(Accesso)<(Abbonamenti),(Abbonamenti)>(Paga),(Abbonamenti)>(Scegliere Abbonamento),(Abbonamenti)>(Aggiungere Carta),
[Banca]-(Elaborazione),(Elaborazione)>(Invio Risultato di Conferma),[Sistema]-(Attivazione Abbonamento)">

        2. UTENTE LAVORATORE:
                L'utente lavoratore avrà la possiblità di selezionare il livello di abbonamento che potrà essere: BASE - MEDIUM - SUPERIOR:
                L'abbonamneto BASE ha una durata di 3 mesi, permetterà all'azzineda di essere consigliata solo agli UTENTI NORMALI con lo stesso piano di abbonamento
                L'abbonamento MEDIUM ha una durata di 6 mesi, permetterà all'azzeinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE
                L'abbonamento SUPERIOR ha una durata di 12 mesi, prmetterà all'azzinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE ma ripestto al MEDIUM verranno messe in primo piano e consigliate come prima scelta

<img src="http://yuml.me/diagram/scruffy/usecase/ [UTENTE LAVORATORE] - (Registrazione),[UTENTE LAVORATORE] - (Accesso),(Registrazione) > (Selezione Piano Abbonamento),(Selezione Piano Abbonamento)>(Transazione),(Transazione) > (Aggiungere Carta),(Transazione) > (Autenticazione),(Transazione) > (Conferma Pagamento)">

MODALITA' DI PAGAMENTO:

Gli utenti alla fine della registrazione e scelta del piano di abbonamento che meglio credono per loro dovranno inserire la modalità di pagamneto che potrà essere scelta tra:

        -Carte di credito e dibito (Visa,Mastercard,American Express, Nexi)
        -Carte prepagate Postepay
        -Paypal

RICERCA DELLA ZONA:

Gli utenti all'interno della applicazione web troveranno una funzione chiamata : "RICERCA VICINO A TE",questa fuznione cosa fa:

        1.Apre una mappa virtuale
        2.Dovremo cerchiare con il dito la zona in cui vogliamo fare la ricerca
        3.Verranno visualizzati tutti i risultati e gli utenti potranno selezionare il più comodo per loro


<img src="http://yuml.me/diagram/scruffy/usecase/ [SISTEMA] - (Attivazione Abbonamento),[SISTEMA] - (Ricerca Cliente),(Ricerca Cliente) > (Apertura della Mappa),[SISTEMA] - (Ricerca Azienda Edile),(Ricerca Azienda Edile) > (Apertura della Mappa),(Apertura della Mappa) > (Visualizzazione Risultati)">




