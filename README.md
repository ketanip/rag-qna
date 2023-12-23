# RAG QnA 🤖📊

In this project we use a Vector Database (Chroma DB) backed LLM Inference using LangChain to create a QnA system.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ketanip/VectorDB-LangChain-LLM)

*While running in `colab` use real OpenAI credentials for LLM inference.*

# Running it 

```bash
git clone https://github.com/ketanip/VectorDB-LangChain-LLM.git
```

Open `src/code.ipynb` and execute cells one by one.

# 🛠️ Tools used in this project:
1. 🔗 LangChain 
2. 📊 Vector Database ([Chroma DB](https://www.trychroma.com/)) 
3. 💡 LLM (Zephyr 7B β - Mistral Architecture) powered by [LM Studio](https://lmstudio.ai/). 

# 🚀 Features:
1. Loads data from the `raw_data` folder 📂.
2. Generates vector embeddings for the data and stores it in Chroma DB.
3. Searches relevant data based on the query 🔍.
4. Combines that data with the input question in a custom prompt template using LangChain.
5. Infers it using LLM and displays the results 🤖.
