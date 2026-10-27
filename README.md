- Superset 6.1.0 with Python 3.10.21
- PostgreSQL, Redis, and a background worker
- PostgreSQL and MySQL drivers
- Local sample data and a starter dashboard
- Generated login credentials and startup instructions
For Intel/AMD 64-bit computers, including Windows with Docker configured for Linux containers. Docker must already be installed; host Python is unnecessary.

Extract the ZIP, open a terminal inside superset-offline, and run:
docker load -i images/superset-images.tar.gz
docker compose up -d --pull never

Open http://localhost:8088. Your credentials are in LOGIN.txt—no configuration editing is required.

Validation: Checksums, local initialization, login, dashboard registration, and a chart query passed. Full Docker startup and browser rendering were not tested here. Optional reports, external map tiles, and additional database drivers need separate preparation.
