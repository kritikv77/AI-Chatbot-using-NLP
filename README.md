# AI-Chatbot-using-NLP
Retrieval-based AI Chatbot using the 3K Conversations Dataset. Implements TF-IDF with cosine similarity and a fallback mechanism. Interactive interface via Streamlit.
Project Overview
You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/kreeshrajani/3k-conversations-dataset-for-chatbot).
This project implements a retrieval-based AI chatbot using the 3K Conversations Dataset. The chatbot takes user queries, finds the most similar question in the dataset using TF-IDF vectorization and cosine similarity, and returns the corresponding answer.
It includes NLP preprocessing, handles unknown queries with a fallback response, and can be deployed with Streamlit for real-time interaction.

Key Features

NLP preprocessing: tokenization, lemmatization, stop-word removal

TF-IDF vectorization with cosine similarity for query matching

Fallback mechanism for unrecognized or unmatched queries

Interactive real-time chatbot interface using Streamlit

Works directly with the 3K Conversations CSV dataset

Easy to extend with additional question-answer pairs

Dataset

Columns used:

question → user queries

answer → chatbot responses

Download link: 3K Conversations Dataset on Kaggle

Tools & Environment

Programming Language: Python

Libraries: pandas, scikit-learn, nltk, streamlit

Development Tools: Jupyter Notebook, VS Code

Implementation Steps

Load and explore the dataset.

Apply NLP preprocessing: tokenization, lemmatization, stop-word removal.

Convert questions to TF-IDF vectors.

Compute cosine similarity between user input and dataset questions.

Retrieve the most similar answer or return a fallback response.

How to Run

Clone the repository: git clone https://github.com/yourusername/AI_Chatbot_3K_Conversations.git
Place 3k_conversations.csv in the project folder.

Install dependencies:pip install pandas scikit-learn nltk streamlit
Run Notebook: Open AI_Chatbot_3K_Conversations.ipynb and execute all cells.

Run Streamlit App:streamlit run app.py
Outcome

Developed a retrieval-based AI chatbot capable of responding to a variety of queries.

Demonstrated expertise in NLP preprocessing, TF-IDF vectorization, cosine similarity, and interactive deployment.

Provides a user-friendly interface for testing and extending chatbot functionality.
License

This project is open-source under the MIT License.

Test chatbot in Jupyter Notebook.

Deploy interactive interface using Streamlit.
