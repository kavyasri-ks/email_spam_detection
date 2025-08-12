📩 Email Spam Detection using AI/ML
An AI/ML-based system that preprocesses email text, extracts features, and classifies messages as SPAM or NOT SPAM using Logistic Regression.
This project integrates Natural Language Processing (NLP), machine learning, and Gmail IMAP to automatically fetch and classify recent emails.

🚀 Features
Model Training – Preprocesses dataset, extracts features using a vectorizer, and trains a Logistic Regression model.
Email Fetching – Connects to Gmail via IMAP to retrieve the latest emails.
Spam Classification – Predicts whether each fetched email is SPAM or NOT SPAM.
Compact Output – Displays only the first few lines of the email body for quick review.

📌 Prerequisites
Enable Gmail IMAP & App Password
Go to Gmail Settings → Enable IMAP.
In Google Account → Security → Generate an App Password.
Use this app password instead of your Gmail password in the script.

Install Required Libraries

pip install pandas numpy scikit-learn imaplib email


🔑 Important Notes
Hotspot Usage – Use a mobile hotspot if facing IMAP connectivity issues.
Security – Never hardcode Gmail credentials in scripts.
Use environment variables or secure input prompts.

💻 Getting Started

Clone the repository

git clone https://github.com/kavyasri-ks/email_spam_detection.git

cd email_spam_detection

📊 Workflow
    Dataset Loading – Reads email dataset or fetched emails.
    Text Preprocessing – Cleans and tokenizes email text.
    Feature Extraction – Converts text into numerical vectors.
    Model Training – Trains Logistic Regression classifier.
    Prediction – Classifies emails as SPAM or NOT SPAM.

