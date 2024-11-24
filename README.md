# Caddy on Docker Compose

This repository contains the Docker Compose configuration to run a Caddy with LE and DNS-0 authentication.

## Getting Started

1. `cp env.tpl .env`
2. Update `.env`
3. Create volumes: `mkdir -p volumes/caddy`
4. `docker compose up`
