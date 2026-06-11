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
bash scripts/build_databases.sh    # EEH (5 datasets)
bash scripts/build_expr.sh         # CSM (Astock only)
```

## Evaluate

```bash
bash scripts/eval.sh               # inference on 128 held-out catalysts per dataset
bash scripts/get_score.sh          # Acc / MCC / F1
```
