# Universal Brain — IT Support Classifier

Live demo: https://suddhasheel333.github.io/universal-brain/

NLP-based IT ticket classifier built during my internship at Indian Oil Corporation Ltd. (IOCL).
Uses TF-IDF with character n-grams and cosine similarity to match tickets to known solutions,
with a custom confidence calibration formula. Deployed on AWS Lambda with S3 model storage.

**Stack:** Python, scikit-learn, AWS Lambda, S3, SNS
