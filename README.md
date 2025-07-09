# h2-optimization-pem_sim
Techno-economic simulation of hydrogen production with PEM electrolyzer and storage strategy.

# SmartH2Agent

**Ziel:**  
Dieses Projekt entwickelt ein intelligentes Agentensystem zur Steuerung einer PEM-Elektrolyse. Ziel ist es, auf Basis historischer und zukünftiger Strompreise sowie des aktuellen Speicherstands wirtschaftlich sinnvolle Entscheidungen zu treffen – z. B. wann Wasserstoff produziert, gespeichert oder eingespeist werden soll.

Das Projekt folgt einem funktionalen Entwicklungsansatz und dient gleichzeitig als praxisnahes Lernprojekt zur Vertiefung relevanter Data-Science- und Engineering-Skills (ETL, SQL, ML, Visualisierung).

---

## 🔧 Funktionen (geplant)

- **ETL:** Einlesen und Bereinigen von Strompreis-Daten
- **Agentenlogik:** Entscheidungsmodell (regelbasiert und ML-basiert)
- **Simulation:** Zeitliche Ausführung von Entscheidungen
- **Logging:** Speicherung von Entscheidungen und Ergebnissen in SQLite
- **Visualisierung:** Analyse des Agentenverhaltens
- **Modularer Code:** Funktional strukturierter Python-Code in Modulen

---

## 📁 Projektstruktur (vorläufig)

```bash
SmartH2Agent/
│
├── data/               # Input-Daten (z. B. Strompreise)
├── db/                 # SQLite-Datenbank (optional)
├── src/                # Funktionale Module (ETL, Agent, Modell, Visualisierung)
├── main.py             # Einstiegspunkt zur Ausführung
├── requirements.txt    # Python-Abhängigkeiten
├── README.md           # Diese Datei
└── .gitignore
