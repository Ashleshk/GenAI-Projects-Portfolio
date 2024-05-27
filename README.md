# GenAI-Projects-Portfolio
The GenAI Projects Portfolio repository is collection of projects leveraging Generative AI and Large Language Models (LLMs). These projects demonstrate various applications and innovations in AI-driven solutions, highlighting the potential and versatility of generative AI technologies

# Project-1 : Text Summarizer


In this Project, I delved into the **impact of input text on model output**, employing **prompt engineering** to steer the model towards specific tasks. By comparing **zero-shot**, **one-shot**, and **few-shot** inferences, I aim to unlock the full potential of prompt engineering, enhancing the generative capabilities of **Large Language Models**.

Steps
1. Summarize Dialogue
2. fine-tune an existing LLM from Hugging Face (FLAN-T5) for enhanced dialogue summarization, PEFT
3. Fine-Tune FLAN-T5 with Reinforcement Learning (PPO) and PEFT to Generate Less-Toxic Summaries

# Project-2 : Retrieval-Augmented Generation (RAG)

In this part, I am implementing the full workflow of **RAG** using text vectorization, vector search, and the question-answering workflow. While I use [FAISS](https://faiss.ai/) (vector library) and [ChromaDB](https://docs.trychroma.com/) (vector database), and a Hugging Face model.

# Project-3 : Building Multi-stage Reasoning Systems with LLM Chains

* The first, code named `JekyllHyde` will be a prototype AI self-commenting-and-moderating tool that will create new reaction comments to a piece of text with one LLM and use another LLM to critique those comments and flag them if they are negative. To build this we will walk through the steps needed to construct prompts and chains, as well as multiple LLM Chains that take multiple inputs, both from the previous LLM and external. 
* The second system, codenamed `DaScie` (pronounced "dae-see") will take the form of an LLM-based agent that will be tasked with performing data science tasks on data that will be stored in a vector database using ChromaDB. We will use LangChain agents as well as the ChromaDB library, as well as the Pandas Dataframe Agent and python REPL (Read-Eval-Print Loop) tool.

Steps:
1. Build prompt template and create new prompts with different inputs
2. Create basic LLM chains to connect prompts and LLMs.
3. Construct sequential chains of multiple `LLMChains` to perform multi-stage reasoning analysis. 
4. Use langchain agents to build semi-automated systems with an LLM-centric agent to perform internet searches and dataset analysis.

# Project-4 : LLMOps
I am walking through some key steps for taking an LLM-based pipeline to production. This pipeline will be familiar to - previous modules: **Summarization of news articles** using a pre-trained model from Hugging Face.

Steps: 
1. Walk through a simple but realistic workflow to take an LLM pipeline from development to production.
2. Make use of MLflow Tracking and the Model Registry to package and manage the pipeline.
3. Scale out batch inference using Apache Spark and Delta Lake.

# Common Applications with LLMs
In this notebook, we'll take a whirlwind tour of some top common applications using Large Language Models (LLMs):
* Summarization
* Sentiment analysis
* Translation
* Zero-shot classification
* Few-shot learning