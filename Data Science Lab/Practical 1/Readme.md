# 🧠 Data Science Practical 1 — Titanic: Machine Learning From Disaster

## 📘 Project Description
This project explores the famous **Titanic: Machine Learning from Disaster** dataset as part of the **COMP5122M Data Science 2024–2025** practical exercise.  
The goal is to perform **exploratory data analysis (EDA)** on the dataset to uncover insights about survival patterns among passengers.  
The dataset includes demographic and travel details such as age, gender, passenger class, fare, and family relationships aboard.  

Through Python (Pandas, NumPy, Matplotlib) or Tableau, this analysis answers guided questions regarding the dataset, such as:  
- What were the ages of the youngest and oldest passengers?  
- Were certain groups more likely to survive?  
- How were titles distributed among passengers?  
- Were there any children under 10 traveling without parents?  

---

## 🧭 Table of Contents
1. [Project Description](#-project-description)
2. [Installation and Setup](#-installation-and-setup)
3. [How to Run](#-how-to-run)
4. [Usage Guide](#-usage-guide)
5. [Credits](#-credits)
6. [License](#-license)
7. [Contributing](#-contributing)
8. [Tests](#-tests)

---

## ⚙️ Installation and Setup

### Requirements
- Python 3.8 or higher  
- Jupyter Notebook or Google Colab  
- Required Libraries:
  ```bash
  pip install pandas numpy matplotlib

Alternatively, you can use Tableau Desktop or Tableau Public for visualization-based analysis.
1. Setup Steps
2. Clone or download this repository.
3. Place your train.csv dataset inside the project folder.
4. Open Titanic_Analysis.ipynb in Jupyter Notebook or Google Colab.
5. Run the code cells sequentially to reproduce the analysis.
---
# ▶️ How to Run:

In your notebook or terminal:
```python
import pandas as pd
df_titanic = pd.read_csv("train.csv")
df_titanic.info()
```
Run each code block to answer the practical questions (1–15), such as displaying rows, checking missing values, calculating averages, and extracting insights.

If using Tableau:
- Import train.csv using the CSV Connector.
- Create visualizations to explore survival rates, class distribution, and demographic effects.
---
# 🧩 How to Use the Project

Each question from the assignment is implemented in a separate cell with a short explanation.
You can modify or extend the notebook to perform deeper analysis or build predictive models.

Example analyses include:

1. Youngest and oldest survivors
2. Most common passenger titles
3. Average fares by class or gender
4. Detecting missing values and handling them
---
# 👥 Credits:

Lecturer: Dr. Duygu Sarikaya  
Course: COMP5122M — Data Science (University of Leeds)  
Dataset: [Titanic: Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/c/titanic)
---
# ⚖️ License:

This project is licensed under the MIT License.
You are free to use, modify, and distribute this project with attribution.
---
# 🤝 How to Contribute

Contributions are welcome!

1. Fork the repository.
2. Create a new branch for your feature `git checkout -b feature-name`
3. Commit your changes `git commit -m "Added new feature"`
4. Push the branch `git push origin feature-name`
5. Submit a Pull Request.
---
# 🧪 Tests

1. To verify the functionality of your analysis:
2. Check that the dataset loads correctly with `df_titanic.info()`.
3. Validate that there are no missing values in required columns after preprocessing.
4. Confirm all outputs (ages, averages, and counts) match the expected results.
5. Run assertions in your notebook such as:
