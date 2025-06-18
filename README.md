# Foreign-Media-Analysis
Sentiment and topic modeling of foreign media coverage of Turkey
This model works on the dataset provided by Murat Isik and Emrah Aydemir at Kaggle: https://www.kaggle.com/datasets/muratiik/news-about-turkey-from-bbc-cnn-tg-and-fox
1.) Sentiment Analysis (WM_Turkey_Foreign_Media_Analysis_P1_VADER.ipynb)
Sentiment analysis on news articles using the VADER tool.
2.) Topic Modeling and Sentiment-Topic Analysis (WM_Turkey_Foreign_Media_Analysis_P2_Topic_Sentiment.ipynb)
LDA to identify the main topics in the news articles and analyzes the sentiment associated with each topic,
3.) Validation (WM_Turkey_Foreign_Media_Analysis_P3_Validation.ipynb)
Validation of the results from the previous parts. VADER sentiment analysis is compared against a pre-trained Hugging Face Transformer model for robustness. Coherence of the identified topics is manually verified by examining sample articles.
