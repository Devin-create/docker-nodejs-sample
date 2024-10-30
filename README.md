# Installation des Projektes
## Klonen des Repository
- Git herunterladen, mit dem Laptop über SSL verbinden
- Erstelle einen **Fork**.
- Wähle deinen Path aus, nutze **cd** um den Path zu ändern
## Installation der notwendigen Pakete
- Nach dem Klonen installierst du die notwendigen Pakete
## Docker Konfiguation-und Installation
- Docker Installieren
- Konto einrichten
- Docker mithilfe von **"wsl --update"** im Terminal ready machen
## Starten der Applikation in einem Docker-Container
Es wird die Applikation als Localhost geöffnet, als auch Hintergrund gestartet
- Nutze "docker init" in Bash, um Docker zu initialisieren
- Anschliessend schreibe **"docker compose up --build"** um die Anwendung im Docker Container zu starten
- Die Applikation wird über **local:host3000** geöffnet
- Beende die Webseite mit ctrl c in der Kommandozeile 
- Öffne die Applikation im Hintergrund mit **"docker compose up --build -d"***
  

