# (To)pic (Mo)delling (Co)mparison
A project aimed at comparing the results of topic modelling tasks performed with various techniques:
* `gensim` implementation of LDA (Latent Dirichlet Aloocation). 
* prodLDA: implemented using [Pyro](https://pyro.ai/).
* LLM_TopicModel (implemented): a generative AI powered topic model, directly outputting labels from input texts .
* [BERTopic](https://github.com/MaartenGr/BERTopic): a transformer-based topic model using BERT embeddings and clustering to extract topics from text.

The dataset used for this experiment is a [corpus of the UN debates](https://www.kaggle.com/datasets/namigabbasov/united-nations-general-debate-corpus-1946-2023) held throughout 1946-2023. 

# Requirements
* [Ollama installation](https://ollama.com/download) + downloading the DeepSeek model used in the code via Ollama CLI: `ollama pull deepseek-r1:8b`.
* packages in requirements.txt.

Having a GPU is reccomended to run LLM_TopicModel
