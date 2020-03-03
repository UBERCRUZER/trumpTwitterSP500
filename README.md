# trumpTwitterSP500
S&amp;P500 Analysis from Donald Trump's Twitter Feed


Quick, broad exploration of S&P 500 returns as a function of Donald Trump's tweets.

Analysis uses LDA topic modeling to group tweets in to topics. S&P returns are categorized into "good" and "bad" days. 

Data is then analyzed using various models to see if there's any relationship between Donald Trump's thumbs and the S&P500. 

Spoiler alert: There isn't much of a strong connection from the methods attempted. However it is fun to note that when Trump congratulated people (himself included), the stock market had bad days, and when he talked about how awful the NFL was, the stock market had good days. I think this has more to do with the stock market having certain good and bad periods while Trump had a popular topic to yap about, than his twitter feed having an effect on the S&P. In other words, those good and bad days were going to happen anyway and he just happened to be talking about the same things during those time periods. 

Below are the coefficients from the logistic regression. Predicting "good" or "bad" days from each topic. Topics with highest and lowest coefficients are shown.

![Logistic Regression Coefficients and their corresponding topics](https://i.imgur.com/thGpui0.png)

Further exploration: If any further exploration is to be done, I would look more indepth into specific industries and explore different time granularities/lag (eg. seeing if minutes after a tweet had an effect on a specific industry, or even company).
