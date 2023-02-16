# Predicting Premier League Match Winners From Post Game Data

### Conclusion
We found that the **random forest classifier** performed the best on our data, with a **CV score of 0.692** and a **test accuracy score of 0.728**. This means that this model can correctly predict the winner of a football match by seeing the post match stats roughly 73% of the time. 

Below is a table that summarises the results for all the models:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/73466733/219405654-3160b6c3-6d4a-4a4a-9436-fb49c73cc58c.png">

Below is a confusion matrix for the random forest classifier:

<img width="400" alt="image" src="https://user-images.githubusercontent.com/73466733/219404636-6a369dcd-4f77-49ce-a1fa-fda1b7bbf061.png">


### Project Goal
In this project we will be using post match data from premier league matches and predicting which team won the game so that coaches can understand from looking at post match data whether they 'deserved' to win the game or not. Using K-nearest neighbour, logistic regression and random forest classifier classification models we will see which models perform best and compare their results.

### Introduction
The premier league is considered the most competitive football league in the world. Nielsen research found that 3.2 billion people watched Premier League football during the 2018/19 campaign (1) and the evaluation of all premier league clubs combined being  18.7 billion pounds in total (2).


sources:
- (1) https://www.sportingindex.com/spread-betting-blog/premier-league-viewing-figures
- (2) https://sqaf.club/premier-league-club-valuations/


### Data Source
https://github.com/dataquestio/project-walkthroughs/blob/master/football_matches/matches.csv
