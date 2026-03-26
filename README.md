# Crypto Market Dashboard

Streamlit dashboard that pulls historical crypto prices from the CoinGecko API and displays:
- Time series line chart
- KPI metrics
- Processed data table

## Local Run

1. Create and activate a virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the app:

```bash
streamlit run app.py
```

## Deploy To Streamlit Community Cloud

1. Push this repository to GitHub (public repo recommended).
2. Open https://share.streamlit.io/deploy.
3. Click New app.
4. Choose your GitHub repository and branch.
5. Set Main file path to `app.py`.
6. Click Deploy.

## Notes

- Dependencies are declared in both `pyproject.toml` and `requirements.txt` for maximum compatibility with cloud build environments.
- The app file is at the repository root, which is the expected layout for Streamlit Cloud.