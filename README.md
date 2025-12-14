# ⚙️ Flusso Automatico: Gestione Allegati Email

Un flusso di lavoro automatico e robusto costruito con **n8n** per intercettare email con allegati, caricarli immediatamente su Google Drive e notificare l'avvenuto caricamento su Slack con un riepilogo dei file.

## ✨ Caratteristiche Principali

* **Trigger Istantaneo:** Si attiva non appena ricevi una nuova email con allegati.
* **Gestione Multi-Allegato:** Estrae e processa ogni allegato singolarmente.
* **Organizzazione Cloud:** Carica tutti i file nella cartella specifica di **Google Drive**.
* **Notifica Unica:** Invia un **unico messaggio riepilogativo su Slack** contenente i nomi dei file salvati.

## 📺 Video di Spiegazione

Per una spiegazione dettagliata del funzionamento, della configurazione dei nodi e del codice utilizzato, guarda il video qui sotto:

[![Video YouTube - Spiegazione del Flusso n8n](https://imgur.com/a/IvPdoUL)](https://youtu.be/FKftAjtOiJU)

## 🛠️ Requisiti

Per utilizzare questo flusso, avrai bisogno delle seguenti credenziali configurate in n8n:

* **Gmail Account** (OAuth2)
* **Google Drive Account** (OAuth2 API)
* **Slack Account** (OAuth2 API)
