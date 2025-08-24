# NLP Disaster Tweets Kaggle Mini-Project

This repository contains a mini-project focused on Natural Language Processing (NLP) using the Disaster Tweets dataset from Kaggle. The goal of this project is to classify tweets as either related to real disasters or not.

The dataset can be found on Kaggle: [Disaster Tweets Dataset](https://www.kaggle.com/c/nlp-getting-started/overview). The dataset files are included in the `data/` directory for convenience.

## Installing Dependencies

The project is using `uv` package manager. To install the required dependencies, run the following command:

```bash
uv sync
```

This will:

- Create a local virtual environment (.venv)
- Install all dependencies specified in pyproject.toml and uv.lock

You can then activate the virtual environment with:

```bash
source .venv/bin/activate   # Linux / macOS
.venv\Scripts\activate      # Windows
```