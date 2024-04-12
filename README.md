# Dmn-Engine vom ProcessCube mit eigener Konfiguration verwenden

Was ist zu tun?
- Repo clonen `git clone git@github.com:moellenbeck/using_dmn_engine.git`
- Docker compose starten `docker compose up`

Ordnerstruktur:
- configs: Konfigurationsdatei des DMN-External-Task
- decisions: DMN-Datei als xlsx oder DMN-Datei
- processes: Beispielprozess mit DMN-External-Task, der beim Start von Docker-Compose automatisch deployed wird

Was ist noch wichtig:
- Engine-URL: http://localhost:8000
- Topic für die External-Task der DMN-Engine: 'dmn.' + Decicion (im Beispiel: Rabatt.xlsx wird zu 'dmn.rabatt')
