---
title: Informativa sulla privacy
---

# Informativa sulla privacy

Jarvis Client collega un'istanza personale di Hermes Agent all'account Google dell'operatore tramite OAuth 2.0. L'integrazione usa i dati di Gmail per consultare le email, quelli di Google Drive per consultare i documenti e quelli di Google Calendar per consultare e aggiornare gli eventi su richiesta dell'operatore.

## Elaborazione dei dati

Per eseguire le richieste, Hermes può includere nei prompt le informazioni pertinenti ottenute da Gmail, Drive e Calendar. L'elaborazione avviene principalmente su Google Cloud Vertex AI. Quando l'operatore sceglie OpenRouter, il prompt può essere trasmesso a OpenRouter e al fornitore che esegue il modello selezionato. La gestione dei prompt presso i fornitori dipende dal servizio, dal modello e dalle impostazioni in uso.

L'uso dei dati ricevuti dalle API di Google Workspace è soggetto alle norme di Google sui dati degli utenti e alle relative restrizioni di utilizzo limitato. I dati sono destinati a svolgere le funzioni dell'integrazione. L'uso per pubblicità, vendita o addestramento di modelli generalisti è escluso dalle finalità dell'integrazione.

## Conservazione e revoca

I contenuti elaborati possono comparire nella cronologia o nei log dell'istanza Hermes secondo la configurazione dell'operatore. L'operatore può gestire e cancellare tali copie nell'istanza e revocare l'accesso dalle [connessioni dell'Account Google](https://myaccount.google.com/connections). La revoca interrompe l'accesso futuro tramite la connessione OAuth. Per informazioni sulla conservazione presso i fornitori, consulta le policy di [Google Cloud](https://cloud.google.com/security/compliance/ai-trust-and-transparency) e [OpenRouter](https://openrouter.ai/privacy).

[Homepage](./) · [Condizioni d'uso](terms.html)
