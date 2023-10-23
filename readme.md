# LB 324

## Aufgabe 2
**Schritte zur Installation von `pre-commit`**

###Voraussetzungen:
   Da `pre-commit` in Python geschrieben ist, muss man zuerst Python auf das System installiert ist. (Falls dies nicht der Fall ist: [Python Download](https://www.python.org/downloads/))

###Installieren von `pre-commit`:
   Zunächst muss man die Kommandozeile oder das Terminal und dann den folgenden Befehl eingeben:
   ```bash
   pip install pre-commit
   ```

###Einrichten von `pre-commit`:
   Um eine Konfigurationsdatei namens .pre-commit-config.yaml im Projektverzeichnis zuerstellen muss man diesen Befehl eingeben 
   ```bash
   pre-commit install
   ```
   Jetzt kann man die .yaml Datei anpassen. Zum Beispiel kann man `flake8` für Code-Stilprüfungen hinzufügen.

###Ausführen der `pre-commit-Hooks`:
   Zum Schluss kann man die `pre-commit-Hooks` ausführen mit folgendem Befehl:
   ```bash
   pre-commit run --all-files
   ```

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
