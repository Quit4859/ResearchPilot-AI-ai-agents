# ResearchPilot AI

Evidence-oriented web research assistant. FastAPI backend + Streamlit frontend.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
```

## Run

Start the backend:

```bash
uvicorn backend.main:app --reload
```

Start the frontend:

```bash
streamlit run app.py
```

## CLI

```bash
python cli.py --question "your question"
```

## Tests

```bash
pytest
```

## Assets

Project images are stored in `assets/images/`.

<img src="assets/images/01_hero_banner.png" alt="Hero Banner" style="border:1px solid #ccc; border-radius:8px; max-width:100%;">
<img src="assets/images/02_architecture_diagram.png" alt="Architecture Diagram" style="border:1px solid #ccc; border-radius:8px; max-width:100%;">
<img src="assets/images/03_research_flow.png" alt="Research Flow" style="border:1px solid #ccc; border-radius:8px; max-width:100%;">
<img src="assets/images/04_cli_terminal.png" alt="CLI Terminal" style="border:1px solid #ccc; border-radius:8px; max-width:100%;">
<img src="assets/images/07_provider_logos.png" alt="Provider Logos" style="border:1px solid #ccc; border-radius:8px; max-width:100%;">

