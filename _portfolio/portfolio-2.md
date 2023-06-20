---
title: "Emotion & Cryptocurrency"
excerpt: "This work is about the emotion detect in cryptocurrency market,which aims to compare ML-based and Lexicon-based methods' accuracy. <br/><img src='/images/emotion.png'>"
collection: portfolio
---

This is an improved research plan based on my course project. Specifically, it uses **sentiment information** from daily tweets about Bitcoin on social platforms and historical price information of the day as features to predict **whether the closing price of the day will rise or fall**. Essentially, this is a **sentiment classification task**. There are typically two approaches to sentiment classification tasks: **deep learning-based and rule-based using dictionaries**. I have comprehensively compared these two methods.

For the unstructured tweet information, I used language models for sentiment feature extraction. I selected three mainstream architectures that have been popular in recent years: TextCNN based on convolutional neural networks, bidirectional RNN based on recurrent neural networks, and BERT-finetuning based on transformer encoders. As a benchmark, I also employed NRC, a **dictionary-based** method that provides eight sentiment scores for each tweet.

Subsequently, the extracted sentiment features from each pre-trained model are combined with the daily opening price, highest price, lowest price, and other historical prices, and fed into a classifier. 
