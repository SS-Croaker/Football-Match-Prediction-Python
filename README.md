# Football-Match-Prediction-Python
Simulator to predict football match results of top 5 football leagues (EPL, La Liga, Busdesliga, Serie A, Ligue 1)

1. Convert this whole code via functions so that I can all all the 5 leagues at once (still working on it)
Currently I have to run the code 5 times to get the data for all 5 leagues - DONE

2. Run this code once every day at midnight automatically (this is important since predicting 7 days into the future is creating issues like a team having multiple matches within that 7 days.)

3. Add a comparison chart which compares the prediction with the actual result  (Lets say I run the code on 3 Jan 2021 at midnight, so I get the prediction for matches on 3rd Jan 2021. And when the code runs on 4th Jan 2020, I get a)prediction for matches on 4th Jan 2021, b) comparison of prediction vs actual result for matches on 3rd Jan 2021 

4. Have a database where the output is automatically stored and then somehow reflected on the website (https://talesofss.com/top-5-football-leagues-match-prediction/…)

5. In the output graph, Mention the date of the match along with the prediction (https://stackoverflow.com/questions/65372100/plot-yticks-to-have-data-from-two-columns-instead-of-just-one-column…)

6. Make the output graph a bit more interactive (either links to http://Goal.com for the match or just highlight the predicted winner or something like that)  

I have some idea on how to go about a few of these, but require expert help to speeden up the process by either collaborating or guiding me in the right direction:

1) is a work in progress - DONE (Updated file is yet to be uploaded)
2) can be done via server (I am assuming I can use a sleep timer for 1 day but I need the code to execute at 0001 hours
3) can be done via merge(). (last_weekend_fixtures to be merged with  this_weekend_fixtures). Date filter would be 1 day instead of current 7 days
4) No clue how to do this.
5) I tired asking this on stackoverflow, but didn't get any answer
6) Is there a graphical library that can help with this? 
