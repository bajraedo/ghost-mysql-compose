# Ghost + MySQL (Docker Compose)
Dieses Repository enthält eine einfache Docker-Compose-Konfiguration zur Ausführung der Blogging-Plattform [Ghost](https://ghost.org) in Kombination mit einer MySQL-Datenbank.

## Enthaltene Container
- `ghost:5-alpine` – Open-Source Blogging-Plattform (Frontend + Backend)
- `mysql:8.0` – Datenbank zur Speicherung der Inhalte

## Schnellstart

### Voraussetzungen
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Starten
```
docker compose up -d
```
Anschließend ist Ghost unter http://localhost:8082 erreichbar.

### Beenden
```
docker compose down
```

### Struktur
```
.
├── docker-compose.yml
└── README.md
```

### Weitere Informationen
[Ghost Docker Image auf Docker Hub](https://hub.docker.com/_/ghost)

[MySQL Docker Image auf Docker Hub](https://hub.docker.com/_/mysql)
