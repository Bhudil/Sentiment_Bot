# IMDb Reviews Sentiment Analysis Chatbot

## **Overview:**

This Python project implements a sentiment analysis chat bot for IMDb movie reviews. The chat bot uses a Naive Bayes classifier trained on a dataset of IMDb reviews to predict the sentiment of user input. The graphical user interface (GUI) is built using Tkinter, providing a user-friendly way to interact with the chat bot.
This project implements a sentiment analysis chatbot for IMDb reviews using Python. The chatbot analyzes the sentiment of user input and provides a predicted sentiment label along with an overall sentiment classification (positive, negative, or neutral).

## **Features:**
Sentiment Analysis: Utilizes a Multinomial Naive Bayes classifier and TF-IDF vectorization for sentiment analysis on IMDb movie reviews.

Graphical User Interface: Provides a Tkinter-based GUI for users to input movie reviews and receive predicted sentiments.

Real-time Interaction: Users can input multiple reviews in real-time, and the chat bot displays both user input and bot responses.

## **Code Structure:**
The code uses the pandas library to read the IMDb dataset and preprocess the data.

It then performs sentiment analysis using the TfidfVectorizer, MultinomialNB model from sklearn, and SentimentIntensityAnalyzer from nltk.

The chatbot function is defined to analyze the user's input and provide the sentiment analysis results.

Additionally, a graphical user interface (GUI) is created using the tkinter library to interact with the chatbot.

## **Dependencies:**
-Python 3.x

-pandas

-scikit-learn

-nltk

-tkinter

## **In-Application Layout:**

![Screenshot (126)](https://github.com/Bhudil/Sentiment_Bot/assets/99169324/9be0532d-e043-4061-8f41-21854759c6ca)

## **In-Application Use Case:**

![Screenshot (125)](https://github.com/Bhudil/Sentiment_Bot/assets/99169324/381a030e-9699-41b7-8f71-2b9cc6731a75)

## **Graphic User Interface:**

![Screenshot (124)](https://github.com/Bhudil/Sentiment_Bot/assets/99169324/19e81660-cd2c-478f-8c2f-550599a212b0)


## **GUI Use Case:**

![Screenshot (127)](https://github.com/Bhudil/Sentiment_Bot/assets/99169324/4c8dd98f-627c-4515-9109-53b4b96a78ed)


## **Usage:**
Setup: Ensure that the required libraries are installed. You can use the following command to install the necessary libraries:
bash
```
pip install pandas scikit-learn nltk
```

Run: Execute the main script to interact with the chatbot. You can use the following command to run the script:
bash
```
python sentiment_analysis_chatbot.py
```

**Interact: Upon running the script, the GUI will prompt you to enter a review. The chatbot will then provide the sentiment analysis results based on your input.**
