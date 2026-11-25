# Particle-Life-G
 Particle Life – Emergent Behavior Projekt Gruppe G

Zara
Anna
Melek
Monawara

## Projektbeschreibung

Im Rahmen des Moduls Data Science und KI Infrastrukturen (Wintersemester 2026/2027) entwickeln wir eine Particle-Life-Simulation mit Python.

Dabei bewegen sich verschiedene Partikeltypen in einer zweidimensionalen Welt und beeinflussen sich gegenseitig. Je nach Partikeltyp und Abstand wirken unterschiedliche Kräfte, die entweder Anziehung oder Abstoßung verursachen.

Aus diesen einfachen Regeln sollen komplexe Bewegungsmuster und Strukturen entstehen. Dieses Phänomen wird als emergentes Verhalten bezeichnet.

## Ziele

Ziel des Projekts ist es, eine funktionierende und möglichst performante Simulation zu entwickeln.

Die wichtigsten Funktionen sind:

- Simulation mit mindestens vier verschiedenen Partikeltypen, also Farben/Formen
- Bewegung der Partikel in einer zweidimensionalen Welt
- Interaktionsmatrix zur Steuerung von Anziehung und Abstoßung
- Berücksichtigung von Abstand und maximaler Interaktionsreichweite
- Reibung und Dämpfung
- Einstellbare Simulationsparameter
- Reproduzierbare Initialisierung durch einen Zufalls-Seed
- Dynamische Visualisierung der Partikelbewegungen
- Möglichkeit, die Simulation ohne grafische Oberfläche auszuführen

## Technologien

Für die Umsetzung verwenden wir folgende Technologien und Bibliotheken:

| Technologie | Verwendung |
|---|---|
| Python | Programmiersprache |
| NumPy | Numerische Berechnungen |
| VisPy | Grafische Darstellung |
| PySide6 | Optionale grafische Benutzeroberfläche |
| uv | Verwaltung der Python-Umgebung |
| pytest | Automatisierte Tests |
| Ruff | Codequalität und Formatierung |
| GitHub Actions | Continuous Integration |
| Numba | Optionale Performance-Optimierung |

## Installation

Zuerst das Repository klonen:

```bash
git clone <https://github.com/dmitrikovaa/Particle-Life-G.git>
```

In das Projektverzeichnis wechseln:

```bash
cd particle-life
```

Abhängigkeiten installieren:

```bash
uv sync
```

Die Anwendung starten:

```bash
uv run python -m particle_life.main
```

## Projektstruktur

```text
particle-life/
│
├── src/
│   └── particle_life/
│       ├── main.py
│       ├── config.py
│       ├── particles.py
│       ├── forces.py
│       ├── simulation.py
│       └── visualization.py
│
├── tests/
├── benchmarks/
├── docs/
├── pyproject.toml
├── uv.lock
└── README.md
```

## Tests und Performance

Die Simulationslogik wird mit pytest getestet. Dabei überprüfen wir unter anderem die Partikelinitialisierung, die Wechselwirkungen, die Bewegung und die Randbedingungen.

Mit Ruff achten wir auf eine einheitliche Codequalität und Formatierung.

Zusätzlich untersuchen wir die Laufzeit der Simulation mit verschiedenen Partikelanzahlen. Mithilfe von Profiling und Benchmarks sollen mögliche Performance-Engpässe erkannt und optimiert werden.

Unser Ziel ist eine flüssige Simulation mit ungefähr 2.000 bis 10.000 Partikeln.

## Zusammenarbeit

Wir entwickeln das Projekt gemeinsam in einem Team (4 Personen) über GitHub.

Für die Zusammenarbeit verwenden wir:

- GitHub Issues zur Aufgabenverteilung
- GitHub Projects zur Projektplanung
- Feature-Branches für neue Funktionen
- Pull Requests und Code Reviews
- GitHub Actions für automatisierte Tests

## Milestones

| Termin | Ziel |
|---|---|
| 25.11.2026 | Projektsetup und Architektur |
| 16.12.2026 | Basis-Simulation |
| 06.01.2027 | Dynamische Visualisierung |
| 27.01.2027 | Performance-Optimierung |
| 24./25.02.2027 | Finalisierung und Präsentation |

## Team

**Studiengang:** Data Science, AI & Intelligent Systems

**Hochschule:** Hochschule Düsseldorf

**Modul:** Data Science und KI Infrastrukturen

**Semester:** Wintersemester 2026/2027

**Teamgröße:** 4 Studierende

**Teammitglieder:** Melekoooo, Zaraaa, Annaa, Monaaaa