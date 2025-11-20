# KI Navigator 2025 - Workshop "Eigene Sprachmodelle"

## Präsentation

## Python-Installation

Am besten verwendet ihr [`uv`](https://astral.sh/uv) und 
ruft dann `uv sync` auf. Falls das nicht möglich ist, 
bitte `miniconda` installieren oder eine andere 
Python-Installation mit `pip` verwenden. Ihr könnt dann 
`pip install -a requirements.txt` aufrufen, aber 
möglicherweise gibt es aktualisierte Abhängigkeiten. 
Besser also folgende Pakete installieren:

* autoawq
* bitsandbytes
* exllamav2
* flash-attn
* ipykernel==6.30.1",
* ipython
* ipywidgets
* jupyter
* liger-kernel
* matplotlib
* openai
* pandas
* peft
* pip
* sentence-transformers
* sglang
* spacy
* tantivy
* tqdm
* transformers
* trl
* unsloth
* usearch
* vllm

## Notebooks

Ihr könnt die Notebooks entweder direkt ausführen oder einfach
mit anschauen und später zur Dokumentation nutzen.

### BERT-Klassifikation finetunen
[01-preparation.ipynb](01-preparation.ipynb)
[02-bert-classification.ipynb](02-bert-classification.ipynb)
[02-bert-classification-EuroBERT.ipynb](02-bert-classification-EuroBERT.ipynb)
[03-svm.ipynb](03-svm.ipynb)

### BERT-Embeddings nutzen
[10-data-text-preparation.ipynb](10-data-text-preparation.ipynb)
[11-similarity-embeddings.ipynb](11-similarity-embeddings.ipynb)
[12-similarity-vectordb.ipynb](12-similarity-vectordb.ipynb)
[21-similarity-tantivy.ipynb](21-similarity-tantivy.ipynb)
[22-similarity-rrf.ipynb](22-similarity-rrf.ipynb)
[23-similarity-cross-encoder.ipynb](23-similarity-cross-encoder.ipynb)

### BERT-Embeddings finetunen
[31-sbert-finetune.ipynb](31-sbert-finetune.ipynb)
[32-create-sbert-data-qwen-reranker.ipynb](32-create-sbert-data-qwen-reranker.ipynb)
[33-sbert-finetune-qwen-reranker.ipynb](33-sbert-finetune-qwen-reranker.ipynb)

### Generative Modelle nutzen
[41a-qwen-8b.ipynb](41a-qwen-8b.ipynb)
[41b-qwen-8b.ipynb](41b-qwen-8b.ipynb)
[42-qwen-8b-exl2.ipynb](42-qwen-8b-exl2.ipynb)
[43-vllm-direct.ipynb](43-vllm-direct.ipynb)
[44-vllm-direct-awq.ipynb](44-vllm-direct-awq.ipynb)
[45-vllm-api.ipynb](45-vllm-api.ipynb)

### Generative Modelle finetunen
[51a-qwen3-07-full-finetune.ipynb](51a-qwen3-07-full-finetune.ipynb)
[51b-qwen3-07.ipynb](51b-qwen3-07.ipynb)
[52a-llama32-1-huggingface.ipynb](52a-llama32-1-huggingface.ipynb)
[52b-llama32-1.ipynb](52b-llama32-1.ipynb)
[53a-smolm-1-huggingface.ipynb](53a-smolm-1-huggingface.ipynb)
[53b-smolm-1.ipynb](53b-smolm-1.ipynb)
[54a-phi3-unsloth.ipynb](54a-phi3-unsloth.ipynb)
[54b-phi3.ipynb](54b-phi3.ipynb)
