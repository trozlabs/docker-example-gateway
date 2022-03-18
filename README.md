# Docker + Nginx Reverse Proxy

Add to `/etc/hosts` or equivelent on Windows.

    127.0.0.1 example.tld
    127.0.0.1 app.example.tld
    127.0.0.1 api.example.tld

- http://example.tld
- http://app.example.tld
- http://api.example.tld

To Run all containers together.
    
    docker compose -f docker-compose.yml up
    docker compose -f docker-compose.yml down


To Run individual containers from the root directory

    docker compose -f example-gateway/docker-compose.yml up
    docker compose -f example-gateway/docker-compose.yml down

    docker compose -f example-app/docker-compose.yml up
    docker compose -f example-app/docker-compose.yml down

    docker compose -f example-api/docker-compose.yml up
    docker compose -f example-api/docker-compose.yml down