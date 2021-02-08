# jupyter-notebooks
Small functionalities and Analyses in Jupyter

**Skill Extraction from Resume:** This uses a spacy phrase matcher to match the required skills from text. Text is extracted from PDF/DOC files using textract.

**Times series anomaly detection:** A simple model using fbprohet ts forecasting model to reconstruct the ts data with an upper and lower margin. Any point from the original which falls outside the bounds of reconstructed data is treated as anomaly.
