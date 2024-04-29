# FanVibe

**1. Introduzione:**<br>
   Con FanVibe, i locali e le venue possono gestire la vendita dei propri biglietti in modo efficiente e intuitivo. L'app offre strumenti avanzati per la gestione degli eventi e la vendita dei biglietti, consentendo ai gestori di offrire un'esperienza ottimale ai propri clienti.

**2. Risoluzione del problema:**<br>
   L'applicazione consente ai locali e alle venue di gestire in modo efficace la vendita dei propri biglietti, semplificando il processo e migliorando l'esperienza complessiva per gli acquirenti.

**3. Specifica dei requisiti:**
  - Requisiti Funzionali Utente:<br>
      Gestione degli Eventi:<br>
        - I gestori dei locali devono poter inserire e gestire gli eventi che desiderano organizzare.

      Vendita dei Biglietti:
        - I gestori dei locali devono poter vendere i biglietti per i propri eventi direttamente dall'app.
        - Devono ricevere notifiche elettroniche delle vendite effettuate.

      Dashboard di Gestione:
        - I gestori dei locali devono avere accesso a una dashboard intuitiva per monitorare le vendite dei biglietti e gestire gli eventi.
      
  - Requisiti Funzionali di Sistema:<br>
      Integrazione con Piattaforme di Pagamento:
        - L'app deve integrarsi con piattaforme di pagamento per consentire ai clienti di effettuare pagamenti in modo sicuro e rapido.
      
  - Requisiti Non Funzionali:<br>
      Integrazione con Piattaforme di Pagamento:
        - L'app deve integrarsi con piattaforme di pagamento per consentire ai clienti di effettuare pagamenti in modo sicuro e rapido.
  
  - Requisiti di Dominio:<br>
      Integrazione con Piattaforme di Vendita di Biglietti:
        - L'app deve essere in grado di comunicare con piattaforme di vendita di biglietti esistenti per garantire un'ampia visibilità degli eventi.
      Gestione delle Transazioni Finanziarie:
        - Deve essere implementato un sistema di gestione delle transazioni finanziarie per monitorare le entrate e le uscite legate alla vendita dei biglietti.

**4. Use Case Diagrams:**<br>
  - Gestore del Locale:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Gestore del Locale]-(Inserire Evento),(Inserire Evento)>(Definire Dettagli Evento),(Inserire Evento)>(Pubblicare Evento),[Gestore del Locale]>(Visualizzare Dashboard),[Gestore del Locale]>(Gestire Vendita Biglietti),[Gestore del Locale]>(Ricevere Notifiche Vendite),[Gestore del Locale]>(Visualizzare Rapporti Vendite)">

  - Utente base:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Utente base]-(Selezionare eventi),[Utente base]-(Visualizza profilo utente),[Utente base]-(Logout),[Utente base]-(Acquisto biglietti),[Utente base]-(Invia recensioni),[Utente base]-(Leggere recensioni),(Selezionare eventi)<(Ricerca eventi),(Invia recensioni)>(Lasciare da 1 a 5 stelle),(Invia recensioni)<(Descrivere la recensione),(Acquisto biglietti)>(Selezione dei posti),(Selezione dei posti)<(Visualizzatore VR),(Acquisto biglietti)>(Selezione quantità biglietti),(Acquisto biglietti)>(Inserire nominativo per ogni biglietto),(Acquisto biglietti)>(Pagamento),(Pagamento)>(Inserire dati pagamento),[Sistema bancario]-(Inserire dati pagamento),(Acquisto biglietti)>(Invio biglietti via Email),[Servizi Email]-(Invio biglietti via Email)">

  - Utente manager:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Utente manager]-(Inserimento eventi),(Inserimento eventi)>(Inserimento dati evento),(Inserimento dati evento)<(Seleziona file per visualizzatore VR),[Utente manager]-(Visualizza profilo utente),[Utente manager]-(Logout),[Utente manager]-(Rispondere alle recensioni),[Utente manager]-(Segnalare una recensione)">

**Work Breakdown Structure:**<br>
1. Progetto FanVibe - Software di Gestione Eventi e Vendita Biglietti<br>
  1.1. Pianificazione e Inizializzazione<br>
   &emsp;1.1.1. Definizione degli Obiettivi del Progetto<br>
   &emsp;1.1.2. Stesura del Piano di Progetto<br>
   &emsp;1.1.3. Allocazione delle Risorse<br>
  1.2. Sviluppo dell'Applicazione<br>
   &emsp;1.2.1. Progettazione dell'Architettura del Software<br>
   &emsp;1.2.2. Creazione dell'Interfaccia Utente per i Gestori dei Locali<br>
   &emsp;1.2.3. Implementazione della Funzionalità di Inserimento e Gestione degli Eventi<br>
   &emsp;1.2.4. Integrazione con Piattaforme di Pagamento<br>
  1.3. Implementazione della Dashboard di Gestione<br>
   &emsp;1.3.1. Progettazione della Dashboard per i Gestori dei Locali<br>
   &emsp;1.3.2. Sviluppo delle Funzionalità di Monitoraggio delle Vendite e dei Rapporti<br>
  1.4. Garanzia della Sicurezza e delle Prestazioni<br>
   &emsp;1.4.1. Implementazione della Crittografia dei Dati Utente e delle Transazioni<br>
   &emsp;1.4.2. Test di Sicurezza e Analisi delle Prestazioni<br>
  1.5. Test e Validazione<br>
   &emsp;1.5.1. Test Funzionali dell'Applicazione<br>
   &emsp;1.5.2. Test di Sicurezza e Prestazioni<br>
  1.6. Distribuzione e Lancio<br>
   &emsp;1.6.1. Preparazione per il Lancio del Software<br>
   &emsp;1.6.2. Distribuzione del Software ai Gestori dei Locali<br>
   &emsp;1.6.3. Supporto Post-Lancio e Aggiornamenti del Software
