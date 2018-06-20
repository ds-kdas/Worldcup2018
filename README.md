# Code to predict winner for World Cup 2018 Russia. 
I am using all match result from 1925 - latest and 1930 - 2014 world cup results as our historical data. Historical data is downloaded from https://github.com/openfootball/world-cup . Final csv file is created by extracting data from all these text files. 
I am also using FIFA rank details from 1991 - 2018 May. Finally model gives winner in terms of Team_A/Team_B/Draw.
In case of Draw I am considering team with 2nd highest probability.

Model details - 
Current model is 62% accurate so far which is definitely not very good. But being world cup prediction is very unpredictable 
this is the best I can get so far based on team level attributes. Using individual player level attributes also may improve 
model performance and it should be an intersting next course of action.

