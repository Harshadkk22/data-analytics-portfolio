
# Steel Pipe Inventory & Pricing Optimizer

**Stack:** Python (Pandas, Matplotlib), CSV datasets (SQL-friendly)

## What this shows
- Inventory master with cost/price attributes.
- 18-month sales history, ABC analysis, and a price elasticity simulation.
- Visual showing ABC class distribution.

## How to run
1. `pip install pandas numpy matplotlib`.
2. Run: `python scripts/analysis.py` (regenerates outputs from data).

## Files
- `data/inventory_master.csv`, `data/sales_history.csv`
- `outputs/abc_classification.csv`, `outputs/price_simulation.csv`
- `outputs/abc_counts.png`
- `scripts/analysis.py`

## Notes
- Price simulation uses a simple linear elasticity around current price for portfolio demonstration.
- Replace `inventory_master.csv` and `sales_history.csv` with your data to reuse the pipeline.
