# AI Usage Log — Lab 1

I used Claude (Anthropic) throughout this lab to help set up and debug my environment.

## What I asked
- How to complete the Lab 1 rubric using Python + uv instead of R, since I was originally
  planning to use Google Colab and it wasn't a good fit for the R/renv requirement.
- Step-by-step help setting up a GitHub repo, installing uv, and creating a working
  Python environment in VS Code on Windows.
- Debugging a "uv is not recognized" PATH error after installing uv with winget.
- Debugging file/folder confusion in VS Code (accidentally pasting terminal commands
  into a Python file, and figuring out how to move analyze.py into the src/ folder).
- A template for README.md and this AI_USAGE.md file.

## What I kept
- The overall plan to use Python + uv (conda/mamba felt like more setup for what I needed).
- The fix for the PATH issue: closing and reopening VS Code (and testing in a fresh
  PowerShell window first) rather than reinstalling uv.
- The README and AI_USAGE.md templates, edited to reflect my actual project and username.

## What I changed or verified myself
- I ran every command myself and checked the output against what was expected
  (e.g. confirming `uv run python src/analyze.py` gave the same stats table before
  and after deleting and rebuilding .venv with `uv sync`).
- I decided the folder structure and file placement myself once I understood the
  differences between terminal commands and file content.
