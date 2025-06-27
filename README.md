# Mine Detection using Logistic Regression

This project uses logistic regression to classify sonar signals as either mines (M) or rocks (R) based on the [sonar_data.csv](sonar_data.csv) dataset.

## Project Structure

- `mine-detection.ipynb`: Jupyter notebook containing data analysis, model training, and evaluation.
- `sonar_data.csv`: Dataset with sonar signal features and labels.
- `README.md`: Project documentation.

## Dataset

The dataset contains 208 samples with 60 features each, representing sonar signal returns. The last column (61st) is the label:  
- `M`: Mine  
- `R`: Rock

## Usage

1. Open `mine-detection.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells to:
   - Load and explore the data
   - Train a logistic regression model
   - Evaluate model performance

## Requirements

- Python 3.9+
- pandas
- numpy
- scikit-learn
- matplotlib

Install dependencies with:
```sh
pip install pandas numpy scikit-learn matplotlib