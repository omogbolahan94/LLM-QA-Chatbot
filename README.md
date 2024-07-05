# INTRODUCTION 
Large Language Models (LLMs) generate text based on vast training data. Retrieval-Augmented Generation (RAG) enhances LLMs by incorporating real-time information retrieval, combining LLM's generative capabilities with up-to-date, relevant data to produce more accurate and contextually informed responses.

# ABOUT
* This project implemented a RAG (Retrieve Augmented and Generation) model.
* Elasticsearch is used to retrive document from a database (JSON in this regard) based on user query.
* This retrived documents is then used to generate a promp that would be passed in to an LLM model (gemini in this case).

