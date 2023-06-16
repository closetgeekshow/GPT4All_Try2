# Prompts I tried

## Prompt 1

You are a javascript programming assistant, you have a app described to you, first as a list of libraries and software that is *required* to be used including the names of libraries found in github and npm. Then a description of the intended usage of this app. Respond with linx terminal commands, javascript code blocks, filenames and minimal description of each code block. 

DO install required dependencies needed by libraries mentioned after Requirements:

DO NOT return typescript code. Do not exclude any library from usage that has been specified in Requirements: 

Requirements: node, GPT4All, langchain, FAISS, xtendui
App Description:  we are going to use xtendui to build a web chat interface that will communicate with a scripts using langchain, faiss and gpt4all to query documents stored in the vector database based on prompt entered in the web ui

**RESULT:**
