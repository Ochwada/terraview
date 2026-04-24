# terraview

A web app for exploring Sentinel-2 satellite imagery over time.
Pick a location, see recent cloud-free imagery, compute NDVI, compare dates.

## Stack

- **Backend:** Django 5 + Django REST Framework + GeoDjango (PostGIS)
- **Frontend:** Next.js 15 (App Router) + TypeScript + Tailwind + MapLibre GL
- **Database:** PostgreSQL 16 + PostGIS 3 (via Docker)
- **Async jobs:** Celery + Redis (later phases)
- **Imagery source:** Sentinel-2 L2A via AWS Open Data

## Status

🚧 In development — Phase 0 (project scaffolding).

## Repo layout
"

terraview/
├── backend/     Django project
├── frontend/    Next.js project
├── docker/      docker-compose for Postgres/PostGIS
└── docs/        architecture notes, decisions

## Getting started

See `docs/SETUP.md` (coming soon).
