# 🥑 Time Series Forecasting - Avocado Prices 📈

This project applies **Facebook Prophet** to perform **Time Series Forecasting (TSF)** on avocado price data in the US.

## 📁 Dataset

- **Source**: [Kaggle - Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)
- The dataset contains historical avocado prices across multiple regions in the US from 2015 to 2018.

## 🛠️ Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from prophet import Prophet
```

ذ
ذ
## 📈 Steps Involved

### 1. 🗂️ Data Loading & Inspection
- Loaded the dataset using `pandas.read_csv()`
- Checked data structure with `data.head()` and `data.info()`

### 2. 🔍 Exploratory Data Analysis (EDA)
- Visualized avocado prices over time using `matplotlib`
- Identified trends, fluctuations, and potential seasonality

### 📌 Workflow

- **Load & Explore Data**
- **Preprocessing**
- **Model Building with Prophet**
- **Forecasting Future Prices**
- **Visualization**

---

### 📈 Output

- Forecasted avocado prices for a specified future period.
- Trend components (yearly, weekly seasonality, etc.).

---

## 🚗 Case Study 2: Forecasting Miles Traveled (with LSTM)

### 📁 Dataset

- **Source**: [Kaggle - Miles Travelled](https://www.kaggle.com/datasets/baghern/miles-dataset)
- **Description**: Monthly miles driven in the US — good for modeling long-term travel trends.

---


