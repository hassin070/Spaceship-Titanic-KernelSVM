# Spaceship Titanic - Kernel SVM Classifier

This repository contains my solution for the [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic) Kaggle competition.  
I implemented a **Kernel SVM classifier** to predict whether passengers were transported to another dimension.

## Dataset
- The dataset consists of information about spaceship passengers, including features like age, spending, cabin type, etc.
- The goal is to predict the `Transported` column (True/False).

## Approach
1. **Data Preprocessing:**
   - Handled missing values.
   - Encoded categorical variables.
   - Scaled numerical features.
   
2. **Model Selection:**
   - Used **Kernel SVM** with the RBF kernel.
   - Evaluated performance using accuracy.

3. **Predictions:**
   - Stored final predictions in `predictions_KernelSVMClassification.csv`.

## Files
- `KernelSVMClassification_spaceship.ipynb` → Jupyter notebook with code & analysis.
- `predictions_KernelSVMClassification.csv` → Final submission file.
- `requirements.txt` → Required Python libraries.

## Dependencies
To install required libraries, run:
```bash
pip install -r requirements.txt
```

## Usage
Clone the repository and run the notebook:
```bash
git clone https://github.com/yourusername/Spaceship-Titanic-KernelSVM.git
cd Spaceship-Titanic-KernelSVM
jupyter notebook KernelSVMClassification_spaceship.ipynb
```

## Results
- Model accuracy: **(0.79284)**
- Kaggle leaderboard score: **(880)**
