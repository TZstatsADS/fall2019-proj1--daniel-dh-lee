# Applied Data Science @ Columbia
## Fall 2019
## Project 1: A "data story" on the songs of our times

<img src="figs/imusic.png" width="500">

### [Project Description](doc/)
Show the data story of the music trend

Term: Fall 2019

+ Projec title: Analysis of music starting from 1960s
+ This project is conducted by Daniel Lee

+ The goal of this project is to look deeper into the patterns and characteristics of different types of song lyrics. Applying tools from natural language processing and text mining, students should derive interesting findings in this collection of song lyrics and write a "data story" that can be shared with a general audience.

+ Project summary: Here I conduct a brief study on the trend of the music industry starting from 1960s to 2010s. This project used EDA analysis, text mining, sentiment analysis and readability of all songs. The result showed that the music industry boomed starting from early 2000s and Rock music was the key driver for that. Also, it showed that the length of the songs increased, which resulted increase of lexicon diversity. Also, generally the complexity of songs have increased, making hard for people to actually understand the full meaning of the lyrics.

+ Datasets:
- "lyrics.csv" ([Download](https://www.dropbox.com/s/3tfv5v73z0ec8vr/lyrics.csv?dl=0)) is a filtered corpus of 100,000+ song lyrics from MetroLyrics. Available features are song name, year, artist, genre, and lyrics. You can find the complete 380,000+ song lyrics data on [Kaggle](https://www.kaggle.com/gyani95/380000-lyrics-from-metrolyrics). A ```lyrics.RData``` file is also provided in the [\data folder](../data/).
- "artists.csv" (in the [\data folder](../data/)) provides additional background information of all the artistis. These information were scraped from [LyricsFreak](https://www.lyricsfreak.com/) by the ADS instructional team. For the singers, a detailed biography is provided. And for the bands, available information are members, established year and location. 

This folder is orgarnized as follows:
```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
