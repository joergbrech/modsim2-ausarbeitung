# Projektdokumentation

## Latex-Vorlage

Dies ist eine Latexvorlage (freundlicherweise zur Verfügung gestellt von [Robin Strickstrock](https://www.h-brs.de/de/emt/robin-strickstrock)), die sie benutzen können, aber nicht müssen.

 - Das Hauptdokument ist `main.tex`. Hier werden alle anderen `.tex`-files inkludiert.
 - Alle verwendeten Pakete müssen in `preamble.tex` über 
   ```latex
   \usepackage{package_name}
   ```
   eingebunden werden.
 - Solange das Hauptdokument `main.tex` heißt, wird es über Continuous Integration mit jedem *push* gebaut.

## Form und Inhalt der Ausarbeitung
 - Die Ausarbeitung muss mit LaTeX verfasst werden.
   - Schriftgröße 11pt
   - Zeilenabstand maximal 1.2-fach
   - Ränder 1.5-3cm.
 - Der Umfang der Ausarbeitung darf **30 Seiten nicht überschreiten**.
 - Sie sind verpflichtet alle **Literaturstellen und andere Quellen** anzugeben.


## Aufbau der Arbeit

Die Gliederung der Arbeit ist Ihnen freigestellt, der folgende ungefähre Aufbau und Inhalt sollte sich aber erkennenlassen.

 1. Motivation und Beschreibung der Problemstellung
 2. Thematische Grundlagen
 3. Herleitung bzw. Erläuterung der Modellgleichungen und der vorgenommenen Modellannahmen und -vereinfachungen
 4. Simulationsdetails: Begründete Wahl des Tools und Auflistung aller Parametereinstellungen, ggf. auch schematischer Ablauf der Simulation. Keine Code-Ausschnitte (bzw. nur wenige Highlights)
 5. Darstellung der Simulationsergebnisse, eventuell Vergleich mit Messungen oder Literatur und Diskussion der Ergebnisse
 6. Zusammenfassung und Ausblick

## Nützliche Links

 - Zum Arbeiten mit Latex benötigen Sie zwingend eine Latexdistribution (für Windows üblicherweise [Miktex](https://miktex.org/), für Mac [MacTeX](http://www.tug.org/mactex/) und für Linux [texlive](https://www.tug.org/texlive/)). Hilfreich ist noch ein Editor wie [Texmaker](https://www.xm1math.net/texmaker/) oder [Kile](https://kile.sourceforge.io/).
 - Unter [diesem Link](https://latex.tugraz.at/latex/warum) finden Sie empfehlenswerte, ausführliche Latexanleitungen von der TU Graz. 
 - [Latex Cheatsheet](http://www.latex4ei.de/downloads/LaTeX_CheatSheet.pdf)
 - [Schreibempfehlungen, inklusive dem C-C-C Schema](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619)