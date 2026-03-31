# Project Name
Project details

## Dependency Management
This project uses [uv](https://docs.astral.sh/uv/guides/projects/) for dependency management. 
The `uv run` command eliminates the need to manually create and activate virtual environments (.venv) for projects, 
as uv automatically sets up the virtual environment and installs necessary dependencies on-the-fly.

## Development Optimizations
- Static type checking
  - mypy
- Linting
  - ruff
- Unit testing
  - pytest

mypy does not need to be installed locally since it is available as a 
[VSCode extension](https://marketplace.visualstudio.com/items?itemName=ms-python.mypy-type-checker).

## Getting Started

```bash
# 1. Sync dependencies
uv sync

# 2. Configure environment variables
cp .env.example .env

# 3. Run the project
uv run main.py
```