# Responsible AI Eval Harness

A lightweight Python harness for evaluating AI prompts and responses against enterprise responsible AI policies.

## Why This Project Matters

This project supports roles requiring:

- AI governance
- Responsible AI practices
- Prompt engineering
- Evaluation automation
- Security controls
- Enterprise reporting

## What It Checks

- Sensitive data exposure
- Prompt injection patterns
- Missing grounding or citations
- High-risk unsupported advice
- Audit metadata completeness

## Quick Start

```powershell
python -m venv .venv
. .venv/Scripts/Activate.ps1
pip install -e ".[dev]"
pytest
python -m responsible_ai_eval.evaluate
```

## Portfolio Talking Point

This project demonstrates that I treat AI quality, safety, and governance as testable engineering concerns instead of after-the-fact documentation.

