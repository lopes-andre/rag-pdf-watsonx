# RAG: Using LLMs to talk to your PDFs

You'll learn, step-by-step, how to use LLMs to ask questions about your personal PDF files using a technique called RAG: Retrieval Augmented Generation.

## Making use of this repo

First, clone this GitHub repo. Make sure you create a [Python Virtual Environment](https://docs.python.org/3/library/venv.html) using Python @ version 3.10.

You can create your Virtual Environment (venv) by running.

```shell
python3.10 -m venv .venv
```

Activate your venv.

```shell
source .venv/bin/activate
```

Install all the dependencies.

```shell
pip3 install -r requirements.txt
```

Make sure you create a `.env` file with your IBM Cloud Credentials. You can start your free trial of the *watsonx.ai* [here](https://dataplatform.cloud.ibm.com/registration/stepone?context=wx).

Your `.env` file must have the following env variables:

```shell
API_KEY="<your_api_key>"
IBM_CLOUD_URL="https://us-south.ml.cloud.ibm.com"
PROJECT_ID="<your_project_id>"
```

Note that you must replace the placeholders above with your actual credentials - API Key and Project ID.

Now you can finally run Jupyter Notebooks and explore in depth the available didactic notebook.

```shell
jupyter notebook
```