# SatRoute

Backend (Person 1): FastAPI + WebSocket simulator.

## Run the backend
cd backend
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
uvicorn app.main:app --port 8000

WebSocket: ws://localhost:8000/ws
Contract: backend/app/schemas.py, docs/sample_frame.json, docs/CONTRACT_CHANGES.md
Note: ground elevation mask is 10 deg (SPEC says 25), so there are more ground links.
