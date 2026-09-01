https://github.com/https://github.com/cd LAST_EON_repo
git remote add origin https://github.com/<tuo-utente>/LAST_EON.git
git push -u origin maincd LAST_EON_repo
git remote add origin https://github.com/ivanlojodice09-gif/LAST_EON.git
git push -u origin mainhttps://github.com/ivanlojodice09-gif/LAST_EON.git# LAST_EON
LAST EON OPEN SOURCE IMMERSIVE DIGITAL EXPERIENCE - Wildland Revolution for free knowledge. 1 race, One face. By Ivan Nicola Lojodice
# LAST EON

**One Face · One Race · Free Knowledge**

Sistema generativo bio-interattivo: DataCore, rete di Eoni (0–25), TouchDesigner, WebSocket, manifesto interattivo neon-glitch.

> Wildland Revolution — dal Prisma **Stasi → Estasi → Caos**.

---

## Contenuti della repository

| Percorso | Descrizione |
|----------|-------------|
| `docs/` | PDF compilati (documentazione completa + tomi) |
| `web/` | Manifesto interattivo (HTML self-contained) |
| `src/datacore/` | Ring buffer, snapshot, trend analysis |
| `src/network/` | Server WebSocket di stato |
| `src/touchdesigner/` | Snippet API Python per TD |
| `assets/images/` | Visual di riferimento |
| `config/` | Parametri JSON di esempio |

---

## Avvio rapido — Web Manifesto

Apri nel browser (doppio clic o server statico):

```bash
# opzionale: server locale
cd web && python -m http.server 8080
# → http://127.0.0.1:8080
```

Controlli:
- **POWER** — accende il sistema
- **Prisma** — Stasi (immagine) → Estasi (diffusion) → Caos (explosion + sposa)
- **Loop Auto** — ciclo continuo
- **Moduli** — Bio / Data / Particle / WebSocket / …

---

## WebSocket server

```bash
pip install websockets
python src/network/lasteon_ws_server.py
# default: ws://127.0.0.1:8765
```

Dalla web page: pannello **Moduli ▾** → Connect.

Protocollo (JSON ~15 Hz):

```json
{
  "power": true,
  "prisma": 0.42,
  "state": "ESTASI",
  "modules": { "bio": true, "data": true, "particle": true }
}
```

---

## DataCore (concetto)

Ring buffer FIFO (`deque(maxlen=N)`) per stati bio / sensor / visual:

- `push(state)` — inserimento O(1)
- `snapshot()` — congelamento frame
- `trend(window)` — deriva temporale
- modalità **SAFE_MODE** — limiti particelle / risoluzione TOP

Vedi `src/datacore/` e i PDF in `docs/tomes/`.

---

## Documentazione PDF

1. `docs/LAST_EON_COMPILAZIONE_COMPLETA.pdf` — master
2. `docs/tomes/01_GLITCH_NEON.pdf` — layout estetico
3. `docs/tomes/02_DataCore_TD_API.pdf` — architettura + TouchDesigner
4. `docs/tomes/03_Memory_WebSocket.pdf` — memoria + rete

---

## Struttura consigliata su GitHub

```text
LAST_EON/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
├── web/
├── src/
├── assets/
└── config/
```

### Pubblicare

```bash
cd LAST_EON_repo
git init
git add .
git commit -m "Initial commit — LAST EON manifesto, DataCore, WebSocket, docs"
git branch -M main
git remote add origin https://github.com/<tuo-utente>/LAST_EON.git
git push -u origin main
```

---

## Licenza

Codice e docs di progetto: vedi `LICENSE` (MIT salvo diversa indicazione).
Immagini personali / dedicazioni: diritti riservati all’autore.

---

**LAST EON · 2026.1**

