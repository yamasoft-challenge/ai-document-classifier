# Task Challenge: AI Document Classifier with Web Interface
## Context:
You are working on an AI platform that helps enterprises automatically classify and summarize documents (e.g., contracts, research papers, or receipts) based on their content. Your task is to create a prototype that demonstrates the core functionality of this platform.
## Requirements:
1. Machine Learning (Core Task)
* Implement a simple ML pipeline to classify documents (text-based).
* Use a pre-trained NLP model (e.g., Hugging Face, spaCy, or scikit-learn).
* The categories for classification should include at least:
  * Legal Document
  * Research Paper
  * Receipt
* You can use simple embeddings like TF-IDF if transformer models are too heavy.
* Implement a basic function to summarize the key sections of the document.
2. Backend Development (Required)
* Build a REST API using Python (Flask or FastAPI) with the following endpoints:

   - /classify: Accepts a text document and returns the classification.
   - /summarize: Accepts a text document and returns a brief summary.
   - /health-check: Returns the health status of the service.

* Include proper error handling and response formats (e.g., JSON).

3. Frontend Development (Optional)
If you choose to implement a front-end, create a simple web interface using any framework (React, Vue, or even plain HTML/CSS/JavaScript):
Upload a text file or paste text into a text area.
A button to classify the document and another to summarize it.
Display the classification result and summary in a clean format.
4. Deployment (Optional)
Provide a Dockerfile to containerize your application.
Instructions for running the service locally using Docker.
