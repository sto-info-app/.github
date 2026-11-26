# STO Info App

**STO Info App** is a free, community-driven web application that provides structured reference data and tooling for *Star Trek Online*.

The project focuses on allowing users to record details about their accounts, characters, fleets and more. It is not a general-purpose wiki.

It is built as a modern web application with a clear separation between frontend, backend, and supporting services.

## Project status

This is an actively developed project. Features, data coverage, and internal tooling will evolve over time as the application matures.

## Live availability

| Service | Status | Uptime (30 days) |
|---|---|---|
| Backend APIs | [![Uptime status](https://img.shields.io/uptimerobot/status/m802169058-d230a9a973c1eef1de28ed63.svg)](https://status.startrekonline.info/) | [![Uptime 30 days](https://img.shields.io/uptimerobot/ratio/m802169058-d230a9a973c1eef1de28ed63.svg)](https://status.startrekonline.info/) |
| Frontend | [![Uptime status](https://img.shields.io/uptimerobot/status/m802169070-054df85f9c4a66231e51da43.svg)](https://status.startrekonline.info/) | [![Uptime 30 days](https://img.shields.io/uptimerobot/ratio/m802169070-054df85f9c4a66231e51da43.svg)](https://status.startrekonline.info/) |

## Repositories

| Repository | What it is | Build |
|---|---|---|
| [sto-info-frontend](https://github.com/sto-info-app/sto-info-frontend) | The website (Angular) | [![Lint and Test](https://github.com/sto-info-app/sto-info-frontend/actions/workflows/lint-test.yml/badge.svg?branch=development)](https://github.com/sto-info-app/sto-info-frontend/actions/workflows/lint-test.yml) |
| [sto-info-backend](https://github.com/sto-info-app/sto-info-backend) | The API (NestJS) | [![Lint and Test](https://github.com/sto-info-app/sto-info-backend/actions/workflows/lint-test.yml/badge.svg?branch=development)](https://github.com/sto-info-app/sto-info-backend/actions/workflows/lint-test.yml) |
| [sto-info-file-scan-worker](https://github.com/sto-info-app/sto-info-file-scan-worker) | The background worker that virus-scans uploaded files before the site uses them (NestJS) | [![Lint and Test](https://github.com/sto-info-app/sto-info-file-scan-worker/actions/workflows/lint-test.yml/badge.svg?branch=development)](https://github.com/sto-info-app/sto-info-file-scan-worker/actions/workflows/lint-test.yml) |
| [sto-info-wiki](https://github.com/sto-info-app/sto-info-wiki) | The central wiki: architecture, roadmap and contributor onboarding | |

Some supporting tooling is kept in private repositories.

Each repository contains its own README with setup and development details.

## Contributing

Contributions are welcome, including code, documentation, testing, and general review.  
Please see [CONTRIBUTING.md](https://github.com/sto-info-app/.github/blob/main/CONTRIBUTING.md) for guidance on how to get involved.

## Disclaimer

This project is **not affiliated with, endorsed by, or associated with** Cryptic Studios, Paramount, CBS, or any related entities.  
*Star Trek* and *Star Trek Online* are trademarks of their respective owners.

The application is provided free of charge and without warranty. Use is at your own risk.
