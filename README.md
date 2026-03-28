# AI/ML Project Chatbot: "Rudhran"

## Project Overview
This repository holds a Python-based conversational agent named "Rudhran." This conversational agent is designed as a base-level project in Artificial Intelligence and Machine Learning domains, utilizing Natural Language Processing (NLP) to comprehend and process user queries related to the domain of Artificial Intelligence and respond accordingly.

Rather than depending on keyword-based responses, the system uses Term Frequency-Inverse Document Frequency (TF-IDF) vectorization and Cosine Similarity to fetch the most mathematically relevant responses from its knowledge base.

## Key Features
* **Dynamic Corpus Generation:** The script is entirely self-contained, meaning it does not rely on external resources. When initialized, it automatically generates its own `chatbot.txt` corpus, thus avoiding file not found errors.
* **Hybrid Architecture:** The chatbot incorporates a lightweight, rule-based system for general social etiquette and a heavier, more complex machine learning model for domain-specific inquiries.
* **Sophisticated Text Processing:** Leverages the Natural Language Toolkit library for rigorous text processing, including punctuation stripping, tokenization, and WordNet lemmatization.
* **Intelligent Fallback:** Automatically recognizes when a user’s input is not within its training data and responds with a friendly fallback message rather than providing an inaccurate response.

## Tech Stack
* **Language:** Python
* **Libraries:** nltk, scikit-learn, numpy, string, random

## How to Run the Project 
- **Step 1: Install Python**'

i. To install Python, please visit [python.org/downloads](https://www.python.org/downloads/).

ii. **Important for Windows users:** You *must* check the box that says **"Add Python to PATH"** at the bottom of the installation window.

- **Step 2: Download the Code**

i. To get the project's code, please click the green **"<> Code"** button in this repository and select **"Download ZIP"**.

ii. Extract the folder to your computer.

- **Step 3: Open Your Terminal**

i. **Windows:** Press the `Windows Key`, type `cmd`, and press `Enter`.

ii. **Mac:** Press `Command + Space`, type `Terminal`, and press `Enter`.

iii. Navigate to the unzipped folder using the `cd` command.

- **Step 4: Install Dependencies**

i. Execute the following command to install the required libraries:
  `pip install numpy nltk scikit-learn`
  
- **Step 5: Run the Chatbot**

i.The chatbot can be started by executing the following command:
  `python VITyarthi_Project_CHATBOT_AIML.py`
  
- **Step 6: Chat!**

i. Just wait for Rudhran to introduce himself.

ii. Ask him any question you have in mind about Artificial Intelligence, for example: `What is deep learning?`

iii. To exit the conversation, just type:
    `bye! or thanks`

  
