# traefik (local proxy)

## Run
- `docker compose up -d`

## Dashboard
- http://localhost:8080

## Hosts
Add to your hosts file:
- `127.0.0.1 sociopata.org.local`
- `127.0.0.1 lodorecords.local`

## TLS
Certificates are generated with mkcert and mounted into Traefik.
