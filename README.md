# AI/ML Project Chatbot: "Rudhran"

## Project Overview
This repository contains Python-based an AI assistant or a Chatbot named "Rudhran." This Chat bot is vitrual helping agent that is designed as a base level project to help in Artificial Intelligence and Machine Learning domains. The main back bone of this project is Natural Language Processing (NLPs), which comprehends and processes user's queries related to the Artificial Intelligence domain and responds accurately to it.

Rather than depending on keyword-based responses, the system works on Term Frequency-Inverse Document Frequency (TF-IDF) vectorization and Cosine Similarity to gather the most mathematically relevant/Emphasised from the knowledge base.

## Key Features
* **Dynamic Corpus Generation:** The script is completely self-contained, it states that it doesn't require any additional files to be installed to run the program. When initialized it creates it own `chatbot.txt` database where the data is present, avoiding the file not found errors.
* **Hybrid Architecture:** The chatbot is incorporated by a less weighted, rule-based system for general social etiquette and a heavier, more complex machine learning model for domain-specific inquiries.
* **Sophisticated Text Processing:** It utilizes the Natural Language Toolkit library for rigorous text processing, including punctuation stripping, tokenization, and WordNet lemmatization.
* **Intelligent Fallback:** The system automatically recognizes if the a user’s input is not present within its training data and it responds with a friendly check on message "I'm sorry, I don't understand you" rather than providing an inappropriate answer.

## Tech Stack
* **Language:** Python
* **Libraries:** nltk, scikit-learn, numpy, string, random

## Detailed Repository Breakdown :
- VITyarthi_Project_CHATBOT_AIML.py contains the Program code
- ChatBot_AIML_VITyarthi_Project_Report.pdf contains the project resport
- Sample_Output.pdf contains the sample output executions

## How to Run the Project 
- **Step 1: Install Python**'

i. To install Python, please visit the website [python.org/downloads](https://www.python.org/downloads/).

ii. **Important for Windows users:** You must check the box that says **"Add Python to PATH"** at the bottom of the installation window.

- **Step 2: Download the Code**

i. To get the project's code, please click the green **"<> Code"** button in this repository and select **"Download ZIP"**.

ii. Extract the folder to your computer.

- **Step 3: Open Your Terminal**

i. **Windows:** Press the `Windows Key`, type `cmd`, and press `Enter`.

ii. **Mac:** Press `Command + Space`, type `Terminal`, and press `Enter`.

iii. Navigate to the unzipped folder using the `cd` command.

- **Step 4: Install Dependencies**

i. Run the following command on the terminal window to install the required libraries:
  `pip install numpy nltk scikit-learn`
  
- **Step 5: Run the Chatbot**

i.The chatbot can be started by executing the following command:
  `python VITyarthi_Project_CHATBOT_AIML.py`
  
- **Step 6: Chat!**

i. Just give Rudhran some time to introduce himself.

ii. Ask him any question you have in mind about Artificial Intelligence, for example: `What is deep learning?`

iii. To exit the conversation, just type:
    `bye! or thanks`

  
  
