# Swiss Road Traffic Accidents

This project explores Swiss road traffic accidents involving personal injury, using data published by the Swiss Federal Roads Office (ASTRA).

The notebook [`accidents.ipynb`](accidents.ipynb) downloads the CSV archive, loads it into Polars, and stores it as Parquet or Excel.

## Getting started

Create a Python 3.13 environment and install the notebook dependencies with [uv](https://docs.astral.sh/uv/):

```powershell
uv venv --python 3.13
uv pip install --python .venv\Scripts\python.exe jupyter polars requests xlsxwriter
```

Open the notebook in VS Code and select `.venv` as its kernel.

## Data source and interactive dashboard

- [ASTRA accident data on geo.admin.ch](https://data.geo.admin.ch/browser/index.html#/collections/ch.astra.unfaelle-personenschaeden_alle/items/unfaelle-personenschaeden_alle)
- [Accident dashboard](https://experience.arcgis.com/experience/322baf6359cc4e41bce89a037694e215)
