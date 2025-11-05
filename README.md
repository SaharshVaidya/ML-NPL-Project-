# multiple-disease-prediction-streamlit-app

This repository contains the codebase for "Multiple Disease Prediction Streamlit App". The training notebooks \& the datasets are also provided in the respective folders.

app.py is the streamlit app code.
run the command "**pip install -r requirements.txt**" to install the required dependencies for the streamlit app.

You may need to install additional libraries for running the jupyter notebooks.

\# Multiple Disease Prediction Using Machine Learning



&nbsp;Project Overview

This project implements a comprehensive machine learning framework to predict multiple diseases simultaneously — specifically diabetes, heart disease, and Parkinson’s disease — using clinical datasets. Leveraging Random Forest classifiers, the system analyzes patient clinical features to provide early diagnostic risk assessments. The integrated multi-disease model framework aims to support healthcare professionals by enabling faster, data-driven disease prediction.



&nbsp;Features

\- Trains disease-specific Random Forest classifiers on publicly available datasets.

\- Preprocesses data including handling missing values, normalization, and feature selection.

\- Evaluates models using accuracy, precision, recall, and ROC-AUC metrics.

\- Produces ROC curve visualizations for each disease model.

\- Provides modular Python code for model training and evaluation.

\- Includes a detailed LaTeX report documenting methodology, results, and literature.



&nbsp;Repository Contents

\- `app.py`: Python code implementing data preprocessing, model training, and evaluation.

\- `Training.csv`: Clinical dataset used for model training.

\- `Testing.csv`: Separate dataset for model testing and validation.

\- `report.tex`: Complete LaTeX report summarizing the project, with expanded theory and results.

\- ROC curve images (`roc\_curve\_diabetes.png`, `roc\_curve\_heart\_disease.png`, `roc\_curve\_parkinsons.png`).



&nbsp;Setup and Usage



&nbsp;Prerequisites

\- Python 3.x

\- Libraries: pandas, numpy, scikit-learn, matplotlib



&nbsp;Installation

```bash

pip install pandas numpy scikit-learn matplotlib

```



&nbsp;Running the Code

1\. Place `Training.csv` and `Testing.csv` in the working directory.

2\. Run the Python script to train models and generate ROC curve images:

```bash

python app.py

```

3\. Check generated ROC curve images and evaluation metrics printed.



&nbsp;Generating the Report

Compile the LaTeX report `report.tex` using your preferred LaTeX editor or command-line tool:

```bash

pdflatex report.tex

```



&nbsp;Project Structure

```

/project-root

|-- app.py

|-- Training.csv

|-- Testing.csv

|-- report.tex

|-- roc\_curve\_diabetes.png

|-- roc\_curve\_heart\_disease.png

|-- roc\_curve\_parkinsons.png

```



&nbsp;References

This project builds on foundational research in machine learning and healthcare informatics. Please refer to the `report.tex` document for an extensive bibliography including seminal papers by Breiman on Random Forest, and modern studies on disease prediction.



&nbsp;Contributing

Contributions to extend disease coverage, improve model accuracy, or incorporate additional data types are welcome. Please fork the repository and submit pull requests for review.







