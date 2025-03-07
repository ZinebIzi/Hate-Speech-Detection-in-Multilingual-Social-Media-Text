# Hate-Speech-Detection-in-Multilingual-Social-Media-Text
In this project, we focused on developing a hate speech detection model using transformer-based architec-
tures, specifically mBERT (Multilingual BERT) and XLM-R (Cross-lingual Language Model – RoBERTa).
These models leverage pre-trained deep learning techniques to understand contextual representations in multiple languages, making them well-suited for detecting hate speech in diverse online discussions. Addi-
tionally, we implemented a web application using Streamlit to present the results, allowing users to input text and analyze predictions interactively. The objective of this study is to compare the performance of these two models on real-world datasets, such as Twitter and Facebook comments, and to evaluate their effectiveness in detecting hate speech across different languages.

# Features
- Multilingual Hate Speech Detection (Supports English, German, and Turkish)
- Fine-tuned Transformer Models (mBERT & XLM-RoBERTa)
- Web Interface using Streamlit for real-time text analysis
# Dataset
This dataset contains hate speech text with labels where 0 represents non-hate and 1 shows hate
texts also the data from different languages needed to be identified as a corresponding
correct language. The following are the languages in the dataset with the numbers corresponding to that language.
(1 Arabic)(2 English)(3 Chinese)(4 French) (5 German) (6 Russian)(7 Turkish) (8 Roman Hindi/Urdu) (9 Korean)(10 Italian) (11 Spanish)(12 Portuguese) (13 Indonesian).
https://www.kaggle.com/datasets/wajidhassanmoosa/multilingual-hatespeech-dataset?resource=download

In this project we focused on three languages: English, German, and Turkish.

# Model Training
- mBERT: Achieved 62.99% accuracy, indicating moderate multilingual performance.
- XLM-RoBERTa: Achieved 87% accuracy, demonstrating stronger cross-lingual capabilities.

# Deployment
The trained model is deployed as a Streamlit web application, allowing users to input text and receive real-time classification results with confidence scores.

# Installation & Usage:

-  Clone the Repository
     
    git clone https://github.com/your-repo/Hate-Speech-Detection-in-Multilingual-Social-Media-Text
   
    cd Hate-Speech-Detection-in-Multilingual-Social-Media-Text

-  Run the Streamlit App
  
    streamlit run APP.py

  
# Future Improvements
Expand support to more languages.
Address data imbalance to improve performance on underrepresented languages.
Optimize deployment for real-world applications


