# your-project

A minimal Python package scaffold using the `src/` layout.

- Library code in `src/your_project/`
- Handy scripts in `scripts/`
- Installed locally in **editable mode** via `requirements.txt` (contains `-e .`)

## Requirements
- Python 3.11+ (3.12/3.13 OK)

## Setup

```bash
# from repo root
python -m venv .venv
```

**Windows (PowerShell):**
```powershell
. .\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**macOS/Linux:**
```bash
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

This installs the package in **editable** mode so changes under `src/your_project/` are picked up immediately.

## Quick check

Run the module:
```bash
python -m your_project
```

Run the smoke script:
```bash
python scripts/smoke_test.py
```

## Repo layout

```
your-project/
├─ src/
│  └─ your_project/
│     ├─ __init__.py
│     └─ __main__.py
├─ scripts/
│  └─ smoke_test.py
├─ .gitignore
├─ pyproject.toml
├─ requirements.txt
└─ README.md
```
