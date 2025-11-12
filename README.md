# LoopBack Cloud Demo

## Overview
A minimal **LoopBack 4** API that demonstrates **cloud-ready configuration**:
- Uses a single `DATABASE_URL` (12-factor style)
- Works with a “remote-like” PostgreSQL via **docker-compose**
- Same CRUD endpoints as Week 1, but with cloud-friendly env setup

## Why this exists (Week 2)
This repo proves I understand **cloud concepts**:
- Separate config via env vars
- One URL for DB in production
- Migration step before start

## Quick Start

### 1) Install & run Postgres (docker)
```bash
docker compose up -d
