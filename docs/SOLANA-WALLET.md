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
- Verifica balance dei token dell'ecosistema

## Token di riferimento (tutti)

### Solana
- **$DSN**: `35w74RT77BPSYNpmzpvxmR9wu2ihpgzubKy4bkGHR3F4`
- **$OV** (VELVET): `2EN6Y1zM4yyt41gE2muzdJSAgRCAZiXqnmkgpbrspump`

### Polygon
- Contratto: `0xfc90516a1f736FaC557e09D8853dB80dA192c296`

Questi token sono da usare per gate, display balance, e integrazioni future con Æsir / zBAG.

## Sicurezza

- Solo indirizzo pubblico memorizzato in memoria del browser.
- Nessuna chiave privata esce dal wallet.
- Allineato alle avvertenze del sito ufficiale.

## Estensioni future

- Firma di messaggi per autenticazione.
- Solana Pay per checkout.
- Lettura balance $DSN / $OV / token Polygon.
