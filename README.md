# Applied Data Science @ Columbia
## Fall 2019
## Project 1: A "data story" on the songs of our times

<img src="figs/title1.jpeg" width="500">

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Fall 2019

+ Projec title: Song Analysis
+ This project is conducted by Alexandra DeKinder

+ Project summary: In this project I decided to use a KNN algorithm to classify songs into the decade they were written. Decades are often defined by their music and I wanted to use elements of the songs to show this from a data analytics perspective. I used the number of words in the song (length), genre, and a numeric sentiment score as my predictors. The first KNN run performed with 73% accuracy; however, this was misleading due to the imbalance in the data. After re-balancing using under-sampling in the over-represented categories, the accuracy rate was reduced to 8%. Further analysis would be needed to determine if classifying songs by their decade is possible, which could be in the form of finding new predictors or other algorithms.


```
proj/
├── lib/
├── data/
├── doc/
├── doc/Final Reports
├── figs/
└── output/
```

Please see each subfolder for a README file. The final reports for this project can be found in the Final Reports subfolder of the Doc folder.
