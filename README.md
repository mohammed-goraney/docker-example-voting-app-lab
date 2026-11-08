# Docker Example Voting App Lab

A hands-on Docker lab completed after a Docker fundamentals course. The lab demonstrates how multiple services communicate through Docker Compose and a shared network.

## Architecture

```text
Vote App (Python/Flask)
        |
      Redis (queue)
        |
Worker (.NET)
        |
PostgreSQL
        |
Result App (Node.js)
```

## Technologies

- Docker and Docker Compose
- Redis and PostgreSQL
- Python/Flask, .NET Worker, and Node.js
- Container networking and environment variables

## What this lab demonstrates

- Multi-container orchestration with Docker Compose
- Service discovery over a shared Docker network
- Queue-backed background processing
- Persistent storage with PostgreSQL
- Troubleshooting with `docker logs`

## Status

Completed hands-on lab. This repository currently serves as the public documentation record; cleaned compose files and configuration examples will be added as they are prepared for publication.

Portfolio: https://github.com/mohammed-goraney/my-portfolio
