
# Project Title

This project, led by *Markus Lang* or *Coding Crash Courses* demonstrates AI and language model applications using LangChain and OpenAI. It covers model interactions, vector indexing, memory management, and agent creation. Suitable for beginners and experienced practitioners.
## Installation

Install required packages:

```bash
  pip install -r requirements.txt
```
Set up your OpenAI API key in a .env file:
```bash
  OPENAI_API_KEY=your_api_key_here
```
    
## Usage


- **`models_prompts_parsers.ipynb`**: Uses OpenAI and LangChain to demonstrate model initialization, prompt templates (`ChatPromptTemplate`), and structured output parsing (`ResponseSchema`, `StructuredOutputParser`).
- **`memory.ipynb`**: Explores conversation memory using LangChain's `ChatMessageHistory`, `ConversationBufferMemory`, and `ConversationChain` for context retention in language models.
- **`models_basics.ipynb`**: Introduces OpenAI's API usage, focusing on chat completions and temperature settings for controlling randomness in outputs.
- **`indexes.ipynb`**: Implements vector indexing using FAISS and LangChain, demonstrating document loading (`DirectoryLoader`), text splitting (`RecursiveCharacterTextSplitter`), and embedding generation (`OpenAIEmbeddings`) for efficient information retrieval.
- **`evaluations.ipynb`**: Utilizes LangChain's `ContextQAEvalChain` for evaluating language model outputs, including creating evaluation prompts and grading model responses.
- **`agents.ipynb`**: Explores LangChain's agent framework, including tool creation (`CustomSearchTool`), agent initialization (`initialize_agent`), and zero-shot reasoning (`ZeroShotAgent`) for task completion.
- **`chains.ipynb`**: Demonstrates LangChain's chain operations, including `SequentialChain` and `LLMChain`, for creating complex workflows combining multiple language model tasks.

- **`chatgpt_plugins.ipynb`**: Illustrates the integration of ChatGPT plugins using LangChain's `AIPluginTool`, focusing on the Wolfram Alpha plugin as an example.


## Contributing

Contributions to this project are welcome. If you have any suggestions, feel free to create an issue or submit a pull request.

