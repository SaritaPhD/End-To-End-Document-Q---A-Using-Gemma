# End-To-End-Document-Q&A-Using-Gemma

## Overview
This Streamlit application allows users to interact with documents by asking questions and receiving accurate answers based on the provided context. The application leverages the power of large language models (LLMs) and document embeddings to perform document retrieval and question answering.

## Features
- Load documents from a specified directory
- Split documents into chunks for better processing
- Embed documents using Google Generative AI Embeddings
- Create a vector store for efficient document retrieval
- Answer questions based on the content of the documents

## Requirements
- Python 3.9+
- Streamlit
- langchain
- langchain_groq
- langchain_community
- dotenv
- PyPDF2
- faiss

## Installation
- Clone the repository: git clone git@github.com:SaritaPhDEnd-To-End-Document-Q---A-Using-Gemma.git
- cd End-To-End-Document-Q---A-Using-Gemma
- Create a virtual environment: python3.10 -m venv venv
- source venv/bin/activate  # On Windows use `venv\Scripts\activate`
- Install the required packages: pip install -r requirements.txt

## Set up your environment variables:
- Create a .env file in the root directory of the project.
- Add your GROQ and Google API keys:
GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_google_api_key

## Usage
Run the Streamlit application: streamlit run app.py

The application interface will open in your web browser.

## Load the documents:

- Click on the "Documents Embedding" button to load and process the documents from the ./us_census directory.
- Ask a question: Enter your question in the text input field and press Enter. The application will process your question and provide an answer based on the content of the documents.

## Project Structure
- app.py: Main application file
- requirements.txt: List of required Python packages
- .env: Environment variables file (not included in the repository)

![Alt text](<Screenshot 2024-07-25 at 1.23.08 PM.png>)