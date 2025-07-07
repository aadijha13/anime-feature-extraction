# 🎌 Anime Feature Extraction Project

This notebook performs **feature extraction** on an anime dataset using **Python, Pandas, and Scikit-learn**. The focus is on processing the `genre` column which contains multiple genres in a single string.

## 📌 Key Steps:

- Loaded anime dataset using pandas
- Cleaned missing data (e.g., missing genres)
- Dropped unnecessary columns (`licensors`, `producers`, etc.)
- Used `MultiLabelBinarizer` to convert multi-genre data into binary columns
- Combined genre features into the main dataframe for future ML/EDA tasks

## 🛠️ Tools & Libraries:
- Python
- Pandas
- NumPy
- scikit-learn (`MultiLabelBinarizer`)

## 📁 Files Included:
- `FeatureExtraction.ipynb` → The main notebook
- `anime.csv` → Dataset used (make sure it's safe/public to share)

---


