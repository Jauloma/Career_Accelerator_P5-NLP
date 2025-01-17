# Project : COVID Vaccine Tweet Sentiments Analysis

## Description

This Streamlit application aims to analyze sentiments in tweets related to COVID vaccines using pre-trained NLP models. The application allows users to input their own tweet or choose from provided examples to predict the sentiment of the text. The sentiment analysis is based on three models: BERT, DistilBERT, and RoBERTa, which are selected by the user. 

## Table of contents
- Summary
- Prerequisites
- How to Use
- Application Layout
- Sentiment Analysis
- Customization
- Conclusion
- Resources
- Acknowledgements
- Contacts

## Summary

| Code | Project Name | Published Article | Deployed App |
|------------------|------------------|------------------|------------------|
| LP5     |Sentiments Analysis     | https://medium.com/jaroyajo/fine-tuning-sentiment-analysis-models-for-covid-vaccine-tweet-sentiments-a-comprehensive-guide-cb2eb391b61c    | https://huggingface.co/spaces/UholoDala/Jj_Sentiment_Analysis_Ap     |



## Prerequisites
Before running the application, ensure you have the following dependencies installed:

- Python 3.6 or higher
- Streamlit
- Transformers
- NumPy
- SciPy
You can install these packages using pip:

- pip install streamlit transformers numpy scipy

## How to Use
1. Clone the repository and navigate to the project directory.

2. Run the Streamlit application using the following command:
        - streamlit run app.py
        The application will open in your default web browser.

## Application Layout
The application is designed to provide a user-friendly interface to analyze tweet sentiments. It consists of the following sections:

        1. Header Animation: A Lottie animation is displayed at the top of the page for a welcoming effect.

        2. Page Title: A centered title "Covid Vaccine Tweet Sentiments" is displayed using a large font.

        3. Description: A subheading "These models were trained to detect how a user feels about the covid vaccines based on their tweets(text)" provides a brief description of the application's purpose.

        4. User Input Form: A form is provided to accept user inputs. Users can either type or copy-paste a tweet into the text area. If they cannot provide their own input, they can select one from the provided examples using the dropdown.

        5. Model Selection: Users can choose from three pre-trained models (BERT, DistilBERT, and RoBERTa) to perform sentiment analysis on the tweet.

        6. Predict Button: A "Predict" button is available for users to submit their input and analyze the sentiment.

        7. Output Columns: Three columns are displayed to show the results of sentiment analysis:

                - Sentiment Emoji: An animated emoji is displayed based on the predicted sentiment (positive, negative, or neutral).
                - How this user feels about the vaccine: The predicted sentiment label (POSITIVE, NEGATIVE, or NEUTRAL) is shown.
                - Confidence of this prediction: The confidence score of the prediction is displayed as a percentage.

## Sentiment Analysis
Once the user submits their input and selects a model, the application processes the text input using the selected model and displays the sentiment analysis results. The model predicts whether the input text reflects a positive, negative, or neutral sentiment towards COVID vaccines.

The sentiment analysis is done by leveraging the Hugging Face Transformers library. The pipeline function is used to easily load the appropriate model for the selected sentiment classification task.

## Customization

To personalize the application further, you can modify the following aspects:

### Background Color: 
The background color is set to gray. You can change it to any desired color by updating the custom_css variable in the code.

### Font Family: 
The application uses the 'Arial' font family. You can change it to any other font family by updating the custom_css variable.

### Page Title and Subheading: 
You can modify the page title and subheading text to better suit your application.

### Lottie Animations: 
The application displays different Lottie animations based on the predicted sentiment. You can change the animations or remove them altogether by modifying the corresponding URL in the code.

## Conclusion

The Streamlit application serves as a powerful tool to quickly analyze sentiments in COVID vaccine-related tweets using state-of-the-art NLP models. By providing a user-friendly interface and pre-trained models, it allows users to gain insights into public sentiments towards COVID vaccines in real-time. Additionally, the code can be easily customized and extended to incorporate more models or different analysis tasks in the future.

## Resources
1. [Quick intro to NLP](https://www.youtube.com/watch?v=CMrHM8a3hqw)
1. [Getting Started With Hugging Face in 15 Minutes](https://www.youtube.com/watch?v=QEaBAZQCtwE)
1. [Fine-tuning a Neural Network explained](https://www.youtube.com/watch?v=5T-iXNNiwIs)
1. [Fine-Tuning-DistilBert - Hugging Face Transformer for Poem Sentiment Prediction | NLP](https://www.youtube.com/watch?v=zcW2HouIIQg)
1. [Introduction to NLP: Playlist](https://www.youtube.com/playlist?list=PLM8wYQRetTxCCURc1zaoxo9pTsoov3ipY)
<!-- 1. [](https://www.youtube.com/)
1. [](https://www.youtube.com/) -->

## Acknowledgements
We are glad and appreciate the opportunity given to us by Azubi Afica to participate in this endeavour.

## Contacts
1. Jacob O. Jaroya

jaroyajo@gmail.com

https://www.linkedin.com/in/jjaroya/

https://github.com/Jauloma/Career_Accelerator_P5-NLP

2. Felix Kiprotich

3. Sylvester Ampomah

4. Kingsley Yaw Siedu

5. Jedida M. Kisiang'Ani