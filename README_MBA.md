
# Market Basket Analysis (MBA) – Product Recommendations

**How to run**
1. Open `Market_Basket_Analysis.ipynb`.
2. By default it loads `/mnt/data/sample_transactions.csv`.
3. Replace `DATA_PATH` at the top of the notebook to point to your own CSV.
4. Run all cells. Outputs (frequent itemsets & rules) will be saved to `/mnt/data/`.

**Dataset format**
- Columns required: `TransactionID`, `Item`. One row per (transaction, item).
- If your dataset uses different names, rename columns in the notebook (example provided).

**Deliverables**
- `mba_frequent_itemsets.csv` – frequent itemsets with support
- `mba_rules.csv` – association rules with support, confidence, lift
- Visualizations: support top-k itemsets, support vs confidence, confidence vs lift

**Resume bullet**
> Market Basket Analysis – Implemented Apriori in Python to mine frequent itemsets and generate association rules from retail transactions. Built matplotlib visualizations and exported rules, uncovering product bundles that inform cross‑sell strategies.
