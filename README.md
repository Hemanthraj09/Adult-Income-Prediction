# Adult Income Prediction

## 🎯 Project Overview
This project predicts whether an individual's annual income exceeds $50,000 based on demographic and employment-related features using machine learning techniques. The model analyzes various factors such as age, education, occupation, and work hours to make income predictions.

## 📊 Dataset
- **Source**: Adult Census Income Dataset (originally from 1994 U.S. Census)
- **Size**: 48,842 instances with 15 attributes
- **Target Variable**: Income (≤50K or >50K)
- **Features**:
  - **Demographic**: age, gender, race, native-country
  - **Education**: education, educational-num
  - **Employment**: workclass, occupation, hours-per-week
  - **Financial**: capital-gain, capital-loss
  - **Personal**: marital-status, relationship, fnlwgt

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 📋 Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Hemanthraj09/Adult-Income-Prediction.git
cd Adult-Income-Prediction
```

### 2. Install required packages
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter notebook
```bash
jupyter notebook IncomePrediction.ipynb
```

### 4. Explore the dataset
The dataset is located in the `dataset/` folder:
- `income.csv` - Main dataset file with all features and target variable

## 📈 Project Structure
```
Adult-Income-Prediction/
├── dataset/
│   └── income.csv
├── IncomePrediction.ipynb
├── README.md
└── requirements.txt
```

## 🔍 Analysis Pipeline

### 1. **Data Exploration & Understanding**
- Dataset shape and structure analysis
- Statistical summary of features
- Missing value detection and handling

### 2. **Exploratory Data Analysis (EDA)**
- Distribution analysis of numerical and categorical features
- Income distribution visualization
- Correlation analysis between features
- Feature relationships with target variable

### 3. **Data Preprocessing**
- Handling missing values (marked as '?')
- Encoding categorical variables
- Feature scaling and normalization
- Train-test split

### 4. **Feature Engineering**
- Creating new meaningful features
- Feature selection techniques
- Handling categorical variables with encoding

### 5. **Model Training & Evaluation**
- Multiple algorithm comparison
- Model performance evaluation
- Cross-validation
- Hyperparameter tuning

### 6. **Results & Insights**
- Model performance metrics
- Feature importance analysis
- Business insights and recommendations

## 📊 Key Features Analysis
- **Age**: Distribution and income correlation
- **Education**: Impact of education level on income
- **Work Hours**: Relationship between working hours and income
- **Occupation**: High-income vs low-income occupations
- **Gender & Demographics**: Income distribution patterns

## 🎯 Model Performance
[Results will be updated after running the complete analysis]
- **Accuracy**: TBD%
- **Precision**: TBD%
- **Recall**: TBD%
- **F1-Score**: TBD%

## 💡 Key Insights
- Education level significantly impacts income prediction
- Certain occupations have higher income potential
- Age and work experience correlate with higher income
- Gender and demographic factors show income disparities

## 📈 Visualizations
The notebook includes various visualizations:
- Income distribution charts
- Feature correlation heatmaps
- Categorical variable distributions
- Model performance comparison plots

## 🚀 Future Improvements
- [ ] Feature engineering with polynomial features
- [ ] Ensemble methods implementation
- [ ] Deep learning model comparison
- [ ] Web application for real-time predictions
- [ ] Model interpretability with SHAP/LIME

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author
**Hemanth Raj** - [GitHub Profile](https://github.com/Hemanthraj09)

## 📧 Contact
Feel free to reach out if you have any questions or suggestions!

## 🙏 Acknowledgments
- UCI Machine Learning Repository for providing the Adult dataset
- Scikit-learn community for the excellent machine learning library
- Jupyter Project for the interactive computing platform
