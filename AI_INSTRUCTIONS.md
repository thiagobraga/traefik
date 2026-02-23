# AI Instructions for traefik

## Common commands
- Build: `docker compose build`
- Start (detached): `docker compose up -d`
- Start (rebuild): `docker compose up --build -d`
- Stop (fast): `docker compose down --timeout 0`
- Logs: `docker compose logs -f --tail=200`

## General instructions
- Keep answers short.
- When asked to restart the project: `docker compose down --timeout 0` then `docker compose up --build -d`.
