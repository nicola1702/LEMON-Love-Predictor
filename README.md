<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/samuel29102002/LEMON-Love-Predictor">
    <img src="images/logo.png" alt="Logo"  height="200">
  </a>

<h3 align="center">LEMON-Love-Predictor</h3>

  <p align="center">
    Predicting Relationship Status Using Emotional, Cognitive, and Behavioral Traits
    <br />
    <a href="https://github.com/samuel29102002/LEMON-Love-Predictor/tree/main/documentation"><strong>Explore the Docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/samuel29102002/LEMON-Love-Predictor">View Demo</a>
    ·
    <a href="https://github.com/samuel29102002/LEMON-Love-Predictor/issues">Report Bug</a>
    ·
    <a href="https://github.com/samuel29102002/LEMON-Love-Predictor/issues">Request Feature</a>
  </p>
</div>

---

## About The Project

The **LEMON-Love-Predictor** project leverages the LEMON dataset to explore whether **emotional**, **cognitive**, and **behavioral traits** can predict an individual's relationship status. By analyzing psychological and medical test scores, this project aims to identify key factors that influence relational outcomes and build predictive models.

### Key Features
- Extensive data preprocessing and feature engineering.
- Advanced machine learning models including **Random Forest** and **Logistic Regression**.
- Hyperparameter tuning using **GridSearchCV**.
- Model evaluation using **cross-validation** and **SHAP analysis**.
- Exploratory data analysis with **advanced visualizations** (Cluster Maps, SHAP, KDE Plots).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Built With

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Scikit-Learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [SHAP](https://shap.readthedocs.io/en/latest/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Getting Started

### Prerequisites

* Python 3.8 or higher

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/samuel29102002/LEMON-Love-Predictor.git
   ```
2. Install required packages:
   ```sh
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Usage

1. Run the Jupyter Notebook for exploratory data analysis and model training.
2. Visualize feature importance and relationship distributions using SHAP and clustering methods.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Roadmap

- [x] Data Cleaning and Preprocessing
- [x] Feature Engineering
- [x] Exploratory Data Analysis (Correlation, Feature Importance, KDE Plots)
- [x] Model Development (Random Forest, Logistic Regression, Dummy Classifier)
- [x] Model Evaluation (Cross-Validation, GridSearch, SHAP, Statistical Analysis)
- [ ] Deployment (Optional Future Work)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Folder Structure

```plaintext
LEMON-LOVE-PREDICTOR/
├── Behavioural_Data_MPILMBB_LEMON/
│   ├── Cognitive_Test_Battery_LEMON/
│   ├── Data_Availability_Tables/
│   ├── Emotion_and_Personality_Test_Battery_LEMON/
│   ├── Medical_LEMON/
├── age_group.csv
├── cleaned_processed_data.csv
├── final_merged_dataset.csv
├── merged_data_clean_relevant.csv
├── META_File_IDs
├── relationship_status.csv
├── code/
│   ├── data_structure_analysis.ipynb
│   ├── model_training.ipynb
│   ├── requirements.txt
├── documentation/
│   ├── doku_LEMON.md
│   ├── Test_Scales_and_Relationship_Relevance.xlsx
│   ├── testresults.txt
├── images/
├── .gitignore
├── README.md
```

---

## Contributing

Contributions are welcome!

1. Fork the Project
2. Create a Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Contact

* Samuel Heinrich - [GitHub](https://github.com/samuel29102002)
* Nicola Reichert - [GitHub](https://github.com/nicola1702)
* Felix Widmann - [GitHub](https://github.com/FelixWidmann)

Project Link: [https://github.com/samuel29102002/LEMON-Love-Predictor](https://github.com/samuel29102002/LEMON-Love-Predictor)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
