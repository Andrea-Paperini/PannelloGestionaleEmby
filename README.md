Il pannello gestionale per Emby Server possiede numerose funzionalità
⬇️⬇️⬇️⬇️⬇️

Pagina di login con google captcha v2.

Disconnessione ➡️ Funzione che permette la disconnessione dell'utente.

Registrazione utente con parametri nome, password, note, connessioni, contenuti adulti e canali.

Registrazione di una prova con parametri nome, password, note (account di durata di due ore) il pannello eliminerà automaticamente gli utenti scaduti.

Migrazione Server ➡️ Funzione che ti permette di migrare gli utenti mantenendo i rispetti parametri (nome, password, note, connessioni, contenuti adulti e canali) su un nuovo server.

Sincronizzatore ➡️ Funzione che scansiona tutti gli utenti e controlla eventuali utenti registrati su Emby ma non presenti sul sito, se un utente viene rilevato viene cancellato automaticamente per evitare problemi di sincronismo.

Scansione dei file della libreria ➡️ Funzione che lancia una scansione dei file della libreria sul server.
Visualizzatore di Host e Porta.

Sezione che tiene i principali download per l'applicazione.

Contatori ➡️ Funzioni che mostrano il totale di: Film, Serie TV, Video Musicali, Episodi e utenti complessivi.

Prova automatica ➡️ Funzione che esegue con un semplice click, una registrazione automatizzata e restituisce nome e password es nome ➡️ prova30 password ➡️ prova30.

Cerca utente ➡️ Funzione che ti permette di cercare un utente con ajax-mysql.

Lista utenti ➡️ la lista degli utenti ( limitata a 10 risultati per pagina ) viene accompagnata dalle operazioni crud basilari ➡️ eliminazione, modifica( tutti i parametri ), prolunga.

Licenze ➡️ Emby non ha il supporto per un contatore di licenze consumate, ho creato una funzione che itera le sessioni sul server e tramite user agent, ti mostra il totale delle licenze consumate e chi le sta consumando.

Playlist ➡️ Emby non supporta (al momento) la disattivazione delle playlist, dato che ogni utente vede le playlist altrui e non solo le proprie ho creato una funzione che elimina automaticamente tutte le playlist esistenti.

Extra
⬇️⬇️⬇️⬇️⬇️
1. La sezione Capofamiglia permette di creare ai rispettivi capofamiglia un loro pannello inferiore che permette di registrare utenti e sottocapofamiglia.
Ogni capofamiglia è in grado di vedere solo gli utenti e i sottocapofamiglia (e poterci interagire) della propria piramide, in questo modo ogni capofamiglia ha la sua privacy
2. Supporto completo per proxy con pagina dedicata di configurazione.
3. Registro nascosto per monitorare le operazioni di ogni Admin (creazione e eliminazione).
4. I 3 pannelli hanno una valuta virtuale immaginaria chiamata "Credito" che viene utilizzata ad ogni operazione di creazione e prolunga al fine di monitorare e limitare le attività
