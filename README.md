# Orologio Sveglia 3 — progetto aggiornato

Questa cartella contiene il progetto Android Studio aggiornato partendo dallo ZIP fornito.

## Funzioni inserite nel codice
- Widget digitale in formato 24 ore `HH:mm`, data italiana `Gio 20 NOV` senza anno e ridimensionabile.
- Tre slot sveglia indipendenti; il secondo e il terzo si rendono visibili con il pulsante `+`.
- Selettori numerici di ore e minuti; i giorni della settimana già selezionati vengono conservati.
- Nota facoltativa per ogni sveglia, visualizzata in alto su sfondo bianco con testo rosso in grassetto.
- Pulsante verde `SVEGLIATI !!`: richiede la pressione continua per il numero di secondi configurato e interrompe l'occorrenza corrente.
- Pulsante rosso `SPENGI SVEGLIA`: un tocco breve attiva lo snooze; pressione prolungata (2 secondi predefiniti, configurabili) elimina la programmazione della sveglia, cancella la notifica e chiude la schermata.
- Durata snooze configurabile in minuti.
- Scelta della suoneria di sistema Android oppure registrazione di un vocale personale.
- Ripristino delle programmazioni dopo il riavvio del telefono.

## Prima prova sul telefono
Android può richiedere di autorizzare notifiche, microfono, sveglie esatte e notifiche a schermo intero. La comparsa automatica della schermata sopra la schermata di blocco dipende dalla versione Android, dalle autorizzazioni e dalle restrizioni del produttore.

## Compilazione
Aprire in Android Studio la cartella principale che contiene `settings.gradle.kts`, attendere la sincronizzazione Gradle e selezionare **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

**Stato:** codice aggiornato, ma non ancora verificato con una compilazione Android/Gradle né provato su un dispositivo reale. Non considerare questo archivio un APK già pronto.
