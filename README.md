app.py:
This is the main application script that initiates and runs the chatbot application. It includes setup for web frameworks like Flask, API endpoints, and the core logic for handling user interactions.
chatbot.

ipynb:
A Jupyter notebook used for developing and testing the chatbot. It includes code cells for data preprocessing, model training, and interactive testing of the chatbot's responses.

ingest.py:
This script is responsible for ingesting medical data from various sources, processing it, and storing it in a format suitable for the chatbot to use. It handles data cleaning and transformation.

medical_chatbot_working.py:
Contains the core logic for the chatbot, including the main functions for processing user queries, generating responses, and integrating with machine learning models.

model.py:
Defines the machine learning model used by the chatbot. It includes functions for model training, loading pre-trained models, and making predictions based on user input.

req.py:
Handles the installation and management of dependencies required for the project. This script ensures all necessary libraries and packages are installed and updated.

data Directory:
Contains medical data files, likely in formats such as CSV or JSON, used to train and test the chatbot. These files provide the knowledge base for the chatbot's responses.

vectorstore/db_faiss:
Stores vectorized data for efficient querying. FAISS (Facebook AI Similarity Search) is used to quickly search through large datasets by converting data into vector space.

NLP Directory:
Contains utilities and scripts related to natural language processing, such as text preprocessing, tokenization, and feature extraction. These are essential for understanding and generating human language in the chatbot.
