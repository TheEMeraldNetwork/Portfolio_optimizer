# Portfolio Optimizer — Pages

This repo hosts the published outputs (HTML/CSV) from the unified runner.

## Live site
- Main dashboard: `https://theemeraldnetwork.github.io/Portfolio_optimizer/`
- Macro quadrants: `https://theemeraldnetwork.github.io/Portfolio_optimizer/macro_quadrants.html`
- Buffett quadrants: `https://theemeraldnetwork.github.io/Portfolio_optimizer/buffett_quadrant.html`

## Local Flask plots (clean redesign)
If you want to serve a cleaner version locally from the codebase:

```bash
# In sentiment_analysis workspace
pip install flask plotly
python -m d_datalakeX.src.cli serve-quadrants --port 5050
# open http://127.0.0.1:5050
```

## Contents
- `dashboard.html`, `macro_quadrants.html`, `buffett_quadrant.html`
- `quarterly_matrix.csv`
- `trades_bayes.csv`

