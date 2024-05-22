# langserve-gcloud-deployment-demo

## Installation and Setup


**Step 1: Clone the repository**

```bash
git clone https://
cd langserve-gcloud-deployment-demo
```

**Step 2: Create and activate a conda environment**

```bash
conda create -n langserve-gcloud python=3.12.3
conda activate langserve-gcloud
```

**Step 3: Install the required packages using poetry**

```bash
pip install poetry
poetry install
```

Note: If you get the error message `'poetry' is not recognized as an internal or external command` even after installing poetry, try to create a new conda environment and install poetry again.

**Step 4: Run the application**

```bash
poetry run langchain serve --port=8080
```

You can now access the application at `http://localhost:8080`. 
Documentation is available at `http://localhost:8080/docs`.
Playground is available at `http://localhost:8080/openai/playground`.


## Deployment to Google Cloud

Read the [deployment guide](https://example.com) to deploy the application to Google Cloud.
