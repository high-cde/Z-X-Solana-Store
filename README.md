# Z-X Solana Store

Prototipo di agenzia viaggi + eSIM + store crypto sovrano, integrato nell'ecosistema ZDOS.

## Demo live (GitHub Pages)

**https://high-cde.github.io/Z-X-Solana-Store/**

(Abilita Pages in Settings → Pages → Branch `main` / root se non è ancora attivo.)

## Funzionalità

- Ricerca destinazioni, mappe (OpenStreetMap), meteo, info città.
- Link affiliati a partner (Booking, Airbnb, Hostelworld, Google Flights, Skyscanner, GetYourGuide, Wikivoyage, Airalo per eSIM).
- Convertitore valuta (API pubblica).
- Scudo K.I.R.A. ANTI-SCAM integrato.
- Collegamento a ZComm per chat cifrata.
- **Wallet Solana (Phantom) read-only** integrato.
- Gate $DSN / Solana Pay (SOL/USDC) pianificato.
- Pannello Starlink (mock / live) da xCLOUD.

## Stato

Prototipo dimostrativo (M1). Nessuna prenotazione o pagamento reale in questa versione. Segue policy di verità ZDOS.

## Avvio locale

```sh
python3 -m http.server 8080
# Poi http://localhost:8080
```

## Integrazioni

- Wallet Solana: `docs/SOLANA-WALLET.md`
- Scudo K.I.R.A.: vedi `docs/KIRA-SHIELD.md`
- ZComm: link a repo Zcomm
- Security Agent: ZDOS-Security-Agent
- xCLOUD: pannello Starlink e gestionale

## API usate (gratuite / pubbliche)

- OpenStreetMap / Nominatim / Overpass
- Open-Meteo
- Frankfurter (tassi di cambio)
- Wikivoyage / Wikipedia
- Link affiliati (Travelpayouts, Booking Affiliate, Airalo Partner — da attivare)

## Note oneste

Airbnb e Booking non hanno API pubbliche gratuite per offerte reali. Si usano link affiliati e dati pubblici. Per eSIM si rimanda ai provider.
