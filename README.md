# AI-Review-Analyzer

AI Review Analyzer is a sophisticated Flask web application that leverages Artificial Intelligence, specifically OpenAI's GPT model, to extract valuable metrics and insights from complex user reviews.

## Features

- **Review Analysis**: Analyzes user reviews for various metrics like satisfaction, category, suggestions, and emotions.
- **AI-Powered**: Integrates OpenAI's GPT-3.5-turbo-instruct model for intelligent text analysis.
- **Security Threat Detection**: Identifies potential security threats in reviews, such as SQL injection or XSS attacks.
- **Flask Web Interface**: Offers a user-friendly web interface for easy interaction with the application.
- **Data Storage**: Manages and stores review data and analysis results.

## Installation

```bash
git clone https://github.com/emgaurav/AI-Review-Analyzer.git
cd AI-Review-Analyzer
pip install -r requirements.txt
```

## Usage
```
python app.py
```
Navigate to http://localhost:5000 in your web browser to access the application.

## Configuration
Set your OpenAI API key in the `app.py` file
```
openai.api_key = 'YOUR-OPENAPI-KEY'
```
