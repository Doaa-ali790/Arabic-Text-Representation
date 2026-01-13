Text Representation Techniques on Surah Al-Fatiha
📌 Project Description

This project applies several text representation techniques on Surah Al-Fatiha from the Holy Quran.
The goal is to understand and compare how different NLP techniques represent textual data numerically.

The following techniques are implemented:

Bag of Words (BOW)

TF-IDF

Word2Vec

BERT (Arabic Pre-trained Model)

🧠 Applied Techniques
1️⃣ Bag of Words (BOW)

Represents text based on word frequency without considering context or word order.

Output:

Word frequency list

BOW matrix per verse

2️⃣ TF-IDF

Assigns weights to words based on their importance in the text by combining:

Term Frequency (TF)

Inverse Document Frequency (IDF)

Output:

TF-IDF weights for each word

TF-IDF matrix per verse

3️⃣ Word2Vec

Learns vector representations of words based on their surrounding context.

Output:

Vector embedding for each word

4️⃣ BERT (Bidirectional Encoder Representations from Transformers)

A deep contextual language model that generates embeddings for words based on their meaning within context.

Arabic pre-trained model used:
asafaya/bert-base-arabic

Embedding size: 768 dimensions

⚠️ Due to the large size of the BERT model, embeddings were generated using Google Colab, and only the final results were saved and included in this repository.

Output:

Contextual embeddings per verse saved in a text file

📁 Project Structure
project/
│
├── data/
│   └── surah.txt
│
├── bow.py
├── tfidf.py
├── word2vec.py
├── bert.py
│
├── results/
│   ├── bow_results.txt
│   ├── tfidf_results.txt
│   ├── word2vec_results.txt
│   └── bert_results.txt
│
└── README.md

🛠 Tools & Libraries

Python

NumPy

scikit-learn

gensim

transformers

PyTorch

Google Colab (for BERT embeddings)

✅ Notes

The BERT model files are not included in this repository due to their large size.

Only the generated embeddings and results are provided.

This project is for educational and academic purposes.
