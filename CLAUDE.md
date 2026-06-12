# History Repeats

A web app that shows historical events that happened on today's date. Users visit the page and see a curated list of notable things that occurred on this day in history — battles, inventions, births, deaths, weird happenings, and more. The goal is to make history feel immediate and fun by connecting the past to today's calendar date.

## Tech Stack

- **Backend:** Python 3 + FastAPI
- **Frontend:** Vanilla JavaScript (no frameworks), HTML, CSS
- **Package management:** pip (backend), npm (frontend)

## Project Structure

```
history-repeats/
├── backend/          # FastAPI application
│   ├── main.py       # App entrypoint
│   └── requirements.txt
├── frontend/         # Static HTML/JS/CSS
│   ├── index.html
│   ├── js/
│   └── css/
└── CLAUDE.md
```

## Running Locally

```bash
# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
# Serve static files (or backend serves them)
```

## Conventions

- Backend API routes go under `/api/`
- Keep frontend simple — no build step, no bundler, just plain JS
- Use `fetch()` for API calls from the frontend
- Python formatting: follow PEP 8
- Prefer small, focused functions over large monoliths

## Testing

```bash
cd backend
pytest
```
