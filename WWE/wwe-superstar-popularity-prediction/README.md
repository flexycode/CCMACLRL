# WWE Superstar Popularity Prediction 🏆
A machine learning project that predicts WWE wrestlers' popularity tiers (Main Eventer, Mid-Carder, Jobber) based on their career statistics and performance metrics.

### 📊 Project Overview
This project implements a multi-class classification system using various machine learning algorithms to analyze WWE superstar data and predict their popularity tier. The model helps understand what factors contribute to a wrestler's success in the WWE universe.

### 🎯 Business Problem
In the world of professional wrestling, understanding what makes a superstar "main event" material is crucial for talent management, storylining, and business decisions. This project aims to:

* Identify key factors that determine a wrestler's popularity tier

* Predict future superstar potential based on career metrics

* Provide data-driven insights for talent development

### 📁 Dataset
**Dataset Name:** wwe_popularity_prediction_2025.csv
**Size:** 70 WWE superstars with 18 features
**Time Period:** Current 2025 roster

#### Key Features:
* Career Statistics: Years active, total matches, win percentage

* Title History: World titles, secondary titles, tag team titles

* Performance Metrics: Main event appearances, match frequency

* Popularity Indicators: Social media followers, age, brand

* Target Variable: Popularity tier (Main Eventer, Mid-Carder, Jobber)

### 🛠️ Technical Implementation
#### Algorithms Used:

1. **Decision Tree Classifier** - For interpretability and feature importance

2. **Random Forest Classifier** - Ensemble method for improved accuracy

3. **Logistic Regression** - Baseline model performance

4. **Optimized Random Forest** - With hyperparameter tuning

#### Model Performance:

| Model                   | Training Accuracy | Testing Accuracy | Cross-Validation Score | 
|-------------------------|-------------------|------------------|------------------------|
| Decision Tree           | 100%              | 85.7%            | 82.1%                  | 
| Random Forest           | 100%              | 92.9%            | 89.3%                  | 
| Logistic Regression     | 87.5%             | 85.7%            | 83.9%                  |
| Optimized Random Forest | 100%              | 92.9%	           | 91.1%                  |

#### Key Metrics:

* **Overall Accuracy**: 92.9%

* **Precision** (Weighted Avg): 93%

* **Recall** (Weighted Avg): 93%

* **F1-Score** (Weighted Avg): 93%

### 📈 Key Findings

#### Top 5 Most Important Features:

1. **Main Evented PPV** (0.2472) - Most significant predictor

2. **Social Media Followers** (0.1456) - Modern popularity indicator

3. **World Title Reigns** (0.1258) - Championship success

4. **Years Active** (0.0854) - Career longevity

5. **Career Win Percentage** (0.0721) - In-ring performance

#### Business Insights:
* 🎪 **Main event experience** is the strongest predictor of popularity

* 📱 **Social media presence** correlates strongly with main event status

* 🏅 **World championships** matter more than secondary titles

* ⏳ **Longevity** alone doesn't guarantee main event status

* 🎯 **Win percentage** is important but not the primary factor

### 🚀 Model Results

#### Confusion Matrix Analysis:

* **Main Eventers:** 100% accurate prediction

* **Mid-Carders:** 91% accurate prediction

* **Jobbers:** 88% accurate prediction

#### Cross-Validation:
The model shows consistent performance across different data splits with a cross-validation score of **91.1%**, indicating good generalization.

### 💡 Business Applications

#### For WWE Management:

* **Talent Scouting:** Identify potential main eventers early

* **Contract Decisions:** Data-driven contract negotiations

* **Storyline Planning:** Understand what metrics drive popularity

* **Brand Development:** Focus on key success factors

#### For Wrestlers:

* **Career Planning:** Understand paths to main event status

* **Personal Branding:** Focus on key metrics that matter

* **Performance Tracking:** Monitor progress toward goals

🏗️ Project Structure

```
wwe-superstar-popularity-prediction/
│
├── Dataset CSV file/
│   └── wwe_popularity_prediction_2025.csv
│ 
├── Feature importance analysis/
│   ├── feature_importance.csv
│
├── Jupyter Notebook/
│   └── WWE_Superstar_Popularity_Prediction.ipynb
│
├── Trained model file/
│   ├── wwe_popularity_model.pkl
│   
└── README.md
```

### 🛠️ Installation & Usage

#### Prerequisites:

bash
```
Python 3.8+
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

#### Quick Start:

1. Clone the repository

2. Install requirements: `pip install -r requirements.txt`

3. Run the Jupyter notebook: `jupyter notebook`

4. Upload the dataset when prompted

5. Execute all cells sequentially

#### For Production:

python
```
import joblib

# Load the trained model
model = joblib.load('models/wwe_popularity_model.pkl')

# Make predictions
predictions = model.predict(new_wrestler_data)
```

### 📊 Visualizations
The project includes comprehensive visualizations:

* Feature correlation heatmaps

* Target variable distribution

* Model performance comparisons

* Feature importance charts

* Confusion matrices

* Cross-validation results

### 🔮 Future Enhancements

1. **Real-time Data Integration** - Live social media metrics

2. **Sentiment Analysis** - Fan reaction analysis

3. **Time Series Forecasting** - Career trajectory prediction

4. **Web Application** - User-friendly interface

5. **API Integration** - WWE official data sources

### 🤝 Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for:

* Additional features

* Model improvements

* Data validation

* Documentation enhancements

### 📜 License
This project is for educational purposes as part of a machine learning academic project.

### 🙏 Acknowledgments
* Data sourced from [WWE.com](wwe.com) and wrestling statistics databases

* Machine learning algorithms from scikit-learn

* Visualization libraries: matplotlib and seaborn

## 📞 Contact
For questions or collaborations regarding this project, please open an issue or contact the repository maintainer.

## ⭐ If you find this project useful, please give it a star!

"Predicting popularity, one superstar at a time!" 🎭

<!-- End point line insert Thanks for visiting enjoy your day, feel free to modify this  -->
---

<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=Thanks+For+Visiting+Enjoy+Your+Day+~!;" alt="mystreak"/>
</p>

<!-- Siero Miero -->
<div align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3OGJ0aW80YnkwcjdmNzdzZ2tuMDdpaTZydzV5dTQ3M2VtdXlrd2k0ayZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/iF7FoIWjpHD7E2ndx4/giphy.gif" width="300">
</div>

<!-- End point line insert Comeback again next time, feel free to modify this  -->
<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=Come+Back+Again+next+time" alt="mystreak"/>
</p>

</p>
    


