# TIER

## Install

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=...
export OPENAI_BASE_URL=...
export LLM_MODEL=gpt-4o-mini
```

## Build

```bash
bash scripts/build_databases.sh
bash scripts/build_expr.sh
```

## Evaluate

```bash
bash scripts/eval.sh
bash scripts/get_score.sh
```
