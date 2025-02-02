# EQL Document Classification

This repository contains a solution for classifying PDF documents into one of three categories:

- **Financial Reports**
- **Presentations**
- **Press Releases**

## Overview

The task is to accurately classify a set of PDF documents into one of the aforementioned categories. The repository includes two approaches to solving this task:

1. **Machine Learning Classifier Model**: A custom-built classifier that leverages a machine learning model to categorize the documents with an accuracy of around 70%.
2. **OpenAI API Integration**: A chatbot solution that utilizes OpenAI’s GPT models to classify documents. Additionally, work is ongoing to fine-tune a Large Language Model (LLM) for improved accuracy and customization to the data at hand.

## Features

- **PDF Text Extraction**: Extracts text from PDF documents for processing and classification.
- **Machine Learning Classification**: Uses a traditional classifier model for document categorization.
- **OpenAI GPT-based Classification**: Integrates with the OpenAI API to classify documents using GPT models.
- **Ongoing Fine-Tuning**: Exploration of fine-tuning an LLM to enhance classification performance tailored to the specific dataset.

## Installation

Clone the repository:

   ```bash
   git clone https://github.com/yourusername/EQL-Document-Classifier.git
   ```
## Usage
1. Machine Learning Classifier Model,
   This will read the PDFs, preprocess the text, and classify them into one of the three categories.
