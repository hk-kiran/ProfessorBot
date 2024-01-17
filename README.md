Production level implementation: https://github.com/hk-kiran/multiinstancellm

# Welcome to our CS205 Final Project!
## This project will walk you through one of the hottest areas of Computer Science today - LLMs!
### To start with, we will introduce HuggingFace Transformers library, and how to make use of it to generate text from a prompt. We will explore some of the important concepts behind LLMs like embeddings. 

#### Installations

If you already have Conda setup, run the below command in the root directory to set up the environment

```
make -f Makefile
```

#### Install the Python packages 

```
pip install -r requirements.txt 
```

#### Ollama 

Install [Ollama](https://ollama.ai/download). Follow the instructions and install Ollama locally. Run the Llama 2 7B with the command. It will serve Llama 2 on port 11434

```
ollama run llama2
```

#### Llama Index 
- Indexing and Vector Storage library
#### Langchain
- TODO
#### ChromaDB 
- Vector Database

Create a database of PDFs (we've used some chapters from Artificial Intelligence: A Modern Approach) and save it in a directory 'data' at the root of this project. This creates a private knowledge database for the LLM
