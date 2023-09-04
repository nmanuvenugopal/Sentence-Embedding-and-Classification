# Sentence-Embedding-and-Classification
Sentence embedding with Universal Sentence Encoder (USE), InferSent, SBERT (Sentence-BERT) and then classifying the embedded input using the same or different transformer model.

**Universal Sentence Encoder (USE)**: Developed by Google. It's available in two versions: USE-Base and USE-Large.

**InferSent**: InferSent is a sentence embedding model developed by Facebook AI Research (FAIR). It's trained on natural language inference data and is known for producing semantically meaningful sentence representations.

**SBERT (Sentence-BERT)**: SBERT is an extension of BERT that focuses specifically on sentence embeddings. It fine-tunes BERT for sentence similarity tasks, enabling it to generate embeddings that capture semantic meaning and relationships between sentences.

for working with sentence embedding we need to install sentence transformers
![image](https://github.com/nmanuvenugopal/Sentence-Embedding-and-Classification/assets/99719105/f2e54eef-c4f9-49a7-a91d-e486d9c79a4c)

Specify the sentence mebedding transformer model that we are going to use.
![image](https://github.com/nmanuvenugopal/Sentence-Embedding-and-Classification/assets/99719105/c33eaf7b-2b14-4d85-8158-ae9ae60f66c9)

Renaming the model to the name we need. by default the model will be named as 'pytorch_model.bin'
![image](https://github.com/nmanuvenugopal/Sentence-Embedding-and-Classification/assets/99719105/7bf35a87-f646-4819-b8f3-1ed7ebe3707a)

Splliting or sentence tokenize using the sent_tokenize function
![image](https://github.com/nmanuvenugopal/Sentence-Embedding-and-Classification/assets/99719105/36add19b-7eb6-4d5d-a18a-f20682e507be)

finally embedding each sentences into numrical vectors.
![image](https://github.com/nmanuvenugopal/Sentence-Embedding-and-Classification/assets/99719105/f07f404a-c207-42ca-9f20-bcfd8605f885)

