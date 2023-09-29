# Building  Apps with watsonx.ai and Streamlit! Langchain + PDF model seeding
Using Langchain's chaining ability, we can seed our model with the word embeddings extracted from an uploaded pdf file. This project shows how to use streamlit to make a frontend UI to interact with watsonx's Langchain PDF question/answer functionality.

![](images/time-at-ibm.png)

# Startup 🚀
1. Open your terminal or console window
2. cd into this project's base directory
3. Copy your .env file into this lab's base folder
   
Your .env should look something like.
```
GENAI_KEY=pak-***
GENAI_API=https://us-south.ml.cloud.ibm.com/
```
4. Set up and activate the python virtual environment.
```Bash
python3 -m venv pdf-venv
source pdf-venv/bin/activate
pip3 install -r requirements.txt
```
5. Execute the app by running the command: `streamlit run app_watsonx_GA.py`

# Other References 🔗
<p>-<a href="https://workbench.res.ibm.com/docs/ibm-generative-ai">IBMGen Documentation</a>:documentation for the IBMGen library available through the tech preview UI.</p>
<p>-<a href="https://github.com/IBM/ibm-generative-ai#langchain-extension">IBMGen Langchain Extension</a>:Langchain is a highly popular LLM library, it's used to structure prompt chains and llm workflows. In this tutorial we use the IBMGen langchain extension to generate responses.</p>


