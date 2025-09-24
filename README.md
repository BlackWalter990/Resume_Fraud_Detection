# CV Fraud Detection and Skill Ranking System

This project combines fraud detection and skill ranking for profiles using a single input CSV file. It performs the following tasks:

- **Fraud Detection:** Identifies fraudulent profiles based on risk factors using a BiLSTM Autoencoder.
- **Skill Extraction and Ranking:** Extracts, normalizes, and ranks skills from profile data. Fraudulent profiles have their skill scores set to zero.
- Read the Report file for better understanding.

## Requirements

- **Python** 3.6 or later
- **Libraries:**

  To install the required libraries, run:
  ```bash
  pip install pandas numpy scikit-learn tensorflow matplotlib networkx textblob spacy seaborn python-louvain
  python -m spacy download en_core_web_sm

