# Food Delivery Data Integration

Data integration pipeline consolidating transactional, user, and restaurant data into a unified analytical dataset.

Sources include CSV, JSON, and SQL inputs. Restaurant data is executed via SQLite and merged using left joins to preserve all order records.

Primary output:
- final_food_delivery_dataset.csv

Implementation:
- Python (Pandas)
- SQLite
- Jupyter Notebook
