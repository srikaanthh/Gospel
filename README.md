# Fake News Prediction System

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![ML Type](https://img.shields.io/badge/ML-Binary_Classification-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

**Author:** Srikanth

---

## About This Project

This app predicts whether a news article contains fake news or misinformation. In the age of social media, distinguishing real news from fake news has become increasingly difficult. This tool helps users verify the authenticity of news articles before accepting them at face value.

## What It Does

- Analyzes news article text
- Predicts the probability of fake news
- Helps identify misinformation that could mislead the public

## How It Works

1. **Text Cleaning** - Removes special characters and unnecessary words
2. **TF-IDF Vectorization** - Converts text into numerical features
3. **Machine Learning** - Uses a Decision Tree model to classify articles
4. **Prediction** - Returns whether the article is likely real or fake

## Model Performance

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 98% |
| Decision Tree | 99% |
| Gradient Boosting | 99% |

**Final Model:** Decision Tree Classifier (99% accuracy)

## Tech Stack

- Python
- Streamlit
- Scikit-learn
- TF-IDF Vectorization

## Run Locally

```bash
# Clone the repository
git clone "repository link"

# Navigate to directory
cd Fake-News-Prediction-System

# Create virtual environment
python -m venv env

# Activate virtual environment
# Windows:
env\Scripts\activate
# Mac/Linux:
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## Limitations

- Limited to English language articles
- Training data covers only a fraction of internet articles
- May not detect sophisticated AI-generated fake news

## Future Improvements

- Expand to multiple languages
- Increase training data coverage
- Fine-tune metrics for specific use cases
- Improve text preprocessing techniques

## License

MIT License - Feel free to use and modify this project.

---

**Made by Srikanth**
