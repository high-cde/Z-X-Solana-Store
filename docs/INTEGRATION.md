# Integrazione comunicazione Z-X Solana Store

## Collegamenti attivi (laboratorio)

- **Scudo K.I.R.A.**: controllo dominio simulato nel frontend.  
  In produzione: POST a Security Agent `/check`.

- **ZComm**: link a demo chat cifrata.  
  Provisioning eSIM tramite `zcomm_gateway.provisionEsim()`.

- **DSN**: record di provisioning possono essere propagati dal nodo.

- **Security Agent**: ogni richiesta sospetta può essere inoltrata.

## Protocollo

Vedi `docs/COMMUNICATION-PROTOCOL.md` nel repo ZDOS.

## Demo

Il file `index.html` contiene i punti di chiamata. Estendere con `fetch()` verso endpoint locali quando i servizi sono in esecuzione.
