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

### Theoretische Einrichtung einer Web App auf Azure:

1. **Web App Erstellung:**
   - Klicken Sie im Azure Dashboard auf **App Service** und erstelle eine Web App.
     
2. **Konfiguration der Laufzeitumgebung:**
   - Wählen Sie **Python** als Runtimestack aus.
     
3. **Regionale Einstellungen:**
   - Stellen Sie die Region auf **East US** ein, da dies die einzige kostenlose Option ist.
     
4. **Überprüfung und Erstellung:**
   - Klicken Sie auf **Review + Create**. Dann wird die Web App erstellt.
     
5. **Einrichtung des Deployment Centers:**
   - Verknüpfen Sie im Deployment Center das Deployment mit GitHub, indem Sie sich anmelden, die entsprechende Organisation, das Repository und den Branch wählen und dann auf **Save** klicken.
     
6. **Überprüfung des Deployments:**
   - Auf GitHub können Sie den Build- und Deploy-Prozess verfolgen. Der Link zur fertigen Web App sollte im Bereich **Deploy** zu finden sein. So sollte es dann aussehen (Bildquelle: Nina Wösten):
     ![image](https://github.com/IlonaZinge/ZingeIlonaLB-324/assets/91138062/437442ff-23ef-4554-a88d-a08172e7cd89)


