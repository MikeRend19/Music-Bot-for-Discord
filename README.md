# 🤖 Sonora (creato da Mike_Rend)

> Sonora Bot é un semplice bot scritto in python che utilizza un nodo lavalink per riprodurre della musica.

## Requirements

1. Discord Bot Token **[Guida](https://www.aranzulla.it/come-creare-un-bot-su-discord-1670742.html)**  
2. Python 3.10 o versioni piu nuove (potrebbe funzionare con versioni vecchie ma con qualche problema)
3. Un nodo lavalink

## 🚀 Per Iniziare

Inserisci i file:
- bot.py
- playlist_manager.py
- requirements.txt
- .env (da creare)

nella stessa cartella ed esegui il bot con i comandi: 

- `cd C:\Users\TuoNome\Desktop\CartellaBot`

- `pip install -r requirements.txt`

- `python bot.py`

oppure puoi fare :

- `git clone https://github.com/MikeRend19/SonoraBot` (Se hai git installato)

- `cd SonoraBot`

- `pip install -r requirements.txt`

- `python bot.py`

## ⚙️ Configurazione

Crea un file .env e inserisci le informazioni del tuo bot seguendo il modello allegato:

⚠️ **Note: Non rendere mai pubbliche le info che inserirai qui sotto** ⚠️

```
DISCORD_TOKEN="IlTuoToken"

# Lavalink Node Configuration
LAVALINK_HOST= /
LAVALINK_PORT= /
LAVALINK_PASSWORD= /
LAVALINK_SECURE= /
```

## 📝 Funzioni e Comandi 

- 🎶 Ascolta musica da youtube mettendo un url:

`/play (link canzone)`

- 🔎 Ascolta musica da youtube mettendo direttamente il nome della canzone:

`/play (nome canzone)`

- 📃 Ascolta le playlist di youtube via url:

`/play (link playlist)`

- Comando /play
- Sistema di coda 
- Sistema di loop
- Controllo del volume
- Pausa/Riprendi
- Skip
- Funzione creazione playlist locali (con eventuale comando di gestione)

## ⚠️ Funzioni Extra

Il bot ha inoltre un comando:

- `secretvolume`

Che aumenta il volume della musica al massimo e boosta i bassi.
Si puo cambiare la password per eseguire il comando nello script alla riga 26.

