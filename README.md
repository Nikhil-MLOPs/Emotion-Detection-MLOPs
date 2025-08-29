# Emotion-Detection-MLOPs
Build an ML pipeline to classify emotions in text using BoW &amp; TF-IDF with Logistic Regression, Random Forest, Naive Bayes &amp; XGBoost. Use DVC, Git, MLflow, Docker, GitHub Actions, FastAPI, Streamlit, Kubernetes, Prometheus &amp; Grafana for end-to-end MLOps.


The Emotion-Detection-MLOPs project focuses on building and deploying a machine learning pipeline to classify emotions from text data. The system will predict categories like happiness, sadness, anger, fear, surprise, or neutral tone.

The pipeline begins with data preprocessing, including tokenization, stopword removal, and text normalization. For feature extraction, both Bag of Words (BoW) and TF-IDF techniques will be applied to convert text into numerical representations. Models such as Logistic Regression, Random Forest, Naive Bayes, and XGBoost will be trained and compared to select the best performer.

To integrate MLOps principles, the project uses:

- DVC + Git for dataset and code versioning.

- MLflow for experiment tracking and model registry.

- Docker for containerization of the ML pipeline.

- GitHub Actions for CI/CD automation.

- FastAPI to serve the trained model as an API.

- Streamlit to provide an interactive user interface for predictions.

Kubernetes for orchestration and scalability.

Prometheus & Grafana for monitoring and visualization of deployed services.
