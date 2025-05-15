# app_for_practice

![Images Build](https://github.com/etoosamoe/eto-app/actions/workflows/build.yml/badge.svg)

Simple application to train some programming and DevOps skills. It contains:
- Backend API (Python, FastAPI, SQLAlchemy, Pydantic)
- Frontend (NodeJS, React)
- Database (default - local SQLite file)

## Backend

Base API CRUD Python application, working with fastapi, sqlalchemy, pydantic.

By default works with SQLite file-based database stored in the container — all data will be deleted after restart.

# Frontend

Frontend works with NodeJS and uses React. It makes requests to backend API to get some data about servers.
