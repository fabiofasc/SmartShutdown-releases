# Smart Shutdown

**Utility intelligente per Windows** che monitora le temperature hardware (CPU/GPU) e gestisce lo spegnimento automatico del PC quando le temperature si stabilizzano.

Ideale per chi lascia il PC acceso durante rendering, encoding, o altre operazioni intensive e vuole che si spenga automaticamente quando ha finito.

## Funzionalit&agrave;

- **Smart Shutdown** - Chiude i processi non critici, attende la stabilizzazione delle temperature, poi spegne il PC
- **Boost** - Chiude i processi per liberare memoria senza spegnere
- **Boost + Sospendi** - Chiude i processi e mette il PC in sospensione
- **Monitor Risorse** - Mostra i processi che consumano pi&ugrave; CPU e RAM

## Requisiti

- Windows 10/11 (x64)
- Privilegi di Amministratore (richiesti automaticamente)

## Download

Scarica l'ultima versione dalla sezione [**Releases**](https://github.com/fabiofasc/SmartShutdown-releases/releases).

1. Scarica il file `SmartShutdown-v0.2-beta-win-x64.zip`
2. Estrai il contenuto
3. Avvia `SmartShutdown.exe`

> L'app richieder&agrave; automaticamente i privilegi di amministratore (necessari per leggere i sensori hardware).

## Screenshot

L'interfaccia mostra in tempo reale:
- Temperature CPU, GPU e MAX
- Log delle operazioni
- Pulsanti per le diverse modalit&agrave;

## Hardware Supportato

- **CPU**: Intel e AMD (testato su AMD Ryzen 9 7950X)
- **GPU**: NVIDIA e AMD (testato su AMD RX 6700 XT)

## Autore

**Fabio Fasciglione** - [fabiofasciglione.it](http://fabiofasciglione.it)

## Licenza

Questo progetto &egrave; distribuito sotto licenza [MIT](LICENSE).
