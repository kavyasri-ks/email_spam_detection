📩Email Spam Detection using AI/ML
An AI/ML-based system that preprocesses email text, extracts features, and classifies messages as SPAM or NOT SPAM using Logistic Regression. The project combines Natural Language Processing (NLP), machine learning, and Gmail IMAP integration to automatically fetch and classify recent emails.

🚀 Features
Model Training: Preprocesses dataset, extracts features using a vectorizer, and trains a Logistic Regression model.
Email Fetching: Connects to Gmail via IMAP to retrieve the latest emails.
Spam Classification: Predicts whether each fetched email is SPAM or NOT SPAM.
Compact Output: Displays only the first few lines of the email body.

📌Enable Gmail IMAP & App Password
Go to Gmail Settings → Enable IMAP.
In your Google Account → Security → Generate an App Password.
Use this app password instead of your Gmail password when running the script.

🔑 Important Notes
Hotspot Usage: Use a mobile hotspot if facing IMAP connectivity issues.
Security: Never hardcode Gmail credentials in scripts. Use environment variables or secure input prompts.


