# Audio Visualizer Database (PostgreSQL)

This container provides the PostgreSQL database for the application.

Environment variables expected by the backend:
- POSTGRES_URL (preferred), or the parts:
  - POSTGRES_USER
  - POSTGRES_PASSWORD
  - POSTGRES_DB
  - POSTGRES_HOST
  - POSTGRES_PORT

The backend initializes the required tables on startup:
- users
- visualizer_configs
