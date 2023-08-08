##This is a useable implementation of the tutorial found at: https://platform.openai.com/docs/tutorials/web-qa-embeddings

The order of execution is crawler.py -> parser_1.py -> embedder.py -> qna.py

embedder.py and qna.py need OpenAI API Keys to function

embedder.py will take 5 or so minutes to execute

the output of embedder.py should be stored in a vector database for production use cases (see: https://platform.openai.com/docs/guides/embeddings/how-can-i-retrieve-k-nearest-embedding-vectors-quickly)