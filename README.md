# boutique-loadgenerator

Runs Locust-based load and performance tests.

## Overview

- **Type:** Python utility
- **Stack:** Python, Locust, Docker

## Flow

```text
Client / service → Controller → Business logic → Database / events / downstream services
```

## Configuration

```text
FRONTEND_ADDR
RATE
USERS
```

## Run

```bash
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
```

## Docker

```bash
docker build -t boutique-loadgenerator:local .
```

## CI/CD

This repository is built and deployed independently through its own GitHub Actions workflow.
