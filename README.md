# Inference Hypothesis Testing on Student Performance Factorial 📊

[](https://www.google.com/search?q=https://github.com/your-username/your-repo-name)
[](https://www.python.org/)
[](https://opensource.org/licenses/MIT)

-----

## 💡 Project Overview

This project uses **statistical inference** and **hypothesis testing** to analyze various factors influencing student academic performance. By applying different regression models and ANOVA techniques, we aim to determine which variables—both quantitative (e.g., hours studied) and categorical (e.g., parental involvement)—have a **statistically significant** impact on a student's `Exam_Score`.

The core goal is to move beyond simple correlation and use formal hypothesis tests to build predictive models and draw robust conclusions about the underlying data structure.

-----

## ✨ Key Analysis & Features

The project is structured around three main types of statistical analysis, each addressing a different aspect of the data:

1.  **Simple Linear Regression (`linear_regression.ipynb`):**

      * Tests the effect of a single quantitative predictor (e.g., `Hours_Studied`) on `Exam_Score`.
      * **Hypothesis:** Is the slope coefficient significantly different from zero?
      * (A line plot showing `Hours_Studied` vs. `Exam_Score` with a clear trend line.)

2.  **Multiple Linear Regression (`multiple_linear_regression.ipynb`):**

      * Models the relationship between `Exam_Score` and several predictors simultaneously (e.g., `Hours_Studied`, `Attendance`, `Previous_Scores`).
      * **Hypothesis:** Which predictors remain significant after controlling for the effects of others?

3.  **Factorial Analysis (ANOVA) (`test.ipynb`):**

      * Uses the General Linear Model (via OLS) and Type II ANOVA to assess the impact of multiple **categorical factors** (e.g., `Parental_Involvement`, `School_Type`, `Gender`).
      * **Hypothesis:** Does the mean `Exam_Score` differ across the levels of each categorical factor?
      * (A bar chart showing the mean `Exam_Score` broken down by one categorical variable, like `Parental_Involvement`.)

-----

## 💾 Data

The analysis uses two primary datasets, both in CSV format:

  * **`StudentPerformanceFactors.csv`:** The comprehensive dataset containing numerous quantitative and categorical variables.
  * **`CategoricalStudentData.csv`:** A subset of the data focusing specifically on the categorical factors used for the Factorial/ANOVA analysis.

| Feature | Description | Example |
| :--- | :--- | :--- |
| **Exam\_Score** (Dependent Variable) | The final score used as the measure of performance. | 70, 85, 62 |
| **Hours\_Studied** | Quantitative predictor of time spent studying. | 23, 19, 29 |
| **Parental\_Involvement** | Categorical factor measuring parent support. | High, Medium, Low |
| **School\_Type** | Categorical factor for the type of school. | Public, Private |

-----

## 🛠️ Setup and Prerequisites

To run the analysis notebooks, you need a Python environment with the following dependencies.

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Install dependencies** using the provided `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis** using Jupyter:

    ```bash
    jupyter notebook
    ```

    Open the `.ipynb` files and run the cells sequentially to reproduce the analysis and conclusions.

-----

## 💻 Technologies

| Category | Tool/Library | Purpose |
| :--- | :--- | :--- |
| **Language** | Python | Primary programming language. |
| **Core Libraries** | `pandas`, `numpy` | Data manipulation and numerical operations. |
| **Statistics** | `statsmodels`, `scipy` | Core libraries for regression, ANOVA, and hypothesis tests. |
| **Visualization** | `matplotlib`, `seaborn` | Generating descriptive and diagnostic plots (e.g., Q-Q plots, residual plots). |
| **Environment** | `Jupyter Notebook` | Interactive analysis and documentation. |

<img width="609" height="470" alt="Code_Generated_Image" src="https://github.com/user-attachments/assets/a11c5897-4245-47ce-9bfe-3232ac3226f0" />
<img width="689" height="547" alt="Code_Generated_Image (2)" src="https://github.com/user-attachments/assets/41d8a28a-65c3-4127-b12c-fabf5fbbc8e6" />
<img width="695" height="547" alt="Code_Generated_Image (1)" src="https://github.com/user-attachments/assets/df875662-7361-4050-9fa4-e96e27fcabc4" />
