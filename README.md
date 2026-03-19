# E-commerce Churn Agent Benchmark

This repository contains three completed Jupyter notebooks for the same churn-prediction workflow, each produced with a different coding agent.

## Repository Contents

- `codex.ipynb`  
  End-to-end churn pipeline generated and executed with Codex.

- `claude_agent_task1_ecommerce_churn.ipynb`  
  Agent-based churn workflow generated and executed with Claude.

- `ecommerce_churn_Antigravity.ipynb`  
  Agent-based churn workflow generated and executed with Antigravity.

- `ecommerce_customer_churn_dataset.csv`  
  Original dataset used by all notebooks (expected in repository root).

- `prompt+Success Criteria.pdf`  
  Prompt protocol and scoring criteria.

- `MSIN0097_ Predictive Analytics 25-26 Group Coursework.pdf`  
  Coursework brief.

## Environment Setup

1. Create and activate a virtual environment.

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Start Jupyter.

```bash
jupyter lab
```

## Running the Notebooks

- Keep `ecommerce_customer_churn_dataset.csv` in the repository root.
- Open any notebook in JupyterLab and run cells top-to-bottom.
- If the dataset file name/path is different, update the `pd.read_csv(...)` path in the first data-ingestion cell.

## Notes

- A fixed random seed (`random_state=42`) is used in the benchmark workflow for reproducibility.
- Train/test split and evaluation are handled inside each notebook.
