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

## References
- [BERTopic](https://github.com/MaartenGr/BERTopic)  
- [UMAP](https://github.com/lmcinnes/umap)  
- [HDBSCAN](https://github.com/scikit-learn-contrib/hdbscan)  
- [Stopwords-ISO](https://github.com/stopwords-iso/stopwords-iso)  
- [llama.cpp](https://github.com/ggml-org/llama.cpp)  
- [Ollama](https://github.com/ollama/ollama)  
- [KoboldCPP](https://github.com/LostRuins/koboldcpp) — a good alternative to llama.cpp and easier to install


## Install
```bash
pip install -r requirements.txt
```
