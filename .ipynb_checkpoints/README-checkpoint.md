# CMSE-202-final
## March Madness Prediction Using Machine Learning

This project's main purpose is to predict the winner of College Basketball March Madness tournament. We did this in Python, specifically using machine learning from the statsmodel.api and sklearn libraries.

To clone this repository to use the code:

```git clone https://github.com/zinnluth/CMSE-202-final.git```

We used data from previous seasons, specifically 2013-2019, to train our model. We also used a popular basketball ranking, the KenPom rankings by Ken Pomeroy, to create the bracket for us to run our matchups. Rebound data was also gathered for each team. Several functions, handling both matchups and determining winners, were created to allow us to advance our bracket. Teams were divided into their regions to mirror the progress of the real tournament.

When reaching the Final Four, new functions was created and the teams were added into one dataset. After running the final functions on the remaining teams, the winner will be determined.

In order to run this code properly, download the entire repository along with the two .csv files to ensure the data is read in properly. This code was designed to be run straight through. The result can be changed by altering the random_state under the "Creating Model With Important Features" header. The default is 10. This code could be re-used in the future with new datasets as long as the new dataset has the same stats as the current dataset. Variables should be adjusted in the case that a new dataset is used. Different models might return different variables as being statistically important, so the sections of code might need to be adjusted.

TJ McKenna: Gathered data, worked on code and presentation

Carter Smotherman: Gathered data, worked on code and presentation

Luke Zinn: Code, presentation, created repository on GitHub

Jack Upton: Code and presentation

Evan Puls: Code and presentation


# References

2023 Data:

https://kenpom.com/

2013-2019 Data:

https://www.kaggle.com/datasets/jedbell/fullseasonstats-1319

2023 Rebounding Data:

https://www.teamrankings.com/ncaa-basketball/stat/total-rebounds-per-game

Idea: 

https://www.analytics8.com/blog/how-to-use-machine-learning-to-predict-ncaa-march-madness/


```python

```
