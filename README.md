# Student Performance Predictor

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains a machine learning application that predicts student exam performance using linear and logistic regression models. The app takes inputs such as study hours, attendance percentage, and number of practice tests to forecast:
- **Final Score** (continuous value via linear regression).
- **Pass/Fail Outcome** (binary classification via logistic regression, with probability).

Built with Python and scikit-learn, the project demonstrates end-to-end ML workflow: data preparation, model training, evaluation, and deployment as an interactive web app using Gradio. It's designed for educational purposes, helping beginners understand regression techniques while achieving high model performance (e.g., R² > 0.9, accuracy > 95% on the provided dataset).

Key features:
- Synthetic/realistic dataset with 501 data points.
- Model evaluation metrics (MSE, R² for regression; accuracy, precision, recall for classification).
- Interactive demo app for real-time predictions.
- Extensions for feature scaling and engineering to optimize performance.

This project is ideal for ML workshops, portfolios, or academic clubs.

## Dataset
The dataset (`studentPerformance.csv`) includes:
- **Features**: Study_Hours (0-10), Attendance (50-100%), Practice_Tests (0+).
- **Targets**: Final_Score (0-100), Pass_Fail (0 or 1, threshold at 50).
## Installation

1. Clone the repository:
git clone https://github.com/Khalifa-Bouneb/MLS_project-Student-Performance-Predictor-ML.git

cd Student-Performance-Predictor-ML

2. Install dependencies (use a virtual environment recommended):

pip install -r requirements.txt

## Usage

1. Open the Jupyter notebook:

jupyter notebook student_predictor.ipynb

2. Run the cells step-by-step:
- Load and prepare data.
- Train models.
- Evaluate performance.
- Launch the Gradio app (shareable link generated).

Example prediction in the app:
- Inputs: Study Hours = 6, Attendance = 90%, Practice Tests = 4.
- Output: Predicted Score ~80/100, Pass with ~95% probability.

## Project Structure
- `studentPerformance.csv`: Dataset file.
- `student_predictor.ipynb`: Main Jupyter notebook with code and explanations.
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file.

## Contributing
Contributions are welcome! Fork the repo, create a branch, and submit a pull request. For issues, open a GitHub issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Inspired by educational ML workshops. Dataset is synthetically generated for demonstration.

