# Ed Muhlestein

Personal full-stack microservices project focused on learning modern web, container, and AI technologies.

## Overview

This is a Docker Compose–based microservices application currently running in both local development and a personal production environment.

- **Main website**: Node.js service (in active development; website functionality is being migrated here)
- **AI service**: FastAPI (Python) — currently also serving some website duties while migration continues; intended long-term home for AI features
- **Game engine**: Separate Node.js service (early stage)
- **Database**: PostgreSQL
- **Reverse proxy**: Nginx
- **Deployment**: Docker Compose (dev on Windows, production on a Debian VM via remote Docker context)
- **Public site**: [edmuhlestein.com](https://edmuhlestein.com)

## Tech Stack

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" alt="Nginx" width="40" height="40"/>

## Certifications

<a href="https://www.credly.com/badges/6fc3053b-562b-4fe7-bfd3-1d8bd3ab667b/public_url">
  <img src="https://images.credly.com/size/110x110/images/80d8a06a-c384-42bf-ad36-db81bce5adce/blob" alt="CompTIA Security+" width="60">
</a>

## Status

- Node.js website service: under active development
- FastAPI AI service: in transition from temporary website duties to dedicated AI work
- Game engine service: early exploration
- Infrastructure (Docker Compose, Nginx, Postgres, remote deployment): functional

## Goals

Primary goal is learning. Secondary goal is to have a clean, publicly available example of modern full-stack and microservices work.

## Getting Started (Local)

```bash
# clone the repo
git clone ...

# start the development stack
docker compose up
```

(Add any specific environment variables, ports, or notes here.)

## Architecture Notes

(Brief description of service boundaries, how requests flow through Nginx, planned AI features, etc.)

## Background

Principal software engineer with decades of experience spanning systems programming and enterprise web development.

- Early career: C/C++ and microkernel work on AIX at IBM, followed by UNIX/Motif contract work.
- Long tenure at Landmark Graphics / Halliburton building and maintaining large oil & gas applications (UNIX, C, C++, Motif; later Linux port). Reached Principal Engineer.
- Subsequent roles in government and government-contractor environments (C/C++/UNIX, then modern web).
- Current role: Principal Consultant building Angular + Java/Spring MVC/Oracle reporting applications for the U.S. government.
- Ongoing personal project: Exploring Node.js, FastAPI, containerized microservices, PostgreSQL, and AI integration.

Open to interesting conversations about systems, enterprise software, or modern full-stack work.
