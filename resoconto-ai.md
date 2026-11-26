Resoconto consegna 8

hai creato uno schema Mermaid per le entità Evento e Sede e descritto la relazione: una sede può ospitare più eventi; ogni evento fa riferimento a una sede con Evento.sede_id.
Hai aggiornato programma.html affinché carichi dati/eventi.json e dati/sedi.json con fetch e crei le schede degli eventi, mostrando anche messaggi di caricamento, lista vuota ed errore. Gli eventi con un sede_id non valido dovrebbero apparire con «Sede da definire».
Per provare la pagina hai usato Live Server/Live Preview di Visual Studio Code. I percorsi dei JSON funzionano se la cartella dati è accanto a programma.html; l’apertura diretta del file in Chrome può impedire il funzionamento di fetch.
Hai aggiunto alla pagina «Info e luoghi» una sezione con i dati meteo attuali di Torino tramite Open-Meteo, inclusi temperatura, vento, orario, attribuzione e messaggio d’errore.
Hai regolato il CSS delle schede evento: una colonna sotto i 600 px, due da 600 px e tre da 1024 px, con spaziatura ridotta.
Hai aggiunto uno stile a cornice alle slide Swiper dei luoghi, simile alle schede del programma.
Hai avviato un commit in VS Code: la schermata mostrata chiedeva di inserire un messaggio, poi premere Commit. Per pubblicare le modifiche online potrebbe servire anche Push o Sincronizza modifiche.

Resoconto consegna 9

Abbiamo lavorato sul sito del festival immaginario Segnale:
Convertito i dati degli eventi e delle sedi da JSON a CSV, con intestazioni nella prima riga; i dati contengono 6 eventi e 3 sedi.
Aggiornato lo script di programma.html per leggere eventi e sedi dai fogli pubblicati in formato CSV con Papa Parse, mantenendo schede, sedi, messaggi di stato e fallback «Sede da definire». Gli ID restano stringhe.
Aggiunto alla Home una sezione Notizie da Torino che legge il CSV della scheda notizie, mostra fino a cinque notizie con data e titolo collegato, cita ANSA Piemonte e visualizza un messaggio se il caricamento non riesce.
Chiarito che i link Google Sheets con pubhtml vanno convertiti in link CSV usando pub e output=csv.