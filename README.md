# chatgpt-retrieval

Simple script to use ChatGPT on your own files.

## Installation

Install [Langchain](https://github.com/hwchase17/langchain).
```
pip install langchain
pip install openai
pip install chromadb
pip install tiktoken

#or just run:

 pip install -r requirements.txt --no-cache
```
Modify `constants.py` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys).

Place your own data into `data.txt`.

## Example usage
```
> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
```

This is using chroma vector db:

https://alphasec.io/summarize-documents-with-langchain-and-chroma/


Here's the [YouTube Video](https://youtu.be/9AXP7tCI9PI).
