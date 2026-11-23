# agentic-design-patterns
This is to explain agentic design patterns

## Environment setup
# 1. Initialize a new project (creates pyproject.toml, .python-version, and .venv)
uv init

# 2. Add runtime and dev dependencies (automatically updates pyproject.toml & uv.lock)
uv add uv add langchain langchain-community langchain-openai langgraph

# 3. Check installed dependencies in virtual environment
uv pip list
uv tree

# 3. Run scripts or tools inside the managed environment without manual activation
uv run python main.py
uv run pytest

