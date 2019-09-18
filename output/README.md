# ADS Project 1:  R Notebook on Lyrics Analysis

### Output folder

The output directory contains analysis output, processed datasets, logs, or other processed things.
- The processed_lyrics file is an outcome of text_processing from the doc folder.
- data cleansing was performed in this process:
1. Eliminate white spaces and stop words from lyrics.  
2. Stemming words and converting tm object to tidy object  
3. Creating tidy format of the dictionary to be used for completing stems  
4. Combining stems and dictionary into the same tibble  
5. Stem completion  
6. Pasting stem completed individual words into their respective lyrics  
7. Keeping a track of the processed lyrics with their own ID  
After this process, I also added character count, word count and decade categorization below. Also, I excluded NA values and two outliers that have a weird year dates.

