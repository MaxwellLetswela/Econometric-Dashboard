SA Trending Markets — Streamlit Demo (Technology & Energy)
This Streamlit app is a synthetic demo of BN Analytics' "Pulse Board" showing trending KPIs for Technology and Energy sectors. It is designed to be embedded inside the BN Analytics website via an iframe.

Files
market_pulse.py — Streamlit app
requirements.txt — Python deps
Run locally
Create and activate a virtualenv
pip install -r requirements.txt
streamlit run market_pulse.py
Deploy to Streamlit Cloud
Push this repo to GitHub (repo name bn-pulse-board recommended).
Go to https://share.streamlit.io and sign in with GitHub.
Click "New app", select your repo, branch main, and main file market_pulse.py.
Deploy — Streamlit Cloud will give you a public URL like: https://bn-pulse-board-YOURNAME.streamlit.app
Embedding
Use the embed-snippet.html from this package. It includes an auto-resize script so the iframe adapts to the Streamlit content.

Note
This is synthetic demo data for layout and integration testing. Replace the generation logic with real API calls when ready.


Disclaimer: This is a conceptual project composed with real and synthetic data for demonstration purpose only. Names of companies are fictitious and do not represent or alias any legally registered entity within the republic or abroad. If my work impress you, reach-out for my services, I'm available for consulting and employment.
Last Updated: August 2024
Version: 1.0
