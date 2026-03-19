# LLM-Based Methods for Taxonomy Construction from Unstructured Text

This repository contains the implementation and experiments for my Master's thesis focused on **unsupervised taxonomy construction** using metadata and Large Language Models (LLMs).

---

## 📌 Overview

The goal of this work is to automatically generate hierarchical product taxonomies from unstructured product data.

The pipeline combines:

* Text preprocessing and metadata extraction
* Embedding generation
* Unsupervised clustering
* LLM-based category naming

---

## ⚙️ Methodology

The overall workflow:

```
Raw Product Data → Preprocessing → Embeddings → Clustering → Hierarchy Construction → LLM Naming
```

### Key Components

* **Embeddings**: Convert product descriptions into vector space
* **Clustering**: Group semantically similar products
* **Hierarchy Construction**: Build multi-level taxonomy
* **LLM Labeling**: Assign meaningful category names

---

## 📂 Repository Structure

```
.
├── Main_code/
│   ├── Final_code.ipynb          # Final implementation used in thesis
│
├── Experiments/
│   ├── experiment_1.ipynb       # Clustering experiments
│   ├── experiment_2.ipynb
│
├── figures/
│   ├── taxonomy_tree_figure.png
│   ├── cluster_purity_table.png
│
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The dataset used in this project is based on **Icecat product data**.

⚠️ Due to size limitations (~1.1 GB), the dataset is **not included in this repository**.

👉 You can access/download the dataset here:
**(https://data.dws.informatik.uni-mannheim.de/largescaleproductcorpus/categorization/)**

---

## 🚀 Running the Project

### 1. Clone the repository

```
git clone https://github.com/malisuyash/LLM_Product_Taxonomy_Construction.git
cd LLM_Product_Taxonomy_Construction
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the main notebook

Open:

```
Main_code/Final_code.ipynb
```

---

## ⚠️ Important Notes

### Large Notebook Rendering Issue

The file:

```
Main_code/Final_code.ipynb
```

may **not render properly on GitHub** due to its large size.

#### Solution:

* Download the notebook locally
* Open using:

  * Jupyter Notebook
  * JupyterLab
  * VS Code

---

### Large Files

The following are intentionally **excluded**:

* Raw dataset files (~1.1 GB)
* Intermediate large outputs

---

## 📈 Results

* Successfully generated hierarchical taxonomy
* Improved semantic grouping using embeddings
* LLM-based naming provided meaningful category labels



---

## 🎓 Thesis Reference

The implementation developed in this thesis is publicly available at:

https://github.com/malisuyash/LLM_Product_Taxonomy_Construction

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Sentence Transformers
* Clustering Algorithms (HDBSCAN, KMeans, etc.)
* Large Language Models (LLMs)

---
