# Modellbildung und Simulation 2 - Ausarbeitung

Dies ist der Starter Code für ihre Ausarbeitung. Bitte ändern Sie den Titel dieser Datei entsprechend ihres Projekttitels um. 

|  Ordner   |  Beschreibung   |
| --- | --- |
| `docs` | Latex-Dateien für die Projektdokumentation |
| `src`  | Alle Quelldateien eurer entwickelten Programme |
| `tests` | *Optional:* Unit tests für eure entwickelten Funktionen in `src` |


## Projektbeschreibung

...

## Abgabe

Die Abgabe Ihrer Ausarbeitung erfolgt über den Issue Tracker dieses repository. Erstellen Sie _vor Ablauf ihrer Deadline_ ein Issue, in dem Sie ihre kompilierte Projektbeschreibung als Anhang beifügen und mir (@joergbrech) das Issue zur Bearbeitung zuweisen.

Folgende Bedingungen müssen zusätzlich erfüllt sein:

 - :pencil2: Ändern Sie den Titel dieser `README.md` Datei.

 - :clipboard: Kopieren Sie ihre Projektbeschreibung aus der vorherigen Aufgabe in den Abschnitt "Projektbeschreibung" von dieser `README.md` Datei.

 - :speech_balloon: Der Quellcode muss gut dokumentiert und fehlerfrei ausführbar sein.

 - :exclamation: Der Latexcode muss kompilierbar sein.


## Zusatzinformationen
<details>
<summary>Teamarbeit mit GIT</summary>

Sie arbeiten gemeinsam als Team an einem Projekt. Es empfiehlt sich vorab die Aufgaben zu verteilen. Der Issue Tracker bietet sich hier als unterstützendes Tool an.

Damit es möglichst zu wenigen Konflikten kommt, bietet es sich an, die Aufgaben so zu verteilen, dass man sich möglichst wenig in die Quere kommt. Am besten arbeitet ihr, in dem ihr **nur in seltenen Ausnahmen** direkt in den `master` branch commitet. Idealerweise folgt ihr dem Workflow mit Pull Requests:

Angenommen Maja möchte eine bestimmte Teilaufgabe bearbeiten, z.B. das Kapitel "Stand der Technik" in die Projektdokumentation einfügen.

 - Maja wechselt in ihrer lokalen Kopie des repositories auf den `master` branch und sorgt dafür, dass sie alle aktuellen Änderungen aus dem Github repository enthält:

   ```bash
   git checkout master
   git pull
   ```

 - Sie erstellt einen neuen lokalen branch mit einem sprechenden Namen, z.B. `maja/chapter-stand-der-technik`, und welchselt in diesen branch

    ```bash
    git checkout -b maja/chapter-stand-der-technik
    ```

 - Anschließend kann Maja Dateien ändern oder neue hinzufügen, und jede inkrementelle Änderung *commit*en.

    ```bash
    git add 02_stand_der_technik.tex
    git add main.tex
    git commit -m "Stand der Technik Kapitel geschrieben"
    ```

 - Sie kann jederzeit ihre lokalen Änderungen auf das Github repository *push*en. 
   Der Befehl

    ```bash
    git push -u origin HEAD
    ```

    erstellt einen neuen branch im *remote* Github repository mit dem selben Namen wie ihr lokaler branch. Wenn Sie weitere Änderungen an dem branch vornehmen möchte, muss sie beim nächsten mal nur noch 

    ```bash
    git push
    ```

    eingeben, da es schon im *remote* Github repository einen branch mit demselben Namen gibt.

 - Sobald Maja mit der Bearbeitung ihrer Teilaufgabe fertig ist, kann sie auf Github eine *Pull Request* stellen, und einen ihrer Teammitglieder, Peter, um einen *review* bitten. Wenn Peter mit Majas Änderungen einverstanden ist, kann er den *Pull Request* in den `master` branch *mergen*.

  - Sobald Maja's Änderungen im `master` übernommen sind, kann der branch `maja/chapter-stand-der-technik` ohne Bedenken gelöscht werden.

</details>

<details>
<summary>Automatische Tests</summary>
</details>

 - [Git Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
 - [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
 - [Markdown Emoticons](https://gist.github.com/rxaviers/7360908)