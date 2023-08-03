# Sentiment Analysis using BERT

This project demonstrates sentiment analysis using BERT (Bidirectional Encoder Representations from Transformers), a state-of-the-art transformer-based model for natural language processing tasks. The program is designed to perform sentiment classification on movie reviews to predict whether the sentiment is positive or negative.

## Usage

1. **Imports**: The program starts with importing the necessary libraries for the analysis, including TensorFlow, NumPy, Matplotlib, Sklearn, Gensim, and more.

2. **Data Preparation**: The IMDb dataset is used for sentiment analysis. The data is tokenized and encoded to prepare it for input into the BERT model.

3. **Modeling**: The program creates a custom sentiment analysis model based on BERT. The model utilizes binary classification to predict whether the sentiment is positive or negative.

4. **Training**: The model is trained using the IMDb dataset. The training process includes optimization using the Adam optimizer and a learning rate schedule.

5. **Testing**: After training, the model can be tested on new movie reviews. The sentiment of the provided text will be predicted as either positive or negative.

## Note

- Ensure GPU support is enabled for better performance during training and testing.

- The dataset used in this program is IMDb, but you can modify the code to use your custom dataset for sentiment analysis.

Enjoy performing sentiment analysis on movie reviews with BERT!
