# 🏠 Real Estate Price Predictor

*A practical, end-to-end machine learning project predicting housing prices — built while working through “Hands-On Machine Learning” by Aurélien Géron.*

[![Python](https://img.shields.io/badge/python-3.10+-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)]()

---

## 📌 Project Summary

This repository contains a complete, reproducible end-to-end workflow for predicting real-estate prices (based on the California housing dataset).  
The notebook demonstrates:

- Data exploration and visualization  
- Feature engineering (including custom transformers)  
- Clean preprocessing with `ColumnTransformer` + `Pipeline`  
- Model training, cross-validation, and hyperparameter search  
- Model evaluation (RMSE/MAE) and error analysis  
- Exporting the final model for inference  

> 🧭 This project is also referenced from the main **Hands-On Machine Learning Practice** collection.

---

## 🔗 Quick Links

- 📓 **Open the main notebook (recommended):**  
  [Open Notebook in this repo](./notebook/real_estate_price_predictor.ipynb)

- ☁️ **Open in Google Colab:**  
  <a href="https://colab.research.google.com/github/umbutun/real-estate-price-predictor/blob/main/notebook/real_estate_price_predictor.ipynb" target="_blank">Open in Colab</a>

---

## 📸 Preview

*(Replace `assets/preview.png` with your own visual for better presentation.)*

![Project Preview](./assets/preview.png)  
*Figure: Example — feature correlations and model prediction vs actual plot.*

---

## 🔧 Setup & Usage

### 1️⃣ Clone Repo
```bash
git clone https://github.com/umbutun/real-estate-price-predictor.git
cd real-estate-price-predictor
```
### 2️⃣ Install Dependencies

Using pip:
```bash
pip install -r requirements.txt
```
Or using conda:
```bash
conda env create -f environment.yml
conda activate real-estate-ml
```
### 3️⃣ Launch the Notebook
```bash
jupyter lab
# or
jupyter notebook
# then open notebook/real_estate_price_predictor.ipynb
```

> 💡 You can also open it directly in **Google Colab** via the link above, no local setup required.

---

## 📁 Repo Structure

```plaintext
real-estate-price-predictor/
├── notebook/
│   └── real_estate_price_predictor.ipynb
├── assets/
│   └── preview.png
├── requirements.txt
├── environment.yml
├── LICENSE
└── README.md
```
---

## ⚙️ Notes About Data & Reproducibility

- The notebook downloads the California housing dataset automatically (no large datasets stored in this repo).  
- Use `requirements.txt` or `environment.yml` to reproduce the environment exactly.  
- Random seeds are fixed for consistent results across runs.

---

## 🧾 Reuse / Citation

If you reuse this project or its code in published work, please cite:

> **Umut Bütün** — *Real Estate Price Predictor* — [https://github.com/umbutun/real-estate-price-predictor](https://github.com/umbutun/real-estate-price-predictor)

---

## 🤝 Contributing

Contributions and suggestions are welcome!  
If you’d like to contribute:
1. Open an issue describing the change or enhancement, or  
2. Fork the repo and submit a pull request.

---

## 🧑‍💻 Author

**Umut Bütün**  
Machine Learning Enthusiast • Python Developer  
🔗 [https://github.com/umbutun](https://github.com/umbutun)

---

## 📜 License

This project is licensed under the **MIT License**.  
If you haven’t yet added one, you can add it from the GitHub web UI:

1. Go to your repo’s main page  
2. Click **Add file → Create new file**  
3. Name it `LICENSE`  
4. On the right, click **Choose a license template** → select **MIT License**  
5. Commit the file

