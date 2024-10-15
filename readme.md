# NLP-Example Repository

This repository contains two Python scripts for Natural Language Processing (NLP) tasks and text summarization, as well as a requirements.txt file specifying the necessary dependencies.


## What is Natural Language Processing (NLP)?

Natural Language Processing (NLP) is a field of artificial intelligence that focuses on the interaction between computers and human language. It involves the development of algorithms and models that enable computers to understand, interpret, and generate human language text. NLP has a wide range of applications, including text classification, sentiment analysis, machine translation, and text summarization.

## Files:

1. **NLP_Text_Preprocessing.py**
   - This script demonstrates various text preprocessing techniques using the Natural Language Toolkit (NLTK) library.
   - It covers tokenization, removing stopwords, stemming, and more.
   
2. **TextSummarization_Preprocess.py**
   - This script builds on the previous one and adds a text summarization component.
   - It uses word frequency to score sentences and generates a summary from the input text.

## Requirements:

To run the scripts in this repository, make sure you have the following dependencies installed:

- click==8.1.7
- joblib==1.3.2
- nltk==3.8.1
- numpy==1.26.0
- regex==2023.8.8
- tqdm==4.66.1

You can install these dependencies using `pip` by running the following command:

```bash
pip install -r requirements.txt
```

## How to Run the Code:
1. Clone this repository to your local machine using Git:
```bash
git clone https://github.com/PabloMazurkiewicz/NLP-Text-Summarizer.git
```

2. Navigate to the repository directory:

```bash
cd NLP-Text-Summarizer
```

3. Install the required dependencies as mentioned above.

4. Run the desired Python script:

To run the NLP text preprocessing script, use:
```bash
python NLP_Text_Preprocessing.py
```

To run the text summarization script, use:
```bash
python TextSummarization_Preprocess.py
```