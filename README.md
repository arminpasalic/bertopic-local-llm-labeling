# BERTopic with Local LLM Labeling

This repo accompanies my Medium article:  
[BERTopic with Local LLM Labeling (Llama.cpp + Ollama): A Practical Guide](https://medium.com/@arminpasalictz/45314e80d723)

## Features
- Topic modeling with BERTopic  
- Embeddings via SentenceTransformers  
- Clustering (UMAP + HDBSCAN)  
- Flexible labeling using Llama.cpp + Ollama
  
## Usage
Open the provided Jupyter notebook: `01_labeling_workflow_demo.ipynb`

##
BERTopic: https://github.com/MaartenGr/BERTopic
UMAP: https://github.com/lmcinnes/umap
HDBSCAN: https://github.com/scikit-learn-contrib/hdbscan
Stopwordsiso: https://github.com/stopwords-iso/stopwords-iso
LLAMA-CPP: https://github.com/ggml-org/llama.cpp
OLLAMA: https://github.com/ollama/ollama
KOBOLD-CPP - is another really good alternative to LLAMA-CPP and easier to install: https://github.com/LostRuins/koboldcpp

## Install
```bash
pip install -r requirements.txt
```
