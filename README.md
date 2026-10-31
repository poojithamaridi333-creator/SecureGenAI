# SecureGenAI
Privacy-Aware Intelligent Content Transformation & Cyber Threat Communication Platform.

## Run
Backend:
```bash
cd backend
python -m venv .venv
# Windows: .venv\Scripts\activate
# Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```
Frontend:
```bash
cd frontend
npm install
npm run dev
```
Open http://localhost:5173. API docs: http://127.0.0.1:8000/docs

## Tests
`cd backend && pytest`

This is a working educational prototype using synthetic data and local rule-based/NLP-style analysis. It does not require a paid AI API.
