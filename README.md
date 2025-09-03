# Sales Prediction Model

A machine learning project that predicts sales based on advertising spending across different media channels (TV, Radio, and Newspaper).

## 📊 Project Overview

This project uses linear regression to analyze the relationship between advertising expenditure and sales performance. The model helps understand which advertising channels are most effective for driving sales.

## 🎯 Features

- **Data Analysis**: Explore advertising spend vs sales relationships
- **Linear Regression Model**: Predict sales based on advertising investment
- **Performance Metrics**: Evaluate model accuracy using MSE and R² score
- **Visualization**: Scatter plot showing actual vs predicted sales

## 📁 Project Structure

```
SALES/
├── sales.py              # Main Python script
├── sales.csv             # Dataset with advertising and sales data
├── car_purchasing.csv    # Additional dataset
└── README.md            # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.x installed with the following packages:

```bash
pip install pandas matplotlib scikit-learn
```

### Installation

1. Clone this repository:
```bash
git clone https://github.com/devaprasannaprincem/sales-prediction.git
cd sales-prediction
```

2. Run the script:
```bash
python sales.py
```

## 📈 Dataset

The `sales.csv` dataset contains:
- **TV**: Advertising spending on TV (in thousands)
- **Radio**: Advertising spending on Radio (in thousands)
- **Newspaper**: Advertising spending on Newspaper (in thousands)
- **Sales**: Sales revenue (in thousands)

### Sample Data
```
      TV  Radio  Newspaper  Sales
0  230.1   37.8       69.2   22.1
1   44.5   39.3       45.1   10.4
2   17.2   45.9       69.3   12.0
```

## 🔍 Model Performance

The linear regression model achieves:
- **Mean Squared Error**: 2.91
- **R² Score**: 0.91 (91% variance explained)

This indicates excellent model performance with high prediction accuracy.

## 📊 Results

The model generates:

1. **Performance Metrics**: MSE and R² score printed to console
2. **Visualization**: Scatter plot comparing actual vs predicted sales
3. **Model Insights**: Understanding of advertising effectiveness

## 🛠️ How It Works

1. **Data Loading**: Reads the CSV file using pandas
2. **Feature Selection**: Uses TV, Radio, and Newspaper as input features
3. **Data Splitting**: 80% training, 20% testing
4. **Model Training**: Fits a linear regression model
5. **Prediction**: Predicts sales on test data
6. **Evaluation**: Calculates performance metrics
7. **Visualization**: Plots results

## 📝 Code Structure

```python
# Key components:
- Data preprocessing and exploration
- Train-test split (80/20)
- Linear regression model training
- Performance evaluation
- Results visualization
```

## 🔧 Customization

You can modify the script to:

- Use different algorithms (Random Forest, SVM, etc.)
- Add feature engineering
- Tune hyperparameters
- Include cross-validation
- Add more evaluation metrics

## 📋 Requirements

- Python 3.x
- pandas
- matplotlib
- scikit-learn

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**devaprasannaprincem**
- GitHub: [@devaprasannaprincem](https://github.com/devaprasannaprincem)
- Email: devaprasannaprincem@example.com

## 🙏 Acknowledgments

- Dataset source: Marketing analytics dataset
- Inspiration: Marketing analytics and sales forecasting
- Libraries: pandas, scikit-learn, matplotlib

## 📚 Learning Outcomes

This project demonstrates:

- Data preprocessing and analysis
- Linear regression implementation
- Model evaluation techniques
- Data visualization
- Python programming for ML

---

*Replace email with your actual email address if needed.*
