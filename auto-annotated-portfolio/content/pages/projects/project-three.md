---
type: ProjectLayout
title: Web Scraping and Sentiment Analysis on advertisement data using Python
colors: colors-a
date: '2022-01-22'
client: Awesome client
description: >-
  This project involved using selenium to automate data downloading (web
  scraping) for a lot of advertisements. After that I used pre-trained
  transformers from HuggingFace to do sentiment analysis on textual repsonses.
featuredImage:
  type: ImageBlock
  url: /images/sentiment_analysis2.jpg
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/sentiment_analysis2.jpg
  altText: Project image
---
This was a cool project as I had never worked on web scraping before, using selenium automates a lot of manual stuff but you need to think of the tradeoff of writing and debugging code when maybe the manual download process might take <1 hr. 

After scrapping the data from the website, I had to do sentiment analysis to show if the textual responses to each advertisement was either "Positive", "Negative" or "Neutral". I tried a few different models, including using GPT-3.5 using the OpenAI api, but I ended up using pre-trained transformers from [huggingFace ](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest)(RoBERTa model pre-trained for sentiment analysis) as it is free to use, very accurate and scalable for large number of text inputs. The website has a cool interactive tool to see how each input text is classified.

[See code on github here](https://github.com/sshourie/ads-sentiment/tree/main),  note that the code requires credentials to login to ispot.tv

