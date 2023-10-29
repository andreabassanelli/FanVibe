# FanVibe

**1. Introduzione:**
  Con FanVibe potrai acquistare i biglietti del tour del tuo cantante o artista preferito, con la possibilità di lasciare recensioni a tutti gli show ed entrare in realtà aumentata direttamente nell'area concerti per scergliere il miglior posto!

**2. Risoluzione del problema:**
   L'applicazione permetterà di unire in un unico grande spazio tutto ciò che riguarda il mondo dei concerti, quindi recensioni e acquisto di biglietti con la realtà aumentata.

**3. Specifica dei requisiti:**
  - Requisiti Funzionali Utente:
      Registrazione e Autenticazione:
      - Gli utenti devono poter creare un account e accedere all'app.
              
      Recensioni degli Show:
      - Gli utenti devono essere in grado di lasciare recensioni per gli eventi a cui partecipano.
      
      Acquisto di Biglietti:
      - Gli utenti devono poter acquistare biglietti per i concerti direttamente dall'app.
      - Devono ricevere conferme elettroniche dei biglietti acquistati.

      Realtà Aumentata per la Selezione dei Posti:
      - Gli utenti devono poter utilizzare la realtà aumentata per selezionare il miglior posto all'evento.
      
  - Requisiti Funzionali di Sistema:
      Integrazione con Sistemi di Vendita di Biglietti:
      - L'app deve integrarsi con i sistemi di vendita di biglietti per consentire agli utenti di acquistarli.
      
  - Requisiti Non Funzionali:
      Sicurezza:
      - I dati utente devono essere crittografati per garantire la privacy.
      - L'applicazione deve essere protetta da attacchi informatici e vulnerabilità.
      
      Prestazioni:
      - L'app deve avere tempi di risposta rapidi per garantire un'esperienza utente fluida.
      
      Compatibilità:
      - L'app deve essere compatibile con una varietà di dispositivi e sistemi operativi, inclusi smartphone iOS e Android.
      
      Usabilità:
      - L'app deve essere intuitiva per garantire che gli utenti possano utilizzarla facilmente.
  
  - Requisiti di Dominio:
      Integrazione con Piattaforme di Vendita di Biglietti:
      - L'app deve essere in grado di comunicare con i sistemi di vendita di biglietti di terze parti.
      
      Gestione delle Transazioni Finanziarie:
      - Deve essere implementato un sistema di gestione delle transazioni finanziarie per l'acquisto di biglietti.
      
      Integrazione con Tecnologie di Realtà Aumentata:
      - L'app deve integrare tecnologie di realtà aumentata per consentire agli utenti di selezionare i posti negli eventi.

**4. Use Case Diagrams:**
    - Registrazione/Accesso:
    <img src="http://yuml.me/diagram/scruffy/usecase/[Utente]-(Registrazione),(Registrazione)>(Inserire Email),(Inserire Email)>(Conferma Email),(Registrazione)>(Inserire Password),(Inserire Password)>(Conferma Password),(Registrazione)<(Autenticazione a due fattori),(Registrazione)>(Inserire Nome),(Registrazione)>(Inserire Cognome),(Registrazione)>(Inserire Data di nascita),(Registrazione)>(Inserire Numero di telefono),(Inserire numero di telefono)>(Verifica con SMS),[Utente]-(Accesso),(Accesso)>(Inserire Email),(Accesso)>(Inserire Password)">
