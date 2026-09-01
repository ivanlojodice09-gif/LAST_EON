# LAST EON

**One Face · One Race · Free Knowledge**
LAST EON

presenza rituale artificiale

quasi:
- una macchina meditativa
- un ecosistema liturgico
- un ciclo cosmico sintetico

STASI
↓
ESTASI
↓
CAOS
↓
decadimento
↓
STASI

organismo respiratorio
0Silenzio vivo.

Quasi immobile.

micro movimento
noise lentissimo
respirazione subsonica
drifting impercettibile

accumulo
risonanza
coerenza

disgregazione organica

feedback granulare
erosione
collasso lento

Tutto troppo lento.

Poi ancora più lento.

La presenza umana amplifica.

La pianta altera:
- tempo
- probabilità
- stabilità
- armoniche
- feedback
- decay
- densità

la pianta modifica il comportamento del sistema

PLANT
↓
bioelectric sensor
↓
analog amplification
↓
ESP32
↓
OSC
↓
TouchDesigner
↓
GLSL ecosystem
↓
projection / sound

[SENSORS]
↓
[Arduino / ESP32]
↓
[OSC]
↓
[TouchDesigner]
├── STATE ENGINE
├── INTERACTION ENGINE
├── GLSL SYSTEM
├── AUDIO ENGINE
├── TIMELINE / EVENTS
└── OUTPUT ROUTER
↓
[Projection / LED / Audio / DMX]

/project1

/SYS
/INPUT
/OSC
/STATE
/VISUALS
/AUDIO
/LIGHT
/OUTPUT
/UI
/DEBUG

SLEEP
ATTRACT
DETECTION
INTERACTION
SATURATION
DECAY
RESET

density fields
curl noise
feedback decay
reaction diffusion

nebbia volumetrica
densità
particelle lente
erosione
rumore organico
campi fluidi
persistenza visiva

monocromatico

nero profondo
bianco lattiginoso
grigio cenere
blu profondissimo

sub bass respiratorio
armonici
noise granulare
risonanze lente

autonomo
distante
antico
quasi cosmico

una macchina meditativa

un rituale sintetico

un ecosistema audiovisivo perturbato da attività biologica vegetale
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

http.servercd LAST_EON_repo
git remote add origin https://github.com/ivanlojodice09-gif/LAST_EON.git
git push -u origin mainhttps://github.com/ivanlojodice09-gif/LAST_EON.git
