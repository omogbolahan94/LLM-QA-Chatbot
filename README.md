# INTRODUCTION 
Large Language Models (LLMs) generate text based on vast training data. Retrieval-Augmented-Generation (RAG) enhances LLMs by incorporating real-time information retrieval, combining LLM's generative capabilities with up-to-date, relevant data to produce more accurate and contextually informed responses.
In this project:
* **RETRIEVAL:** We will search for the top 5 documents from the documents.json file that are similer to a user's query based on most similar word using `elasticsearch` **key-word** search.
* **AUGMENTATION:** Create a prompt from this 5 searched documents by adding some context.
* **Generate:** Then generate a summarise content from this generated prompts using  google gemini model.

# ABOUT
* This project implemented a RAG (Retrieve Augmented and Generation) model.
* Elasticsearch is used to retrive document from a database (JSON in this regard) based on user query.
* This retrived documents is then used to generate a promp that would be passed in to an LLM model (gemini in this case).

# REQUIREMENT
* Docker to create and run elasticsearch image.
* Python 
* [Gemini API](https://ai.google.dev/gemini-api/docs/get-started/tutorial?lang=python). 
