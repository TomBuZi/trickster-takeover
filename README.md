# Trickster Takeover – Loki & Worlds Collide

Eine kleine Web-App als digitaler Spielhelfer für das **Marvel Champions**-Szenario
*Trickster Takeover* (Loki, Kampagne „Worlds Collide"). Sie behält Lokis Status,
die Bedrohung und die abhängigen Werte im Blick, damit du dich aufs Spielen
konzentrieren kannst.

🔗 **Live-Version:** https://tombuzi.github.io/trickster-takeover/

## Funktionen

- **Loki-Statusanzeige** – Stufe 1 / Stufe 2 mit passender Karte und animiertem
  Stufenwechsel (Verwandlungs-Sequenz).
- **Automatische Werteberechnung** abhängig von der Spielerzahl:
  - Lokis Trefferpunkte (20 × Spieler)
  - maximale Bedrohung (2 × Gruppen, 1–4 Spieler pro Gruppe)
- **Bedrohungsanzeige** mit Inline-Bearbeitung – Werte anpassen ohne Spiel-Reset.
- **Sprach-Umschalter** Deutsch / Englisch.
- **Theme-Umschalter** Dunkel- / Hell-Modus.
- **Sperr-Schalter** – schützt Spielerzahl, Gruppen und Reset vor versehentlichem Ändern.
- **Responsives Layout** – skaliert auf die Fenstergröße, ohne über den Rand hinauszulaufen.

## Nutzung

Einfach die Live-Version im Browser öffnen – es ist keine Installation nötig.
Die App ist eine einzelne, eigenständige HTML-Datei.

## Lokal ausführen

Repository klonen und `index.html` direkt im Browser öffnen:

```bash
git clone https://github.com/TomBuZi/trickster-takeover.git
cd trickster-takeover
# index.html im Browser öffnen
```

## Projektstruktur

| Datei              | Beschreibung                                   |
| ------------------ | ---------------------------------------------- |
| `index.html`       | Die komplette App (HTML, CSS und JavaScript)   |
| `55027Ade.jpg`     | Loki-Karte Stufe 1 (deutsch)                   |
| `55028Bde.jpg`     | Loki-Karte Stufe 2 (deutsch)                   |
| `logo.png`         | Logo                                           |
| weitere `*.jpg`    | zusätzliche Kartenscans (Reserve)              |

## Technik

Reines HTML, CSS und JavaScript – keine Build-Tools, kein Framework, keine
Abhängigkeiten. Gehostet über GitHub Pages.
