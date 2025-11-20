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
* [01-preparation.ipynb](01-preparation.ipynb): Vorbereitung des Datensets, nur als Beispiel, so nicht lauffähig.
* [02-bert-classification.ipynb](02-bert-classification.ipynb): Finetuning eines BERT-Modells zur Klassifikation der Newsticker-Meldungen
* [02-bert-classification-EuroBERT.ipynb](02-bert-classification-EuroBERT.ipynb): Finetuning eines alternativen BERT-Modells zur Klassifikation der Newsticker-Meldungen
* [03-svm.ipynb](03-svm.ipynb): Training einer SVM zum Vergleich

### BERT-Embeddings nutzen
* [10-data-text-preparation.ipynb](10-data-text-preparation.ipynb): Vorbereitung des UN-Korpus
* [11-similarity-embeddings.ipynb](11-similarity-embeddings.ipynb): Berechnung der Embeddings und Suche
* [12-similarity-vectordb.ipynb](12-similarity-vectordb.ipynb): Nutzung einer Vektor-Datenbank
* [21-similarity-tantivy.ipynb](21-similarity-tantivy.ipynb): Lexikalische Suche
* [22-similarity-rrf.ipynb](22-similarity-rrf.ipynb): Reciprocal Rank Fusion zur Vereinheitlichung der Ergebnislisten
* [23-similarity-cross-encoder.ipynb](23-similarity-cross-encoder.ipynb): Optimierung mit Cross-Encoder
 
### BERT-Embeddings finetunen
* [31-sbert-finetune.ipynb](31-sbert-finetune.ipynb): Finetuning eines BERT-Modells für Ähnlichkeit
* [32-create-sbert-data-qwen-reranker.ipynb](32-create-sbert-data-qwen-reranker.ipynb): Optimierung des Datensets oder Erzeugung eigener Datensets
* [33-sbert-finetune-qwen-reranker.ipynb](33-sbert-finetune-qwen-reranker.ipynb): Fientuning mit dem optimierten Datenset

### Generative Modelle nutzen
* [41a-qwen-8b.ipynb](41a-qwen-8b.ipynb): Generative Modelle funktionieren nicht ohne die richtigen Optionen
* [41b-qwen-8b.ipynb](41b-qwen-8b.ipynb): Hier mit den richtigen Optionen
* [42-qwen-8b-exl2.ipynb](42-qwen-8b-exl2.ipynb): Deutlich schneller mit exl2
* [43-vllm-direct.ipynb](43-vllm-direct.ipynb): Nutzung von `vllm` als Bibliothek
* [44-vllm-direct-awq.ipynb](44-vllm-direct-awq.ipynb): Nutzung von AWQ-quantisierten Modellen mit `vllm`
* [45-vllm-api.ipynb](45-vllm-api.ipynb): Nutzung von `vllm` als API

### Generative Modelle finetunen
* [51a-qwen3-07-full-finetune.ipynb](51a-qwen3-07-full-finetune.ipynb): Voller Finetune mit Qwen3 700 Millionen
* [51b-qwen3-07.ipynb](51b-qwen3-07.ipynb): Ausführen des finegetuneten Modells
* [52a-llama32-1-huggingface.ipynb](52a-llama32-1-huggingface.ipynb): LoRA-Finetuning eines Llama-Modells mit 1,7 Milliarden Parametern
* [52b-llama32-1.ipynb](52b-llama32-1.ipynb): Ausführen des finegetuneten Modells
* [53a-smolm-1-huggingface.ipynb](53a-smolm-1-huggingface.ipynb): LoRA-Finetuning von SmoLm mit 1,7 Milliarden Parametern
* [53b-smolm-1.ipynb](53b-smolm-1.ipynb): Ausführen des finegetuneten Modells
* [54a-phi3-unsloth.ipynb](54a-phi3-unsloth.ipynb): LoRA-Finetuning eines Phi 3.5 Modells mit ~ 4 Milliarden Parametern
* [54b-phi3.ipynb](54b-phi3.ipynb): Ausführen des finegetuneten Modells
