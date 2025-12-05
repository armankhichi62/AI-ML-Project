# Fraud Detection Streamlit App

Files:
- `app.py`: Streamlit app (entrypoint)
- `model.keras`, `scaler.pkl`, `encoders.pkl`, `features.pkl`, `threshold.pkl`: model + preprocessors

## Run locally
1. pip install -r requirements.txt
2. streamlit run app.py

## Deploy
Push repository to GitHub and deploy to Streamlit Community Cloud (Create app -> choose repo -> set entrypoint to `app.py`). See Streamlit docs: https://docs.streamlit.io. 
