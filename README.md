# 🦜🔗🤗  Search with LangChain, HuggingFace embeddings, Chroma, FAISS, Azure OpenAI and OpenAI

This project will help you learn the basics to -
- Index multiple documents in a repository using HuggingFace embeddings.
- Save the indexes in Chroma &  FAISS for recall.
- Cleanup / delete the indexes to start fresh.
- Query the FAISS and Chroma index / db.
- Search using embeddings (without having to sign up for any OpenAI) for similarity text snippets.
- Search with either OpenAI or Azure OpenAI.  You will use the "Which API would you like to use?" page to choose the API to use.
- Bonus: Get details on cost of the call (AI tokens and cost) and also get similar information document search on the store.

Link to the video recording - https://youtu.be/VaShd-0UoGg

# Setup the sample
To use the script, you will need to follow these steps:
- Clone the repository via `git clone https://github.com/ushakrishnan/SearchWithOpenAI.git` and `cd SearchWithOpenAI` into the cloned repository.
- Install the required packages: `pip install -r requirements.txt`
- Run `playwright install` to install playwright
- Copy the .env.template file to .env: `cp .env.template .env`. This is where you will set the following variables.
- Set your OpenAI API key in the OPENAI_API_KEY and Azure OpenAI details in the env file.  
   
# Run the sample
- Run the script: `streamlit run Home.py`

# What to expect
Streamlit will spin up a page that will look like this

<img src="/assets/start.gif" height=500>

Now go ahead, and ask you questions about the two "State of the Union" speech pdfs and txt you had indexed (some ideas - when were the speeches made? What were the dates that the speeches were made? Summarize both speeches in 100 words or less. What did the president say about affordable care act?)
<img src="/assets/page.png" height=500>

The new feature - Your own ChatGPT will be as below
<img src="/assets/chatgpt.gif" height=500>


# Packages used
- Streamlit - https://github.com/streamlit/streamlit
- LangChain - https://github.com/hwchase17/langchain
- OpenAI - https://github.com/openai/openai-python
- Chroma - https://github.com/chroma-core/chroma
- TikToken - https://github.com/openai/tiktoken
- pypdf - https://github.com/py-pdf/pypdf
- Unstructured - https://github.com/Unstructured-IO/unstructured
- Cython - https://github.com/cython/cython

Have fun creating making your own searchable library of PDFs.


## Contributing

This repository is for educational purposes only. However, if you find an error in the code, feel free to open an issue or submit a pull request.


## Issues

If you encounter any issues or have suggestions for improvements, please open an issue in the GitHub repository. We appreciate your feedback and will do our best to address any problems.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute the code as per the terms of the license.