# Sentiment Analysis using Watson NLP (BERT) - Flask Application

## Introduction
This repository contains a simple Flask web application for sentiment analysis using the Watson Natural Language Processing (NLP) service with BERT models. The application allows users to input text, and it provides sentiment analysis results based on the provided text.

## Requirements
Make sure you have the following requirements installed before running the application:
- Python 3.x
- Flask
- requests

You can install the required Python packages using the following command:
```bash
pip install Flask requests
```

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/sentiment-analysis-watson-bert.git
cd sentiment-analysis-watson-bert
```

### 2. Set up a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Run the Flask Application
```bash
python server.py
```
#### The application will be accessible at http://127.0.0.1:5000/ in your web browser.

## Usage
1. Open your web browser and navigate to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).
2. Enter the text you want to analyze in the input field and submit the form.
3. View the sentiment analysis result, which includes the sentiment label and score.

## Files and Structure
- **server.py:** Flask application file containing the server logic.
- **SentimentAnalysis/sentiment_analysis.py:** Module for interacting with the Watson NLP service and performing sentiment analysis.
- **tests/test_sentiment_analysis.py:** Unit tests for the sentiment analysis module.
- **index.html:** HTML template for the web application.

## Watson NLP Configuration
The sentiment analysis is performed using the Watson NLP service with BERT models. Make sure you have the appropriate credentials and endpoint configured in `sentiment_analysis.py`. Update the `url` and `header` variables in the file accordingly.

## Unit Tests
To run the unit tests, use the following command:
```bash
python -m unittest discover tests
```

## Contributing
Feel free to contribute to the project by submitting issues or pull requests. Follow the guidelines outlined in CONTRIBUTING.md.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.