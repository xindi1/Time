# Time Kit — Timer / Stopwatch / World Clock (Sun-Clock Rugged UI)

A rugged, offline-ready **Timer + Stopwatch + World Clock** built as a **single HTML app** with Sun-Clock design principles:
- **Blue/Light theme toggle**
- **Instrument-panel cards**
- **Sun-phase background** (night / dawn / day / dusk)
- **Progress bars + markers** (timer fill, stopwatch minute sweep, top-of-hour markers)
- **Installable PWA** (iOS Add to Home Screen, Android Install App)
- **No frameworks / no build step**

---

## What’s Included

### ⏳ Timer
- Set hours/minutes/seconds + quick presets
- Start / pause / reset
- Rugged progress bar that **fills as time elapses**
- Optional beep on completion

### ⏱️ Stopwatch
- Start/pause, lap, reset
- Lap list (most recent on top)
- Progress bar tracks the **current minute sweep** (always meaningful, even after hours)

### 🌍 World Clock
- Add IANA time zones (ex: `Europe/London`)
- Quick add buttons (NY, LA, London, Berlin, Tokyo)
- Each world clock shows a **top-of-hour marker** (minutes+seconds position)

### 🌅 Sun-phase Background
Uses **your saved latitude/longitude** to estimate sunrise/sunset and set:
- `phase-night`, `phase-dawn`, `phase-day`, `phase-dusk`

You can:
- enter coordinates manually, or
- tap **Use my location** (geolocation permission)

---

## Repo Structure

