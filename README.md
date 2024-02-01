# Graduation Speeches
What words did Oprah and Tom Hanks choose to inspire 2023 graduates? An analysis of some of this year's most memorable speeches. 

## My Goals
I planned to analyze and visualize the most frequent words in six commencement speeches. I used Python's NLTK library because I didn't know better. I completed the analysis for the six speeches.
These were the questions I wanted to answer:
- What did the most popular commencement speakers say to 2023 graduates?
- What words did they use more frequently?
- Are there common topics?

In the end, due to time constraints, I only visualized three speeches and couldn't do a comparison among them, which was one of my top goals.

## Findings
My most obvious finding is that I don't love word frequency counts. It may be that I did not have enough time for a more in-depth analysis, but I realized that it was crucial to read/listen to the speeches to understand the word count. Also, it might have been better to keep some phrases together. 

## Data collection and analysis 

To decide the top 12 speakers I checked several news articles and chose two --one from The Guardian and another one from Forbes-- to scrape the names and create a list using pandas and Beautiful Soup. 

Because I had limited time to finish this project, I decided to focus on the speeches with
full transcripts. I found some of the other speeches on YouTube and actually realized I could copy and paste the YouTube transcripts when I inspected the page, but I only did it for one speech. 

I imported the nltk package to analyze the speeches. Since I had not done this before,
I followed the NLTK documentation plus several tutorials: 
1.https://www.youtube.com/watch?v=X2vAabgKiuM --Great because he uses Jupyter Notebooks and offers a very simple yet deep explanation
2.https://realpython.com/nltk-nlp-python/
3.https://towardsdatascience.com/find-common-words-in-article-with-python-module-newspaper-and-nltk-8c7d6c75733
Credits for nltk: Bird, Steven, Edward Loper and Ewan Klein (2009).
#Natural Language Processing with Python.  O'Reilly Media Inc.

I removed words like "applause" and "laughter" because they were not part of the speech, and also stop words and punctuation.

## New skills, approaches
I used the NLTK library, but more importantly, I familiarized myself with the natural language analysis process.

## Things I tried to do or want to do but did not have the skills/time (but if I have more time might do)
- Analyze the similarities/differences among the speeches. Do some of the frequent words repeat?
- Finish the graphics and texts for all six speeches.
- After I finished the analysis, I discovered https://investigate.ai/text-analysis/counting-words-with-pythons-counter/ and the site's tutorials. I would like to code a more efficient way to obtain and analyze these speeches because they happen every year and it would be cool to make comparisons over time and also have the code ready to run. 
-  Another idea worth exploring in the future is to focus on speeches delivered by Black women. I noticed that at least 6 gave very inspiring commencement speeches in 2023. It would be great to highlight them.
- I would also edit the graphics in Illustrator as was my original plan. I would add annotations to make it more interesting. 
