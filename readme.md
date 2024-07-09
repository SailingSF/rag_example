## Example of an Earnings Transcript RAG App

This notebook contains example code for developing a RAG app in an financial assistant and is part of [this](https://goodatinvesting.xyz/website/earnings_rag_app.html) blog post.

This example uses Pinecone as the vector database and defines a tool for an OpenAI assistant that enables one to query context from stored earnings transcripts stored as vectors. The automation comes from defining a python function where an AI assistant can call the function in order to receive relevant context.

There is a sample query against the index to show how vector search works.

In order to use this functionality in an AI assistant a python function is writted to take arguments that query and filter the index and then return a standardized dictionary to provide additional context to the AI assistant.

