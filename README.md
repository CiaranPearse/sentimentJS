# sentimentJS
Detect &amp; calculate the sentiment of a string (comment, message etc.) with pure JavaScript.

SentimentJS uses the AFINN-11 file to determine if a word is positive or negative and weigh its score.

Check the console as almost every variable declaration or change is logged out.

I build this to solve a problem in an admin area of a site, not a highly used public area so speed and lightweightness were not a huge concern.

If you use it in production on a consumer facing area of your site you'll have to do some work with it to lighten the footprint.

##Installation
Simply include js/sentiment.js in your file.

##Customize
there are 10 variables (neg1 - neg5 & pos1 - pos5). Each is checked against a regex with a list of words with a positive or negative weight that corrosponsd to the variable (pos5 will have a list of very positive words)
). Change these as you see fit but be aware that there has been sme research put into the AFINN-11 list so its probably pretty accurate.
