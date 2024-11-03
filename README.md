# NLP-LLM-and-text-summarization
The code is a part of the Text mining course Labs.

Large language models (LLMs) are deep neural networks trained on the language modelling task over massive amounts of text data.\
Analyse token and sentence representations from a language model of the “BERT” family of models.
The code includes:
- prepared a data set containing a small sample of sentences from DBpedia
- Contextualized word embeddings
  - Extracting specific embeddings
  - Plotting embeddings with t-SNE
- Sentence embeddings
- Extractive summarization
  - Extracting sentence embeddings
  - Extractive summarization with MMR
- Evaluation of summarization
  - Implementing ROUGE-2
  - Evaluating extractive summarization against a baseline
- Abstractive summarization
  - Prompt construction
  - Generating the abstractive summaries & evaluating
  - Sampling from the probability distribution  

## Libs
!pip install torch\
!pip install transformers\
import os\
from ctransformers import AutoModelForCausalLM, AutoTokenizer
