# Predicting Premier League Match Winners From Post Game Data

### Conclusion
**See full conclusion at bottom of project**

We found that the **random forest classifier** performed the best on our data, with a **CV score of 0.692** and a **test accuracy score of 0.728**. This means that this model can correctly predict the winner of a football match by seeing the post match stats roughly 73% of the time.

Below is the confusion matrix for our random forest classifier.

![image.png](attachment:image.png)

<img width="431" alt="image" src="https://user-images.githubusercontent.com/73466733/219404112-df5eb35f-f3ea-4c9b-9f58-2db6fe359b6b.png">


### Project Goal
In this project we will be using post match data from premier league matches and predicting which team won the game so that coaches can understand from looking at post match data whether they 'deserved' to win the game or not. Using K-nearest neighbour, logistic regression and random forest classifier classification models we will see which models perform best and compare their results.

### Introduction
The premier league is considered the most competitive football league in the world. Nielsen research found that 3.2 billion people watched Premier League football during the 2018/19 campaign (1) and the evaluation of all premier league clubs combined being  18.7 billion pounds in total (2).


sources:
- (1) https://www.sportingindex.com/spread-betting-blog/premier-league-viewing-figures
- (2) https://sqaf.club/premier-league-club-valuations/


### Data Source
https://github.com/dataquestio/project-walkthroughs/blob/master/football_matches/matches.csv
