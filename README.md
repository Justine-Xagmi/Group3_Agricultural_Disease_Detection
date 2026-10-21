Agricultural Disease Detection

A Python-based machine-learning and data-analysis project exploring crop disease prediction using environmental data.

Overview

Agricultural Disease Detection investigates how structured agricultural and environmental data can be explored to identify patterns that may be useful for crop-disease prediction. The project includes a dataset and Jupyter notebooks for exploratory data analysis, feature-distribution visualizations, and data preparation or experimentation.

The aim is to support earlier investigation of potential crop-health risks and contribute to more informed agricultural decision-making.
This repository is a project prototype and should not be treated as a validated diagnostic tool without further testing.
Objectives
- Explore the available agricultural dataset and understand its features.
- Inspect data quality and prepare data for analysis.
- Visualize feature distributions and investigate patterns in the data.
- Experiment with machine-learning approaches where implemented in the notebooks.
- Document the analysis so that another developer can review and reproduce the workflow.
  
Project Contents
The repository currently includes a dataset and Jupyter notebooks. The exact file names and the role of each notebook should be checked against the current repository contents.

A typical workflow for this project is:
1. Load the dataset.
2. Inspect columns, data types, missing values, and basic statistics.
3. Explore feature distributions and relationships using visualizations.
4. Prepare suitable features and target labels, if provided.
5. Run the analysis or model experiments implemented in the notebooks.
6. Review results and record limitations.
   
Technology
- Python — data analysis and experimentation.
- Jupyter Notebook — interactive, step-by-step analysis.
- CSV — dataset storage, if the repository's dataset is in CSV format.
- Python data-analysis and machine-learning libraries — use the exact libraries imported by the notebooks; commonly used examples include pandas, NumPy, Matplotlib, Seaborn, and scikit-learn, but verify which are actually required before installing them.
Getting Started

Prerequisites
- Python 3.10 or another version compatible with the notebook dependencies.
- Git.
- Jupyter Notebook or JupyterLab.
1. Clone the repository
git clone https://github.com/Justine-Xagmi/Group3_Agricultural_Disease_Detection.git
cd Group3_Agricultural_Disease_Detection
2. Create and activate a virtual environment
Windows PowerShell:
python -m venv .venv
.\.venv\Scripts\Activate.ps1
macOS or Linux:
python3 -m venv .venv
source .venv/bin/activate
3. Install dependencies
Check the notebooks for their imports and install the required packages. For example, if these libraries are used:
python -m pip install jupyter pandas numpy matplotlib seaborn scikit-learn
If the repository has a requirements.txt file, prefer:
python -m pip install -r requirements.txt
4. Launch Jupyter
jupyter notebook
Open the notebook you want to explore and run the cells in order. If a notebook expects a dataset at a specific path, keep the dataset in the expected location or update the path in the notebook.

Reproducibility Notes
- Run notebook cells in sequence, from top to bottom.
- Confirm the dataset path before running data-loading cells.
- Record the Python and library versions used for experiments.
- If a model is trained, keep the target column, feature-selection process, train/test split, random seed, and evaluation metrics documented.
- Do not interpret exploratory patterns as proof of disease causation.
Evaluation and Limitations
Before describing this project as a disease-detection system, verify whether the repository contains a trained model and a clearly defined evaluation. If model training is implemented, report only measured results and specify the evaluation method.
Important considerations include dataset quality, class imbalance, generalization to new locations or seasons, and the difference between environmental-risk prediction and diagnosis based on crop images or field observations.

My Role
Developer: Justine Silwimba (Justine-Xagmi)

I was the primary developer of this project. My work should be described in terms of the parts I personally implemented, such as notebook development, data preparation, exploratory analysis, visualization, model experimentation, debugging, or documentation. Update this section if the division of work needs to be stated more precisely.
Future Improvements

- Document the dataset source, features, target variable, and usage permissions.
- Organize reusable processing and training logic into Python modules where appropriate.
- Add repeatable evaluation and baseline comparisons if model training is part of the project.
- Include a clear results section with measured metrics and known limitations.
- Add tests for reusable code and a documented way to reproduce results.
  
Responsible Use

This project is intended for learning and experimentation. Do not rely on its output alone to diagnose crop disease or make high-impact agricultural decisions. Validate any predictions with suitable field evidence and qualified agricultural advice.
