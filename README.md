# Data Mining Project

A comprehensive Jupyter notebook for data mining tasks, fully compatible with Google Colab.

## Getting Started

### Option 1: Open in Google Colab (Recommended)

Click the badge below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FarnoodTavasoli/datamining_project/blob/main/data_mining_project.ipynb)

### Option 2: Download and Upload to Colab

1. Download the `data_mining_project.ipynb` file
2. Go to [Google Colab](https://colab.research.google.com/)
3. Click on "File" → "Upload notebook"
4. Select the downloaded `.ipynb` file

### Option 3: Local Jupyter Notebook

If you have Jupyter installed locally:

```bash
# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Start Jupyter
jupyter notebook
```

Then open `data_mining_project.ipynb` in your browser.

## Features

The notebook includes:

- **Setup and Installation**: Install and import necessary libraries
- **Data Loading**: Multiple methods to load data (Google Drive, local upload, URL, built-in datasets)
- **Exploratory Data Analysis**: Visualizations, statistics, and data understanding
- **Data Preprocessing**: Handle missing values, encode categorical features, feature engineering
- **Model Training**: Train multiple machine learning models (Logistic Regression, Decision Trees, Random Forest, SVM)
- **Model Evaluation**: Compare models and detailed performance metrics
- **Predictions**: Make predictions with trained models
- **Model Saving**: Export models for future use

## Usage

1. Open the notebook in Google Colab
2. Run cells sequentially (Shift + Enter)
3. Customize the data loading section with your own dataset
4. Adjust the target column name to match your data
5. Modify features and models as needed for your specific task

## Requirements

The notebook uses common data science libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

All packages are pre-installed in Google Colab.

## Customization

- **Data Source**: Change the data loading method in Section 2
- **Target Variable**: Update `target_col` variable to match your dataset
- **Models**: Add or remove models in Section 5
- **Features**: Add custom feature engineering in Section 4
- **Visualizations**: Customize plots and charts throughout

## Contributing

Feel free to fork this repository and submit pull requests with improvements.

## License

This project is open source and available for educational purposes.
