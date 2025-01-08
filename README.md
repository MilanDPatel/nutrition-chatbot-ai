Created a nutrition/sports chatbot for users to ask queries to.
Full stack: Python, Flask, Pinecone, Langchain, OpenAI

- Compiled information from a pdf about nutrition/sports
- Utilized OPENAI Embeddings to create vectorizations of each chunk of information from the pdf.
- Stored vectorizations into a Pinecone vector database.
- Used semantic similarity to retrieve top three pieces of information similar to the user's query from the vector database.
- Plugged in the top three pieces of information into OpenAI's large language model
    - System prompt
    - Lang Chain to retrieve the user's answer
- Incorporated Flask for the User Interface of the chatbot
