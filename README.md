# Sentiment_Analysis_Linkedin_photo
## Problem:  simple app/script that will take a LinkedIN profile URL as an input, and, perform the following changes and analysis on the LinkedIn profile photo, such as :  
1) Blur the background from the face  
2) Identify profiles where the face is at least 50-60% of the overall photo. If it's less than 50%, then score of face quality being too small  
3) Identify if teeth are visible. If so, mention teeth is shown  
4) Identity sentiment on face. E.g. smiling / happy, or neutral, sad.

## Solution:
1) I utilized selenium to connect chrome to my python notebook.
2) Scrapped profile photo from LinkedIN profile.
3) Called microsoft facial API.
4) This API performed sentiment analysis.
