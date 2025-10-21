# Sentiment_Analysing_Project
## Project Overview
This project implements a sentiment analysis system using machine learning to analyze text and determine sentiment polarity. The model is trained to classify text into different sentiment categories using advanced NLP techniques.

## Project Structure
```
├── notebooks/
│   ├── 01)download_datase.ipynb     # Dataset acquisition
│   ├── 02)model_building.ipynb      # Model training pipeline
│   └── model_pipeline.ipynb         # Complete model pipeline
├── artifact/
│   ├── kaggle.json                  # Kaggle API credentials
│   └── sentiment_analysis.csv       # Dataset
├── Static/
│   └── model/                       # Saved model files
└── requirements.txt                 # Project dependencies
```

## Setup and Installation

1. **Create Virtual Environment**
   ```bash
   python -m venv sentiment_env
   source sentiment_env/bin/activate  # On Windows: sentiment_env\Scripts\activate
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Development Pipeline

### 1. Data Acquisition (01)download_datase.ipynb)
- Dataset download using Kaggle API
- Initial data exploration
- Data validation and verification
- Basic data cleaning and preprocessing

### 2. Model Building (02)model_building.ipynb)
- Data preprocessing
  - Text cleaning
  - Tokenization
  - Feature extraction
- Model selection and training
- Model evaluation and validation
- Hyperparameter tuning
- Performance metrics analysis

### 3. Model Pipeline (model_pipeline.ipynb)
- Complete end-to-end pipeline
- Text preprocessing functions
- Model inference pipeline
- Integration testing
- Performance optimization

##
Train and test the decision tree,random forest, svm, naive bayse : multinominalNB,logistice regression. and selected LOgistic regression, becasue it had the better accuracy. Here the model is Fine tuned only using text processing the dataset.

## Model Information

- Model Type: [Logistic Regression]
- Training Dataset: Sentiment Analysis Dataset
- Features:
  - Text preprocessing
  - Feature extraction
  - Sentiment classification
- Performance Metrics:
  - Accuracy: [0.941]
  - F1 Score: [0.943]

## Future Improvements

# Sentiment Analysis Project

## Project Overview
This project implements a sentiment analysis system using machine learning to analyze text and determine sentiment polarity. The model is trained to classify text into different sentiment categories using advanced NLP techniques.

## Project Structure
```
├── notebooks/
│   ├── 01)download_datase.ipynb     # Dataset acquisition
│   ├── 02)model_building.ipynb      # Model training pipeline
│   └── model_pipeline.ipynb         # Complete model pipeline
├── artifact/
│   ├── kaggle.json                  # Kaggle API credentials
│   └── sentiment_analysis.csv       # Dataset
├── Static/
│   └── model/                       # Saved model files
└── requirements.txt                 # Project dependencies
```

## Setup and Installation

1. **Create Virtual Environment**
   ```bash
   python -m venv sentiment_env
   source sentiment_env/bin/activate  # On Windows: sentiment_env\Scripts\activate
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Development Pipeline

### 1. Data Acquisition (01)download_datase.ipynb)
- Dataset download using Kaggle API
- Initial data exploration
- Data validation and verification
- Basic data cleaning and preprocessing

### 2. Model Building (02)model_building.ipynb)
- Data preprocessing
  - Text cleaning
  - Tokenization
  - Feature extraction
- Model selection and training
- Model evaluation and validation
- Hyperparameter tuning
- Performance metrics analysis

### 3. Model Pipeline (model_pipeline.ipynb)
- Complete end-to-end pipeline
- Text preprocessing functions
- Model inference pipeline
- Integration testing
- Performance optimization

## Usage

```python
# Example usage of the sentiment analysis model
from model_pipeline import SentimentAnalyzer

# Initialize the analyzer
analyzer = SentimentAnalyzer()

# Analyze text
text = "This product is amazing!"
sentiment = analyzer.predict(text)
print(f"Sentiment: {sentiment}")
```

## Model Information

- Model Type: [Your Model Type]
- Training Dataset: Sentiment Analysis Dataset
- Features:
  - Text preprocessing
  - Feature extraction
  - Sentiment classification
- Performance Metrics:
  - Accuracy: [Your Accuracy]
  - F1 Score: [Your F1 Score]

## Future Improvements
Planing to improve tthe accuarcy by more fine tuning the Logistic regresson mdel and using deep learning models. Further works will be uploaded/are uploaded to another repository.
## Contributing

Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


