# Docker Compose Repo.

# Install
Kurze Anleitung zur Instalation des Repo's.

## Terminal
Erstelle Ordnerstruktur.
``` bash
mkdir ~/docker-compose && cd ~/docker-compose
```
Kopiere das Perository.
``` bash
git clone https://github.com/devgarden-de/docker_compose_repo.git
```
Gehe in das gewünschte Verzeichniss z.B. "n8n_light"
```bash
cd n8n_light
```

Führe Docker compose aus.
``` bash
docker compose up -d 
```

Der Container sollte nun unter der nachfolgenden URL aufrufbar sein.

http://localhost:5678/