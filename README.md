# Data Science UE in MCIT (Sommer 2026)

Willkommen im Repository für die Übung (UE) Data Science im Studiengang Management, Communication & IT (MCIT). Dieses Repository enthält alle Materialien, Datensätze und Jupyter Notebooks für das Sommersemester 2026.

# 🐍 Python Version
Dieser Kurs und alle bereitgestellten Skripte sind für Python 3.14 optimiert. Es wird empfohlen, diese Version zu verwenden, um die Kompatibilität mit den neuesten Sprachfeatures und Bibliotheks-Updates sicherzustellen.

# 🛠 Setup & Installation
Um eine konsistente Arbeitsumgebung zu gewährleisten und Konflikte mit anderen Projekten zu vermeiden, wird die Verwendung einer virtuellen Umgebung (virtualenv) dringend empfohlen.

## Virtuelle Umgebung erstellen

Stelle sicher, dass du Python 3.14 installiert hast. Navigiere im Terminal in das Projektverzeichnis und führe folgenden Befehl aus:

```Bash
# Erstellt eine virtuelle Umgebung mit Python 3.14
python3.14 -m venv .venv
```

## Umgebung aktivieren

Je nach Betriebssystem unterscheidet sich der Befehl zur Aktivierung:

* Windows:

```Bash
.venv\Scripts\activate
```

* macOS / Linux:

```Bash
source .venv/bin/activate
```

## Abhängigkeiten installieren (requirements.txt)

Sobald die Umgebung aktiviert ist (erkennbar am Präfix (.venv) in der Konsole), installiere alle notwendigen Pakete:

```Bash
pip install --upgrade pip
pip install -r requirements.txt

```

> **Hinweis:** Die requirements.txt enthält alle spezifischen Versionen der benötigten Bibliotheken (wie ``pandas``, `scikit-learn` und `matplotlib`), die für Python 3.14 getestet wurden.

# 📁 Struktur des Repositories

* `/notebooks`: Wöchentliche Übungsblätter und Fallstudien.
* `/data`: Rohdaten und prozessierte Datensätze.
* `/src`: Modularer Python-Code und Hilfsfunktionen.
