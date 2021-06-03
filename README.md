# traefik-v2-example
Traefik v2 example with file configuration provider and external services

```bash
  # Clone this repo
  $ git clone git@github.com:tribal2/traefik-v2-example.git
  $ cd traefik-v2-example

  # Start Trafik v2
  $ docker-compose up -d

  # Start external services
  $ cd sample-external-service
  $ docker-compose up -d

  # Start internal services
  $ cd ../sample-internal-service
  $ docker-compose up -d
```
