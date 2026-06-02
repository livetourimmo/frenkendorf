# Interaktives Brand Moodboard — Rheinstrasse Frenkendorf

Dieses Repository enthält das offizielle interaktive Brand Moodboard und Materialkonzept für das Neubauprojekt an der **Rheinstrasse in Frenkendorf (Kanton Basel-Landschaft)**.

Das Projekt besteht aus **19 hochwertigen Stockwerkeigentumswohnungen (STWE)** mit überdurchschnittlich grossen Sonnenterrassen und Balkonen, eingebettet in eine geschützte L-förmige Architektur.

---

## 🌟 Features der interaktiven Präsentation

Dieses Moodboard wurde als hochperformante, portable Single-Page-Anwendung konzipiert (inspiriert durch die Welcome Home-Linie) und bietet folgende Funktionen:

* **Dynamic Morphic Switching (3 Brand-Konzepte):** Wechseln Sie über den Header-Switcher oder die Concept Cards direkt zwischen den drei ausgearbeiteten Markenwelten:
  1. **Aurelia (Sonnenseite — Favorit):** Erdige Geborgenheit mit mineralischem Terrakotta-Beige, warmem Mokka und edler Bronze.
  2. **Frenco (Urbaner Puls):** Kontrastreiches, modernes skandinavisches Wohnen mit hellem Kupfer, Waldgrau, Sichtbeton und Salbeigrün.
  3. **Rhenia (Freiraum fliesst):** Organische Hofoase mit Muschelkalk, hellem Eschenholz und sattem Waldgrün.
* **Haptik- & Material-Morphing:** Die Detailbeschreibungen des **Schweizer Ausbaustandards** passen sich bei Klick auf ein Markenkonzept vollautomatisch an die jeweilige Materialstimmung an.
* **Click-to-Copy Farbsystem:** Alle Farbcodes sind als interaktive Kacheln gestaltet. Ein Klick kopiert den HEX-Farbcode direkt in die Zwischenablage (mit Toast-Meldung).
* **Live UI- & Button-Vorschau:** Testen Sie die Tasten-Stile (0px Kantenradius passend zur geometrischen Gebäudearchitektur) im echten Hover-Zustand.

---

## 📸 Integrierte Visualisierungs-Assets

Im Ordner `assets/` befinden sich fünf fotorealistische Renderings im Schweizer Ausbaustandard, die direkt in das Moodboard eingebunden sind:

1. `aurelia_moodboard.png` — Südwest-Fassade des L-Winkelbaus während der Goldenen Stunde.
2. `frenco_moodboard.png` — Heller Innenraum bei klarer Morgensonne mit Sichtbeton-Akzenten.
3. `rhenia_moodboard.png` — Blick auf die üppig begrünten Ergolzauen-Bepflanzungen im Innenhof.
4. `fassade_aussen.png` — Schweizer Putzfassade mit integriertem Denner-Supermarkt im Erdgeschoss.
5. `innenraum_eigentum.png` — Fliessende Hebe-Schiebetüren mit Blick auf die Sonnenterrasse bei Abendrot.

---

## 🚀 Hosting auf GitHub Pages (Anleitung)

Sie können diese Präsentation in weniger als einer Minute **kostenlos im Web hosten**, um sie Kunden, Agenturen oder Investoren per Link freizugeben:

1. Laden Sie diesen Ordner (`Github_Moodboard_Frenkendorf`) in ein neues, eigenes Repository auf Ihrem GitHub-Konto hoch.
2. Navigieren Sie in den Repository-Einstellungen zu **Settings** (Zahnrad-Symbol oben rechts).
3. Wählen Sie im linken Menü unter *Code and automation* den Punkt **Pages** aus.
4. Wählen Sie unter *Build and deployment* -> *Source* die Option **Deploy from a branch**.
5. Wählen Sie unter *Branch* Ihren Haupt-Branch (z.B. `main` oder `master`) und den Ordner `/ (root)` aus und klicken Sie auf **Save**.
6. Nach ca. 30 Sekunden ist Ihre interaktive Projekt-Website unter `https://<ihr-benutzername>.github.io/<repo-name>/` weltweit abrufbar!

---

## 📁 Repository-Struktur

```bash
├── index.html         # Die interaktive Hauptpräsentation (HTML5, Vanilla CSS, JS)
├── assets/            # Ordner für Visualisierungen im Schweizer Standard
│   ├── aurelia_moodboard.png
│   ├── frenco_moodboard.png
│   ├── rhenia_moodboard.png
│   ├── fassade_aussen.png
│   └── innenraum_eigentum.png
├── README.md          # Diese Dokumentation
└── .gitignore         # Ausschlussliste für Git-Systeme
```

---
*Konzept und Ausarbeitung durch Antigravity AI — 2026.*
