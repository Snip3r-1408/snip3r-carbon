# snip3r.de Carbon

> Ein dunkles Carbonfaser-Cockpit für [YourEliteSystems/WebRadio](https://github.com/YourEliteSystems/WebRadio).

**snip3r.de Carbon** ist ein kontrastreiches Theme für alle, die ihren Player dunkel, technisch und unverwechselbar mögen. Es verbindet eine fast schwarze Basis mit einem gewebten 2×2-Carbonfaser-Muster, zurückhaltenden Ultraviolett-Akzenten und einem animierten Spectrum Runner, der am Fensterrand entlangläuft.

Das Design lässt die Musik im Mittelpunkt: keine übertrieben leuchtenden Flächen, keine ausgewaschenen Grautöne. Nur dunkle Materialtiefe, präziser Kontrast und ein kleiner Energieimpuls am Rand.

[English](README.md) · **Deutsch**

## Highlights

- **Gewebte Carbonfaser** – ein bitmapfreies 2×2-Twill-Muster für Titelleiste, Seitenleiste, Karten und Player.
- **Low-Glare Midnight Palette** – fast schwarze Flächen, angenehm bei langen Hörsessions.
- **Elektrische Akzente** – Indigo und Violett heben wichtige Aktionen klar hervor, ohne das Interface zu überladen.
- **Rainbow Runner** – ein schmaler, farbiger Lichtimpuls umrundet das Fenster im Uhrzeigersinn.
- **Maker’s Mark** – ein dezentes `BY SNIP3R`-Wasserzeichen liegt hinter dem Inhaltsbereich.
- **Keine Zusatzdateien** – ein Stylesheet und ein Manifest, ohne Fonts, Bilder oder Abhängigkeiten.

## Die Geschichte

Dieses Theme begann mit einer einfachen Frage: *Wie würde ein Radioplayer aussehen, wenn er sich weniger wie ein Dashboard und mehr wie eine Maschine anfühlt?*

Carbonfaser war die Antwort. Sie wirkt dunkel, leicht und technisch – und ihr Charakter zeigt sich erst, wenn Licht im richtigen Winkel darauf trifft. Genau diesem Prinzip folgt das Muster des Themes: präsent genug, um jeder Fläche Tiefe zu verleihen, aber zurückhaltend genug, damit Sendergrafiken und Musik die Hauptrolle behalten.

Die violetten Bedienelemente erinnern an einen ruhigen elektrischen Strom unter der Oberfläche. Der Rainbow Runner ist der bewusste Kontrast zur Zurückhaltung: ein Impuls, der wie ein lebendiges Signal um das Gehäuse wandert. Daraus entstand **snip3r.de Carbon** – von Grund auf dunkel, bewusst detailliert und für Menschen gemacht, denen die Atmosphäre um ihre Musik genauso wichtig ist wie die Musik selbst.

## Installation

1. Dieses Repository herunterladen oder klonen.
2. Den vollständigen Ordner `snip3r-carbon` in den Benutzer-Theme-Ordner von WebRadio kopieren:

   - **Linux:** `~/.config/webradio/themes/`
   - **Windows:** `%APPDATA%/webradio/themes/`
   - **macOS:** `~/Library/Application Support/webradio/themes/`

3. WebRadio neu starten, die Theme-Auswahl öffnen und **snip3r.de Carbon** wählen.

Die finale Ordnerstruktur muss so aussehen:

```text
themes/
└── snip3r-carbon/
    ├── theme.json
    └── style.css
```

> **Hinweis:** Die verwendete WebRadio-Version muss eingebaute und Benutzer-Themes gemeinsam laden. Falls das Theme nicht erscheint, wird eine Version mit Benutzer-Theme-Erkennung benötigt.

## Kompatibilität

Entwickelt für die aktuelle Electron/React-basierte Theme-Engine von WebRadio. Das Theme nutzt nur Standard-CSS, CSS-Gradienten und eingebettetes SVG; es lädt keine externen Inhalte.

## Anpassung

Die wichtigsten Farbvariablen stehen am Anfang von [`style.css`](style.css). Für schnelle eigene Varianten:

- `--accent-color` für eine andere Hauptfarbe ändern.
- Die SVG-Farbwerte des Rainbow Runners auf eine eigene Farbwelt anpassen.
- Die Regel `#app::after` entfernen, wenn der Look komplett statisch sein soll.
- `.content::before` ändern oder entfernen, um das Wasserzeichen anzupassen.

## Credits

Erstellt von [snip3r.de](https://snip3r.de) für die WebRadio-Community. WebRadio selbst wird von [Your Elite Systems](https://github.com/YourEliteSystems/WebRadio) entwickelt.

## Lizenz

Veröffentlicht unter der [MIT-Lizenz](LICENSE).
