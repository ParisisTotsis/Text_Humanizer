# KI-Text-Humanizer

Ein lokales Python-Programm, das KI-generierte und andere Texte natürlicher formuliert. Es nutzt **Ollama** mit dem Modell **Gemma 3 (4B)** und bietet eine grafische Oberfläche mit **Tkinter**.

**Ziel:** Schreibstil, Wortwahl und Satzbau verbessern – nicht übersetzen. Die ursprüngliche Sprache und Aussage sollen erhalten bleiben.

## Funktionen

- Texte mit bis zu 20.000 Zeichen überarbeiten
- Vier Schreibstile: Natürlich, Locker, Professionell und Einfach
- Überarbeitete Texte kopieren oder als TXT speichern
- Lokale KI-Verarbeitung ohne kostenpflichtigen API-Schlüssel
- Deutsche Benutzeroberfläche

## Voraussetzungen

- Python 3 mit Tkinter
- [Ollama](https://ollama.com/download)
- Modell `gemma3:4b`
- Optional: Visual Studio Code

## Installation

**1. Ollama installieren und starten**

Ollama von der offiziellen Website herunterladen und auf dem Mac starten.

**2. KI-Modell herunterladen**

```bash
ollama pull gemma3:4b
```

**3. Python überprüfen**

```bash
python3 --version
python3 -m tkinter
```

**4. Humanizer starten**

```bash
python3 ki_text_humanizer.py
```

## Verwendung

1. Text eingeben.
2. Gewünschten Schreibstil auswählen.
3. Auf „Text humanisieren“ klicken.
4. Ergebnis überprüfen, kopieren oder speichern.

## Beispiel

**Vorher:**

„Die Implementierung dieser Maßnahme ist von entscheidender Bedeutung.“

**Mögliche Überarbeitung:**

„Es ist wichtig, diese Maßnahme umzusetzen.“

## Projektstruktur

```text
KI-Text-Humanizer/
├── ki_text_humanizer.py
├── README.md
└── .gitignore
```

## Datenschutz

Die Textverarbeitung erfolgt über die lokal laufende Ollama-Schnittstelle. Der Python-Code benötigt keinen externen KI-API-Dienst.

KI-generierte Überarbeitungen sollten auf inhaltliche Richtigkeit geprüft werden. Eine bestimmte Bewertung durch KI-Erkennungssysteme wird nicht garantiert.
