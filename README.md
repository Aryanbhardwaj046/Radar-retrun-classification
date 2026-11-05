# Radar Return Classification for Ionospheric Signal Analysis

## Project overview
Binary classification of ionospheric radar-return observations as GOOD or BAD using the UCI Ionosphere dataset and a Support Vector Machine (SVM) with an RBF kernel.

## Dataset
- UCI Ionosphere, dataset ID 52
- 351 observations and 34 input attributes
- Classes: GOOD (`g`) and BAD (`b`)
- Dataset: https://archive.ics.uci.edu/dataset/52/ionosphere

## Algorithm
- Support Vector Machine (SVM), RBF kernel
- Feature standardization using `StandardScaler`

## Workflow
1. Load and inspect the dataset.
2. Perform exploratory data analysis.
3. Encode labels (`g` -> 1, `b` -> 0).
4. Split into training and testing subsets.
5. Train the SVM pipeline.
6. Evaluate accuracy, precision, recall, F1-score and confusion matrix.
7. Perform cross-validation and optional hyperparameter tuning.

## Repository contents
- `Radar_Return_Classification_Project_Report.docx`: editable report draft.
- `radar_ionosphere_classification.ipynb`: add your completed Colab notebook here.
- `requirements.txt`: Python dependencies.
- `images/`: workflow diagrams.
- `improved_radar_svm_model.pkl`: optional trained model; add only if successfully saved.

## Initial baseline results
- Held-out test accuracy: 95.77%
- Preliminary five-fold cross-validation mean accuracy: 94.01%

These are initial baseline results. Update this section with the final tuned-model results from your executed notebook. Do not label the preliminary CV result as the tuned-model score.

## Optional future hardware extension
A future version may use an SDR/radar signal acquisition front end, a signal-processing computer or embedded processor, feature extraction compatible with the 34 dataset attributes, and the trained SVM pipeline. This is proposed future work and has not been implemented.

## How to run
Open the notebook in Google Colab or Jupyter, install dependencies from `requirements.txt`, and run cells in order.

## Author
- Name: [Add your name]
- Roll number: [Add your roll number]
- Department / College: [Add your department and college]
