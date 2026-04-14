# expense-tracker

Desktop-Anwendung für private Buchhaltung — Tracking von Einnahmen,
Ausgaben und wiederkehrenden Transaktionen mit monatlicher Übersicht.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![PyQt5](https://img.shields.io/badge/-PyQt5-41CD52?style=flat&logo=qt&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

## Features

- 📊 Monatliche Übersicht über Einnahmen, Ausgaben und Kontostand
- 💾 Lokale Datenhaltung via SQLite (keine Cloud)
- 🔁 Wiederkehrende Transaktionen (Miete, Abos, etc.) einmal anlegen
- ➕ Schnelles Erfassen neuer Einträge über Dialog
- 🧮 Eingebauter Taschenrechner für schnelle Berechnungen
- 📅 Navigation zwischen Monaten

## Screenshots

| Hauptmenü | Fix-Ausgaben | Neue Ausgabe |
|-----------|--------------|--------------|
| ![](doc/screenshots/finanze-app.PNG) | ![](doc/screenshots/finanze-app2.PNG) | ![](doc/screenshots/finanze-app3.PNG) |

## Setup

```bash
git clone https://github.com/OemerErguen/expense-tracker.git
cd expense-tracker/mainproject

pip install PyQt5 qtpy

python main.py
```

## Tech Stack

- **Language:** Python 3
- **GUI:** PyQt5 / qtpy
- **Database:** SQLite

## About

Personal-finance side project — originally built to get comfortable with
Qt-based desktop development and SQLite persistence in Python.
