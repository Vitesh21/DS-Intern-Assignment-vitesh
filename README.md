# Smart Factory Energy Prediction Challenge

## Project Structure
```
.
├── data/               # Data directory
│   └── data.csv       # Dataset containing sensor data
├── notebooks/         # Jupyter notebooks
│   └── analysis.ipynb # Main analysis notebook
├── requirements.txt   # Project dependencies
└── README.md         # This file
```

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter notebook in `notebooks/analysis.ipynb`

## Project Approach

This project aims to predict equipment energy consumption in a manufacturing facility using sensor data. The analysis includes:

1. **Exploratory Data Analysis (EDA)**
   - Data quality assessment
   - Missing value analysis
   - Distribution analysis
   - Correlation analysis
   - Feature importance visualization

2. **Data Preprocessing**
   - Handling missing values
   - Outlier detection and treatment
   - Feature engineering
   - Data scaling

3. **Model Development**
   - Multiple regression models implementation
   - Model comparison and evaluation
   - Hyperparameter tuning
   - Cross-validation

4. **Model Evaluation**
   - RMSE (Root Mean Square Error)
   - MAE (Mean Absolute Error)
   - R² Score
   - Cross-validated performance

5. **Insights and Recommendations**
   - Key factors affecting energy consumption
   - Actionable recommendations for energy reduction
   - Optimization strategies

## Dependencies

Key libraries used:
- pandas: Data manipulation and analysis
- numpy: Numerical computations
- scikit-learn: Machine learning models and tools
- matplotlib: Basic plotting
- seaborn: Advanced statistical visualizations
- jupyter: Interactive notebook environment

## Results

The analysis provides:
1. Identification of key factors influencing energy consumption
2. Predictive models for energy consumption
3. Insights for energy optimization
4. Recommendations for reducing energy costs

## Usage

1. Open `notebooks/analysis.ipynb` in Jupyter Notebook or VS Code
2. Run the cells in sequence
3. Review the visualizations and insights
4. Check the model performance metrics
5. Review the recommendations for energy reduction

## Notes

- The analysis includes handling of missing values and outliers
- Feature engineering has been performed to improve model performance
- Multiple models are compared to find the best predictor
- Cross-validation is used to ensure robust model evaluation 