# FanVibe

**1. Introduzione:**<br>
  Con FanVibe potrai acquistare i biglietti del tour del tuo cantante o artista preferito, con la possibilità di lasciare recensioni a tutti gli show ed entrare in realtà virtuale direttamente nell'area concerti per scergliere il miglior posto!

**2. Risoluzione del problema:**<br>
   L'applicazione permetterà di unire in un unico grande spazio tutto ciò che riguarda il mondo dei concerti, quindi recensioni e acquisto di biglietti con la realtà virtuale.

**3. Specifica dei requisiti:**
  - Requisiti Funzionali Utente:<br>
      Registrazione e Autenticazione:
      - Gli utenti devono poter creare un account e accedere all'app.
              
      Recensioni degli Show:
      - Gli utenti devono essere in grado di lasciare recensioni per gli eventi a cui partecipano.
      
      Acquisto di Biglietti:
      - Gli utenti devono poter acquistare biglietti per i concerti direttamente dall'app.
      - Devono ricevere conferme elettroniche dei biglietti acquistati.

      Realtà Aumentata per la Selezione dei Posti:
      - Gli utenti devono poter utilizzare la realtà virtuale per selezionare il miglior posto all'evento.
      
  - Requisiti Funzionali di Sistema:<br>
      Integrazione con Sistemi di Vendita di Biglietti:
      - L'app deve integrarsi con i sistemi di vendita di biglietti per consentire agli utenti di acquistarli.
      
  - Requisiti Non Funzionali:<br>
      Sicurezza:
      - I dati utente devono essere crittografati per garantire la privacy.
      - L'applicazione deve essere protetta da attacchi informatici e vulnerabilità.
      
      Prestazioni:
      - L'app deve avere tempi di risposta rapidi per garantire un'esperienza utente fluida.
      
      Compatibilità:
      - L'app deve essere compatibile con una varietà di dispositivi e sistemi operativi, inclusi smartphone iOS e Android.
      
      Usabilità:
      - L'app deve essere intuitiva per garantire che gli utenti possano utilizzarla facilmente.
  
  - Requisiti di Dominio:<br>
      Integrazione con Piattaforme di Vendita di Biglietti:
      - L'app deve essere in grado di comunicare con i sistemi di vendita di biglietti di terze parti.
      
      Gestione delle Transazioni Finanziarie:
      - Deve essere implementato un sistema di gestione delle transazioni finanziarie per l'acquisto di biglietti.
      
      Integrazione con Tecnologie di Realtà Aumentata:
      - L'app deve integrare tecnologie di realtà aumentata per consentire agli utenti di selezionare i posti negli eventi.

**4. Use Case Diagrams:**<br>
  - Registrazione/Accesso:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Registrazione),(Registrazione)>(Inserire Email),(Inserire Email)>(Conferma Email),(Registrazione)>(Inserire Password),(Inserire Password)>(Conferma Password),(Accesso)<(Autenticazione a due fattori),(Registrazione)>(Inserire Nome),(Registrazione)>(Inserire Cognome),(Registrazione)>(Inserire Data di nascita),(Registrazione)>(Inserire Numero di telefono),(Inserire numero di telefono)>(Verifica con SMS),[Utente]-(Accesso),(Accesso)>(Inserire Email),(Accesso)>(Inserire Password)">

  - Utente base:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Utente base]-(Selezionare eventi),[Utente base]-(Visualizza profilo utente),[Utente base]-(Logout),[Utente base]-(Acquisto biglietti),[Utente base]-(Invia recensioni),[Utente base]-(Leggere recensioni),(Selezionare eventi)<(Ricerca eventi),(Invia recensioni)>(Lasciare da 1 a 5 stelle),(Invia recensioni)<(Descrivere la recensione),(Acquisto biglietti)>(Selezione dei posti),(Selezione dei posti)<(Visualizzatore VR),(Acquisto biglietti)>(Selezione quantità biglietti),(Acquisto biglietti)>(Inserire nominativo per ogni biglietto),(Acquisto biglietti)>(Pagamento),(Pagamento)>(Inserire dati pagamento),[Sistema bancario]-(Inserire dati pagamento),(Acquisto biglietti)>(Invio biglietti via Email),[Servizi Email]-(Invio biglietti via Email)">

  - Utente manager:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Utente manager]-(Inserimento eventi),(Inserimento eventi)>(Inserimento dati evento),(Inserimento dati evento)<(Seleziona file per visualizzatore VR),[Utente manager]-(Visualizza profilo utente),[Utente manager]-(Logout),[Utente manager]-(Rispondere alle recensioni),[Utente manager]-(Segnalare una recensione)">

**Work Breakdown Structure:**<br>
1. Progetto FanVibe<br>
   1.1. Pianificazione e Inizializzazione<br>
       1.1.1. Definizione degli Obiettivi del Progetto<br>
       1.1.2. Stesura del Piano di Progetto<br>
       1.1.3. Allocazione delle Risorse<br>
   1.2. Sviluppo dell'Applicazione<br>
       1.2.1. Progettazione dell'Architettura dell'App<br>
       1.2.2. Creazione dell'Interfaccia Utente<br>
       1.2.3. Implementazione della Funzionalità di Registrazione e Autenticazione<br>
       1.2.4. Integrazione con Sistemi di Vendita di Biglietti<br>
       1.2.5. Gestione delle Transazioni Finanziarie<br>
       1.2.6. Implementazione delle Recensioni degli Show<br>
   1.3. Implementazione della Realtà Aumentata<br>
       1.3.1. Ricerca e Integrazione delle Tecnologie di Realtà Aumentata<br>
       1.3.2. Sviluppo della Funzionalità di Realtà Aumentata per la Selezione dei Posti<br>
   1.4. Garanzia della Sicurezza e delle Prestazioni<br>
       1.4.1. Implementazione della Crittografia dei Dati Utente<br>
       1.4.2. Test di Sicurezza e Analisi delle Vulnerabilità<br>
       1.4.3. Ottimizzazione delle Prestazioni dell'App<br>
   1.5. Test e Validazione<br>
       1.5.1. Test Funzionali<br>
       1.5.2. Test di Sicurezza<br>
       1.5.3. Test di Prestazioni<br>
   1.6. Distribuzione e Lancio<br>
       1.6.1. Preparazione per il Lancio<br>
       1.6.2. Distribuzione dell'App sulle Piattaforme iOS e Android<br>
       1.6.3. Monitoraggio Post-Lancio<br>
   1.7. Formazione e Supporto<br>
       1.7.1. Creazione di Materiale di Formazione<br>
       1.7.2. Supporto Utente Post-Lancio<br>
