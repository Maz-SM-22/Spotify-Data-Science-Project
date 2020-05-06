# Spotify-Data-Science-Project
A data science project in Python exploring the Spotify and Genius APIs

For my final project as part of the [AllWomen](https://www.allwomen.tech/)'s Data Science bootcamp, I decided to focus on NLP and do my project on an industry that interests me: the music industry. 

Spotify, as the industry leader in streaming, has over 124 million Premium susbscribers worldwide and therefore has huge sway in the music industry and helps determine what we listen to. So, I decided to look at the top ten markets/countries for Spotify and their top 50 charts and look at what music was popular and the lyrical content of the commerically sucessful tracks. 

For more details about the project and a full walk through, please check out [this article](https://www.linkedin.com/pulse/allwomens-adaptability-gave-me-support-i-needed-my-maria-smickersgill/?trackingId=1L22TrwZRoiKSXnMI9irSQ%3D%3D). 

In this repository there are seven files: 
1) **Spotify Dataset Functions** which is the script working with the Spotify API and spotipy libraries to get the playlist details 
2) **Global Charts Spotify (EDA)** which is a notebook exploring the newly extracted data
3) **Genius API Generating Lyrics** where I get the lyrics for all songs in all the playlists 
4) **POS Tagging & NER** where I do a preliminary linguist analysis of the lyrics 
5) **Get Translation** where I translate the lyrics ready for further linguist analysis
6) **Spotify Sentiment Analysis** where (predictably) I carry out sentiment analysis 
7) **Spotify Topic Modelling & Embeddings** where I do some topic modelling on the translated lyrics and create a Word2Vec model 

All references and are cited in each notebook, except for topic modelling and embeddings for which I owe thanks to Susan Li's fantastic topic modelling [example](https://towardsdatascience.com/topic-modeling-quora-questions-with-lda-nmf-aff8dce5e1dd) and, for word embeddings, Kavita Ganesan's great worked [example](https://kavita-ganesan.com/gensim-word2vec-tutorial-starter-code/#.XrLLIJlS8aE).

I thoroughly enjoyed working on the project and getting to grips with the Spotify API and hope you enjoy checking it out! As always, I am very open to suggestions on how to improve the project and the code itself. 

Thanks! 😁
