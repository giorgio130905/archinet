# archinet

Il mio sito web permette a tutti gli appassionati del mondo dell'architettura e non solo di potersi informare sulle novità architettoniche. Il sito permetterà anche di avere delle consulenze da impiegati certificati per poter avere delle informazioni o degli aiuti nei campi in cui si hanno bisogno.
Questo sito permette anche di poter pubbliccizare la propia attivita grazie al propio account, perchè tutti gli utenti potranno fare una ricerca di azziende o piccole attività che possono essere competenti per il lavoro che si deve svelgere. 
Questa applicazione ci permette di risolvere il probema di non conoscere aziede edili che ci possono svolgere il lavoro. 

COSA DI CUI DEVI AVER BISOGNO PER REGISTRARSI:

Prima di tutto quando faremo l’accesso la prima volta su questa applicazione web ci verrà chiesto ,CHE TIPO DI UTENTE SEI:

    -Utente normale
    -Utente lavoratore
    
A seconda della selezione utente che facciamo i campi che ci serviranno per creare un account saranno differenti:
1. UTENTE NORMALE:
     
          -Mail
          -Nome Utente
          -Numero di Telefono
          -Password
     
 2. UTENTE LAVORATORE:
   
          -Mail
          -Nome dell'Azienda
          -Numero di Telefono
          -Tipo di azienda
          -Servizio che svolgo
          -Password
     
MODELLO DI BUISINES:

Ci saranno due piani di abbonamento a seconda del tipo di utente che sei:
   
        1. UTENTE NORMALE:
                L'utente normale avrà la possibilita di selezionare il livello di abbonamento che potrà essere: BASE - MEDIUM - SUPERIOR.
                L'abbonamneto BASE ha una durata di 3 mesi con l'accesso però non a tutte le azziende disponibili nel applicazione
                L'abbonamento MEDIUM ha una durata di 6 mesi con l'accesso a tutte le azziendi disponibili nel applicazione
                L'abbonamento SUPERIOR ha una durata di 12 mesi con l'accesso sempre a tutte le azziende disponibile ma rispetto al MEDIUM quando richiedermo un servizio ad un'azzinede registrata avrà la priorità rispetto agli altri utenti.
                
<img src="http://yuml.me/diagram/scruffy/usecase/ [UTENTE NORMALE] - (Registrazione),[UTENTE NORMALE] - (Accesso),(Accesso) > (Selezione Piano Abbonamento),(Selezione Piano Abbonamento)>(Transazione),(Transazione) > (Aggiungere Carta),(Transazione) > (Autenticazione),(Transazione) > (Conferma Pagamento)">


   
        2. UTENTE LAVORATORE:
                L'utente lavoratore avrà la possiblità di selezionare il livello di abbonamento che potrà essere: BASE - MEDIUM - SUPERIOR:
                L'abbonamneto BASE ha una durata di 3 mesi, permetterà all'azzineda di essere consigliata solo agli UTENTI NORMALI con lo stesso piano di abbonamento
                L'abbonamento MEDIUM ha una durata di 6 mesi, permetterà all'azzeinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE
                L'abbonamento SUPERIOR ha una durata di 12 mesi, prmetterà all'azzinda di essere consigliata a tutti gli utenti tranne a quelli con il piano BASE ma ripestto al MEDIUM verranno messe in primo piano e consigliate come prima scelta

<img src="http://yuml.me/diagram/scruffy/usecase/ [UTENTE LAVORATORE] - (Registrazione),[UTENTE LAVORATORE] - (Accesso),(Accesso) > (Selezione Piano Abbonamento),(Selezione Piano Abbonamento)>(Transazione),(Transazione) > (Aggiungere Carta),(Transazione) > (Autenticazione),(Transazione) > (Conferma Pagamento)">

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





