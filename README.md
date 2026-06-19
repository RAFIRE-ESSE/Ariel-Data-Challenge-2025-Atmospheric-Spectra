# 🔭 Ariel Data Challenge 2025 — Atmospheric Spectra

![Astrophysics](https://img.shields.io/badge/-Astrophysics-1a1b26?style=flat-square&logoColor=c0caf5) ![Signal Processing](https://img.shields.io/badge/-Signal%20Processing-1a1b26?style=flat-square&logoColor=c0caf5) ![Regression](https://img.shields.io/badge/-Regression-1a1b26?style=flat-square&logoColor=c0caf5) ![Deep Learning](https://img.shields.io/badge/-Deep%20Learning-1a1b26?style=flat-square&logoColor=c0caf5)

![Banner](./banner.png)

> [!IMPORTANT]
> **Host:** `ESA Ariel Mission`  
> **Platform Link:** [Kaggle Competition](https://www.kaggle.com/competitions/ariel-data-challenge-2025)  
> **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/ariel-data-challenge-2025/data)  
> **Domain:** `Astrophysics & Signal Processing`

## 📖 Overview

Here are my notebooks for the Ariel Data Challenge 2025. I worked on extracting exoplanet atmospheric spectra from simulated telescope data. It was super cool bridging machine learning with astrophysics!

## ⚙️ Standard Pipeline Workflow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'background': '#0f0f12', 'primaryColor': '#1a1b26', 'edgeLabelBackground':'#11111b', 'tertiaryColor': '#1a1b26'}}}%%
flowchart LR
    A[Data Gathering] --> B[Preprocessing & EDA]
    B --> C[Model Training]
    C --> D[Inference & Submission]
    style A fill:#1e1e24,stroke:#7aa2f7,stroke-width:2px,color:#c0caf5
    style B fill:#1e1e24,stroke:#bb9af7,stroke-width:2px,color:#c0caf5
    style C fill:#1e1e24,stroke:#f7768e,stroke-width:2px,color:#c0caf5
    style D fill:#1e1e24,stroke:#9ece6a,stroke-width:2px,color:#c0caf5
```

## 🗂️ Notebook Architecture & Inventory

### 📂 Preprocessing & EDA
*Data cleaning, feature engineering, and exploratory data analysis.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📄 [EDA_and_Visualization](./Preprocessing%20%26%20EDA/EDA_and_Visualization.ipynb) | Single Notebook | `v1` | `257 KB` | `Pandas Data Prep` |
| 📁 **EDA_and_Visualization_2** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/EDA_and_Visualization_2/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/EDA_and_Visualization_2/v2.ipynb) | `Avg 37107 KB` | `Pandas Data Prep` |
| 📁 **EDA_and_Visualization_3** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/EDA_and_Visualization_3/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/EDA_and_Visualization_3/v2.ipynb), [v3](./Preprocessing%20%26%20EDA/EDA_and_Visualization_3/v3.ipynb) | `Avg 219 KB` | `Pandas Data Prep` |
| 📁 **EDA_and_Visualization_4** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/EDA_and_Visualization_4/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/EDA_and_Visualization_4/v2.ipynb), [v3](./Preprocessing%20%26%20EDA/EDA_and_Visualization_4/v3.ipynb) | `Avg 61204 KB` | `Pandas Data Prep` |
| 📁 **LSTM_EDA_and_Visualization** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/LSTM_EDA_and_Visualization/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/LSTM_EDA_and_Visualization/v2.ipynb) | `Avg 169 KB` | `PyTorch, OpenCV` |

### 📂 Inference & Submission
*Prediction pipeline and Kaggle submission file generation.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **CatBoost_Inference** | Multi-Version Script | [v1](./Inference%20%26%20Submission/CatBoost_Inference/v1.ipynb), [v2](./Inference%20%26%20Submission/CatBoost_Inference/v2.ipynb), [v3](./Inference%20%26%20Submission/CatBoost_Inference/v3.ipynb), [v4](./Inference%20%26%20Submission/CatBoost_Inference/v4.ipynb) | `Avg 110 KB` | `CatBoost, PyTorch` |
| 📄 [Inference](./Inference%20%26%20Submission/Inference.ipynb) | Single Notebook | `v1` | `54 KB` | `PyTorch` |
| 📁 **Inference_2** | Multi-Version Script | [v1](./Inference%20%26%20Submission/Inference_2/v1.ipynb), [v2](./Inference%20%26%20Submission/Inference_2/v2.ipynb) | `Avg 115 KB` | `Pandas Data Prep` |
| 📁 **Inference_3** | Multi-Version Script | [v1](./Inference%20%26%20Submission/Inference_3/v1.ipynb), [v2](./Inference%20%26%20Submission/Inference_3/v2.ipynb), [v3](./Inference%20%26%20Submission/Inference_3/v3.ipynb), [v4](./Inference%20%26%20Submission/Inference_3/v4.ipynb) | `Avg 97 KB` | `Pandas Data Prep` |
| 📁 **LightGBM_LightGBM_CatBoost_Inference** | Multi-Version Script | [v1](./Inference%20%26%20Submission/LightGBM_LightGBM_CatBoost_Inference/v1.ipynb), [v2](./Inference%20%26%20Submission/LightGBM_LightGBM_CatBoost_Inference/v2.ipynb) | `Avg 100 KB` | `LightGBM, CatBoost` |
| 📄 [LightGBM_LightGBM_XGBoost_XGBoost_Inference](./Inference%20%26%20Submission/LightGBM_LightGBM_XGBoost_XGBoost_Inference.ipynb) | Single Notebook | `v1` | `15 KB` | `LightGBM, XGBoost, Scikit-Learn Split` |

### 📂 Models & Utilities
*Shared model architectures, helper functions, and custom loss functions.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **LSTM_Utility** | Multi-Version Script | [v1](./Models%20%26%20Utilities/LSTM_Utility/v1.ipynb), [v2](./Models%20%26%20Utilities/LSTM_Utility/v2.ipynb), [v3](./Models%20%26%20Utilities/LSTM_Utility/v3.ipynb), [v4](./Models%20%26%20Utilities/LSTM_Utility/v4.ipynb), [v5](./Models%20%26%20Utilities/LSTM_Utility/v5.ipynb) | `Avg 59 KB` | `PyTorch, OpenCV` |

---

## 🚀 Navigation & Usage Guidelines

> [!TIP]
> 1. **EDA & Preprocessing**: Verify data loaders, actigraphy or DICOM image transformations before model training.
> 2. **Training & Optimization**: Check model definition parameters and training logs to reproduce network weights.
> 3. **Inference & Post-Processing**: Run final pipelines to verify predictions and check submission formats.


---

> *"The oldest and strongest emotion of mankind is fear of the unknown deep space."*
>
> — **Vigneshwaran S**
