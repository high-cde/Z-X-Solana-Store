# Integrazione Wallet Solana

## Phantom (read-only nel prototipo)

Il frontend (`index.html`) supporta la connessione a Phantom:

- Rileva `window.solana.isPhantom`
- Richiede connessione (`solana.connect()`)
- Salva solo l'indirizzo pubblico
- Non firma transazioni in automatico
- Non chiede seed phrase

## Uso nel sistema

- Identificazione sessione (come sul sito x-zdos.it)
- Gate per azioni privilegiate (provisioning eSIM, store)
- Preparazione a Solana Pay (SOL / USDC)
- Verifica balance $DSN (via RPC o Æsir/zBAG in futuro)

## Token di riferimento

- $DSN: `35w74RT77BPSYNpmzpvxmR9wu2ihpgzubKy4bkGHR3F4`

## Sicurezza

- Solo indirizzo pubblico memorizzato in memoria del browser.
- Nessuna chiave privata esce dal wallet.
- Allineato alle avvertenze del sito ufficiale.

## Estensioni future

- Firma di messaggi per autenticazione.
- Solana Pay per checkout.
- Lettura balance $DSN / $OV.
