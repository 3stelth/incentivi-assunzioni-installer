# Incentivi Assunzioni: installer

Qui ci sono solo gli installer per Windows dell'app "Incentivi Assunzioni" (nella sezione Releases) e il file `notizie.json` con le novità normative mostrate nella campanella dell'app.

Nessun codice e nessun dato: il codice sta in un repository privato, i dati restano sui computer dello studio.

## notizie.json

Ogni notizia ha questi campi:

| Campo | Valori |
|---|---|
| `id` | testo univoco, es. `inps-2026-142` |
| `tipo` | `circolare_inps`, `messaggio_inps`, `decreto`, `legge`, `ddl`, `altro` |
| `numero` | es. `n. 142 del 28/10/2026` |
| `data` | data del documento, `AAAA-MM-GG` |
| `titolo`, `riassunto` | testo breve |
| `incentivi` | id degli incentivi interessati: `bonus-giovani-under35`, `bonus-donne`, `esonero-under30`, `bonus-zes` |
| `stato` | `in_verifica`, `applicata`, `nessun_impatto` |
| `versioneApp` | solo se `applicata`, es. `0.2.0` |
| `impatto` | facoltativo, es. `Nessun lavoratore cambia esito` |
| `url` | collegamento `https://` al documento ufficiale |

Le notizie informano soltanto: le regole dell'app cambiano solo con un aggiornamento approvato.
