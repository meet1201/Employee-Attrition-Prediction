# Employee Attrition Prediction Model

## Project Overview
This project focuses on predicting employee attrition using machine learning. By analyzing various factors and employee characteristics, the model can identify potential attrition risks, aiding HR departments in implementing effective retention strategies.

## Model Performance
- **Accuracy**: 82.70%
- **Precision**: 81.23%
- **Recall**: 85.17%
- **Confusion Matrix**:
  - True Positives: 316
  - True Negatives: 296
  - False Positives: 73
  - False Negatives: 55

## Dataset Description
The dataset used for this model is the IBM HR Analytics Employee Attrition & Performance dataset, which contains details about employee's job satisfaction, demographic info, and their stay or departure status from the company. Attributes include Age, DailyRate, JobRole, OverTime, etc.

### Source
The dataset is publicly available and can be accessed from the [IBM HR Analytics Dataset page on Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).

## Files in the Repository
- `Emp_attrition.ipynb`: Jupyter notebook containing the data analysis, preprocessing, model training, and evaluation.

## How to Run the Notebook
1. Ensure Python 3 and Jupyter Notebook are installed on your system.
2. Install necessary Python packages: pandas, numpy, matplotlib, seaborn, sklearn, imblearn.
3. Clone this repository and run `jupyter notebook` in the project directory.
4. Open `Emp_attrition.ipynb` and execute the cells sequentially.

## Libraries Used
- Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for data visualization.
- Scikit-Learn for model building and evaluation.
- Imbalanced-Learn (imblearn) for handling imbalanced data.

## Author
[Meet Patel] - Feel free to connect on mpatel122931@gmail.com

## License
This project is licensed under the MIT License - see the LICENSE file for details.
