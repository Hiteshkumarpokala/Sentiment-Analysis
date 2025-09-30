Sentiment Analysis Project

This project demonstrates sentiment analysis using two approaches:

Web-based Implementation (HTML, CSS, JavaScript + Streamlit UI)

A simple interactive interface to analyze text sentiment.

Allows both single text analysis and bulk CSV file upload for batch sentiment analysis.

Python-based Implementation

Uses Python libraries (re, json, typing) for advanced text sentiment classification.

Easily extendable for more complex NLP tasks.

🚀 Features

🔹 Single Analysis: Enter a text snippet and instantly classify it as Positive, Negative, or Neutral.

🔹 Bulk Analysis: Upload a CSV file containing text column(s) for large-scale sentiment analysis.

🔹 Web-based Dashboard with clean UI (Streamlit + HTML/CSS/JS).

🔹 Lightweight Python Backend for text cleaning and sentiment detection.

🔹 Exportable Results after bulk analysis.

🛠 Project Requirements

To run this project locally, you’ll need:

Python 3.10+

Download Python 3.10 here

Virtual Environment (recommended)

Python Libraries:

streamlit
pandas
re
json
typing


Install dependencies with:

pip install -r requirements.txt

📂 Database / Data Setup (in short)

No heavy database is required for this project.

For single text analysis, input is directly processed.

For bulk analysis, you can upload a CSV file with at least one column containing text data.

Example CSV format:

id,text
1,This product is amazing!
2,I'm not happy with the service.
3,It was okay, nothing special.

💻 How to Run the Project Locally
1. Clone the Repository
git clone <your-repo-link>
cd Sentiment-Analysis

2. Create & Activate Virtual Environment
# Windows
py -3.10 -m venv venv
venv\Scripts\activate

# Mac/Linux
python3.10 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Run the Streamlit App

Make sure you are in the project root folder where sentiment_app.py is located:

streamlit run sentiment_app.py

5. Open in Browser

Once started, Streamlit will give a local URL, usually:

👉 http://localhost:8501

📸 Outputs

Single Analysis: Enter a sentence → click Predict → sentiment displayed.

Bulk Analysis: Upload CSV → see sentiment classification table + chart instantly.

🔮 Future Enhancements

Use Machine Learning models (Naive Bayes, LSTM, Transformers).

Add Sentiment Intensity Score instead of just Positive/Negative/Neutral.

Multi-language support.