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

![Hero Banner](assets/images/01_hero_banner.png)
![Architecture Diagram](assets/images/02_architecture_diagram.png)
![Research Flow](assets/images/03_research_flow.png)
![CLI Terminal](assets/images/04_cli_terminal.png)
![Provider Logos](assets/images/07_provider_logos.png)

See plan/ResearchPilot_Documentation_Bundle for full docs.
