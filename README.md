## Unit 7 | Assignment - Twitter VADER sentiment analysis (News outlets)

Skills Tested: Python, Twitter API calls (via Tweepy), Arrays/Loops, Matplotlib, Pandas

This program utilizes the Twitter api to measure news outlet sentiments of the last 100 tweet by 5 news outlets.  The program takes in a 
list of 5 news agencies and stores the compound tweets as a list in a dictionary.  The dictionary of lists is then converted to a dataframe and then a scatterplot.  For the bar graphs, the program will sum the total compound sentiments, and then output a bar graph with the totals for each news outlet.  

As for the API key, it is stored in a separate file call "apikeys", which is imported as a dependency.


![](/SocialAPI_BarPlot.png)
![](/SocialAPI_ScatterPlot.png)
