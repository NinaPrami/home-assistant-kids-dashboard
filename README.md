# Home Assistant Kids Dashboard 👧📱

Ein kinderfreundliches, stilvolles Tablet-Dashboard für Home Assistant.  
Ideal für Familien mit Kindern, die ihr Smart Home sicher & spielerisch nutzen wollen.

## ✨ Features
- Große, farbige Buttons mit Icons
- Einfache Bedienung für Licht, Musik & TTS („Mama, komm bitte!“)
- Optionaler Uhrzeit-Block
- Responsive Grid-Layout (perfekt für Tablets)
- Kindersicher: keine Admin-Funktionen
- 📁 `www/icons/` – Hier kannst du eigene kindgerechte Icons ablegen. Der Ordner wird durch `.gitkeep` erhalten.


## 📸 Vorschau

![Kids Dashboard](./screenshots/preview.png)

## ⚙️ Anforderungen

- Home Assistant (aktuelle Version)
- [HACS](https://hacs.xyz) installiert
- Folgende Custom Cards:
  - [`layout-card`](https://github.com/thomasloven/lovelace-layout-card)
  - [`button-card`](https://github.com/custom-cards/button-card)

## 🚀 Installation

1. Kopiere den Inhalt von `dashboards/default_view.yaml` in dein Home Assistant Dashboard (YAML-Modus).
2. Stelle sicher, dass du `layout-card` und `button-card` installiert hast.
3. Passe die `entity_id`s an deine Geräte an (z. B. Lichter oder Echo-Geräte).
4. Optional: Passe Farben und Texte nach Belieben an!

## 📦 Noch geplant

- Gute-Nacht-Seite mit Szene & Musik
- Farben nach Tageszeit
- Zeitbasierte Sperre (z. B. keine Musik nach 21 Uhr)

---

📣 Feedback & Pull Requests willkommen!

---

### 💖 Unterstütze mich

Wenn dir das Projekt gefällt, freue ich mich über Unterstützung:

[☕ Buy me a coffee] (buymeacoffee.com/ninaprami)

MIT License © 2025 Nina Pramendorfer
