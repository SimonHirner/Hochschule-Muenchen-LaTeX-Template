# Hochschule-Muenchen-LaTeX-Template

Mein persönliches LaTeX Template für die Erstellung von Seminar-, Bachelor- oder Masterarbeiten an der Hochschule München.

## Voraussetzungen

- LaTeX-Distribution mit pdflatex und Biber als Backend für BibLaTeX
- LaTeX-Editor

## Benutzung

1. Dieses Repository klonen oder herunterladen
2. `bachelor-thesis.tex` mit beliebigem LaTeX-Editor öffnen und mit pdflatex ausführen

## Aufbau der Arbeit

- Titelblatt
- Abstract
- Inhaltsverzeichnis
- Abbildungsverzeichnis
- Tabellenverzeichnis
- Quellcodeverzeichnis
- Abkürzungsverzeichnis
- Inhalt
- Literarturverzeichnis
- Selbständigkeitserklärung

## Projektstruktur

- `chapters`:  Enthählt die Kapitel der Arbeit
- `figures`: Enthählt Bilder und Grafiken der Arbeit
- `logos`: Enhält Logos für die Arbeit
- `pages`: Enthält die Seiten für das Abstract, das Abkürzungsverzeichnis und das Titelblatt
- `bachelor-thesis.tex`: Herzstück des Projektes, fügt alle Komponenten zu einer Arbeit zusammen
- `bibliography.bib`: Enhält die Literaturangaben für die Arbeit
- `settings.sty`: Enthält Einstellungen für die gesamte Arbeit

## Literaturverzeichnis

Für das Literaturverzeichnis und Zitate wird BibLaTex verwendet. Die Literaturangaben werden in `bibliography.bib` eingefügt. Als Backend wird Biber verwendet.

## Lizenz

Dieses Projekt ist unter den Bedingungen der [MIT Lizenz](http://en.wikipedia.org/wiki/MIT_License) öffentlich verfügbar.
