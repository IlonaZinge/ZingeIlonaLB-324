# LB 324

## Aufgabe 2
**Schritte zur Installation von `pre-commit`**

### Voraussetzungen:
   Da `pre-commit` in Python geschrieben ist, muss man zuerst Python auf das System installiert ist. (Falls dies nicht der Fall ist: [Python Download](https://www.python.org/downloads/))

### Installieren von `pre-commit`:
   Zunächst muss man die Kommandozeile oder das Terminal und dann den folgenden Befehl eingeben:
   ```bash
   pip install pre-commit
   ```

### Einrichten von `pre-commit`:
   Um eine Konfigurationsdatei namens .pre-commit-config.yaml im Projektverzeichnis zuerstellen muss man diesen Befehl eingeben 
   ```bash
   pre-commit install
   ```
   Jetzt kann man die .yaml Datei anpassen. Zum Beispiel kann man `flake8` für Code-Stilprüfungen hinzufügen.

### Ausführen der `pre-commit-Hooks`:
   Zum Schluss kann man die `pre-commit-Hooks` ausführen mit folgendem Befehl:
   ```bash
   pre-commit run --all-files
   ```
## Aufgabe 2
   [Quelle](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python)

## Aufgabe 4

### Da bei mir Azure nicht funktioniert, erkläre ich es theoretisch:
   - Zuerst muss man auf App Service klicken und dann eine Web App erstellen. 
   - Unter Runtimestack muss man Python wählen.
   - Die Region muss East US sein, weil das die einzige konstenlose Option ist.
   - Zum Schluss muss man Review und Create drücken.
   - Jetzt muss man im Deployment Center den deployment mit Github verlinken in dem man sich anmeldet die Organisation Repository und Branch auswählt und auf Save drückt. 
   - Auf Github sieht man den build und deploy und unter Deploy sollte dann der Link sein. So sollte es dann aussehen (Bildquelle: Nina Wösten):
     ![image](https://github.com/IlonaZinge/ZingeIlonaLB-324/assets/91138062/437442ff-23ef-4554-a88d-a08172e7cd89)

   
   Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
