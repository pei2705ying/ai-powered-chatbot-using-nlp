# AI-Powered Chatbot Using NLP

## Overview
This project is an **AI-powered chatbot** designed to answer **elementary and middle school scientific inquiries** through natural language conversations. It utilizes **Natural Language Processing (NLP) techniques** like **TF-IDF and Cosine Similarity** to match user queries with relevant answers from a pre-defined dataset.

## Features
- ✅ **Intent Classification** – Categorizes user queries into predefined intents (e.g., factual questions, small talk).
- ✅ **Natural Language Processing (NLP)** – Uses tokenization, lemmatization, and stop-word removal for query processing.
- ✅ **TF-IDF & Cosine Similarity** – Computes similarity between user queries and stored responses to find the best match.
- ✅ **Identity Management** – Recognizes and stores user names for personalized conversations.
- ✅ **Small Talk Integration** – Enhances the chatbot’s human-like interaction with casual conversations.
- ✅ **Typo Correction** – Handles minor spelling mistakes to improve response accuracy.

## Technology Stack
- **Python** – Core programming language
- **NLTK** – Used for NLP pre-processing
- **Scikit-learn** – Implements TF-IDF and Cosine Similarity
- **Pandas** – For data handling and analysis

## Usage
Clone the repository.
Install the required dependencies.
Run main.py.

## How It Works
1. **Preprocess User Input**
   - Tokenization: Breaks sentences into words
   - Lemmatization: Converts words to base forms
   - Stop-word Removal: Eliminates unnecessary words

2. **Compute Query Similarity**
   - Converts processed text into a **TF-IDF vector**
   - Uses **Cosine Similarity** to find the closest match

3. **Generate a Response**
   - Returns the **most relevant answer** from the knowledge base
   - If no strong match is found, the chatbot asks for clarification

## Usage
```
# Run the chatbot
python main.py
```
Then, start interacting with the chatbot by typing your questions!

## Evaluation & Performance
The chatbot was tested with:
- ✅ **Factual questions** – **80% accuracy**
- ✅ **Modified queries** – **100% accuracy**
- ✅ **Small talk responses** – **100% accuracy**
- ✅ **Modified small talk** – **80% accuracy**

## Challenges & Future Improvements
- 🔸 **Handling complex NLP syntax** – Variations in question phrasing may impact accuracy.
- 🔸 **Bias in dataset** – Trained primarily with US English, leading to potential inconsistencies for UK English users.
- 🔸 **Enhancing semantic understanding** – Improving response matching beyond keyword similarity using **word embeddings** (e.g., Word2Vec, BERT).

## Potential Impact
This chatbot can evolve into a **fact-based AI assistant** capable of retrieving and verifying data more efficiently than traditional search engines.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Pull requests are welcome! If you'd like to contribute, please fork the repository and use a feature branch. You can also open an issue for discussion.
