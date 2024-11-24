# {{project_name}}

{{project_description}}

## Setup

This project uses:
- `uv` for fast virtual environment management and package installation
- `poetry` for dependency management and running scripts

1. Install required tools if you haven't already:
```bash
pip install uv poetry
```

2. Create virtual environment:
```bash
uv venv
```

3. Activate the virtual environment:
```bash
# On Unix/macOS:
source .venv/bin/activate

# On Windows:
.venv\Scripts\activate
```

4. Install dependencies using Poetry:
```bash
poetry install
```

## Running the Project

After setup, you can run the project using:
```bash
poetry run run
```

Or activate the environment and run:
```bash
poetry run python main.py
```

# Made with Copier
[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier)
