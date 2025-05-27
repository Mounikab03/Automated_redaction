# Automated_redaction
PATEGAN-Project

# REDACT: Automated Redaction with Encoder + PATE-GAN

**REDACT** is an AI-powered web app that automatically redacts personally identifiable information (PII) from PDF text using a combination of a custom encoder model, pre-trained Hugging Face transformers, and privacy-preserving techniques via PATE-GAN.

---

## Overview

"REDACT" addresses the critical need for protecting sensitive data in PDF documents by offering a machine learning-based solution designed for intelligent redaction. Users can choose between two powerful models depending on their redaction needs:

- **NER BERT-Based Model**  
  Leverages Named Entity Recognition (NER) to identify sensitive data and replace it with a placeholder like `"******"`. Ideal for users who want to preserve the original document’s structure while obscuring sensitive content.

- **PATE-GAN Model**  
  Uses privacy-preserving GAN techniques to replace PII with contextually appropriate, realistic synthetic data. This ensures anonymization while maintaining the usability of the redacted document for analysis or collaboration.

---

## Features

- Upload PDF/WORD/CSV/TXT format files and redact them instantly.
- Choose between structure-preserving or synthetic data redaction.
- Download the redacted file effortlessly.
- Intuitive, user-friendly interface built with Streamlit.

---

## Technologies used

- **Python**
- **DeBERTa model** (via Hugging Face)
- **PATE-GAN**
- **TensorFlow**
- **PyPDF2**
- **Streamlit** (UI)
- **NumPy & Pandas**
- **Scikit-learn**
- **XGBoost**

---

## 📁 Project Structure

