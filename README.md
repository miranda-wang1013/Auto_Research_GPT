# README for Auto_Research_GPT
This is an AI-powered research agent that efficiently extracts and summarizes web content to assist in comprehensive research tasks.

# Overview
This project is a sophisticated Twitter Thread Generator designed to automate the process of creating engaging and informative Twitter threads on specific topics. It leverages advanced NLP (Natural Language Processing) techniques and APIs to fetch relevant articles, summarize their content, and generate compelling Twitter threads.

# Features
- **Automated Article Retrieval:** Utilizes the SerpAPI to search and retrieve a list of relevant articles based on user queries.
- **Intelligent Article Selection:** Employs a model-based approach to choose the best articles for summarization.
- **Content Summarization:** Uses OpenAI's GPT-3.5 model to summarize the content of selected articles.
- **Thread Generation:** Generates a Twitter thread that is engaging, concise, and tailored to the specific query, ensuring it adheres to Twitter's format and is likely to garner significant engagement.

# Prerequisites
To run this project, you need:
1.Python 3.x
2.An active internet connection
3.API keys for OpenAI and SerpAPI

# Installation
- **1.Clone the repository:**
git clone git@github.com:miranda-wang1013/Auto_Research_GPT.git

- **2.Navigate to the project directory:**
cd twitter-thread-generator

- **3.Install required dependencies:**
pip install -r requirements.txt

- **4.Setting Up Environment Variables：**
Create a .env file in the project root.

- **5.Add your SerpAPI and OpenAI API keys:**
SERPAPI_API_KEY=your_serpapi_key_here
OPENAI_API_KEY=your_openai_key_here

- **6.Start the application:**
streamlit run your_script_name.py
Open the provided local URL in your web browser.
Enter a topic in the input field to generate a thread.

# Components
- **Streamlit Interface:** Offers a user-friendly interface to input queries and view the generated threads.
- **SerpAPI Integration:** Fetches relevant articles based on user queries.
- **OpenAI GPT-3.5 Turbo:** Powers the article summarization and thread generation.

# Contributions
Contributions, issues, and feature requests are welcome. Feel free to check the issues page for any open issues or to open a new one.

# License
Distributed under the MIT License. See LICENSE for more information.

# Contact
Your Name - miranda_wang@foxmail.com or huijiawang1023@gmail.com

