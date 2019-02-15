# Predicting the Outcome of Soccer Matches

Note: This project is not currently active. It is likely outdated and buggy. I unfortunately do not have the time to update it or keep up with pull requests.

## History of Soccer

Soccer, or Football as much of the world knows it, has been played throughout history. The international governing body, Fédération Internationale de Football Association (FIFA) recognizes a Chinese game Cuju as the first version of the game with regular, recognizable rules. Cuju was played by military members in the Han Dynasty during the 3rd and 2nd century BC. It has been a sport us humans have enjoyed for a long time. Not only do we enjoy the sport, but we attach monetary stakes as well. In fact, the first documented english reference to the sport regards a tax levied on matches, implying this was something of popularity. Fast forward to today (2019) soccer is the most watched sport in the world with 4 billion fans, all hoping for their desired outcome to occur in the game they are watching. As such a relevant question is, "how can we best predict the outcome of a future soccer match?" In this analysis I attempt to tackle this question.

##Table of Contents
1. [Dataset](#dataset)
2. [Soccer Betting Background](#popularity-of-Soccer)

## Data Set

Data for this project was provided by [The European Soccer Database](https://www.kaggle.com/hugomathien/soccer) compiled together by Hugo Mathien. When I took this analysis my dataset it consisted of over 25,000 matches across 11 European leagues, for the seasons starting in 2008 continuing through the end of the 2015/2016 season. This data set includes observations of each match's home team goal count, each matches away team goal count, and player positional coordinates (x,y). (In addition to what was just described, the the betting odds across multiple betting platforms are included for each match; and the player stats/ team attributes created by FIFA's video game platform are also included. )

## Popularity of Soccer

Soccer TV broadcasting revenues have risen to historic heights in recent years.

<img alt="Money Going into the Soccer System" src="images/Soccer_TV_Broadcasting_Revinues" width=450>


As more people tune into watching soccer more money and interest is entered into the system. As more money is entered into the system, player salaries and transfer fees have increased. As the number of people with interest in the sport increases more are willing to place monetary wagers on the outcome they prefer.

## Difficulty of predicting Soccer Matches

There is a famous saying that people who play or watch Soccer know, which is "the better team does not always win." Soccer matches are commonly known to end with low goal counts and close or non-existent score margins. Score margins can be non-existent with the outcome of a match as a draw, yet each team is still rewarded points towards the seasons ultimate goal of highest point count.

<img alt="Mexico's Late Equalizer to Tie Match Favorite, Germany" src="images/WE_TIED.png" width=450>
<sub><b> Mexico's Late Equalizer to Tie Match Favorite, Germany. </sub>

In many leagues, including the European leagues, it is <b> vital to maximize your season end point count. The three teams with the lowest point count at the end of the season get dropped out of the league, and replaced by the highest point count in the three teams of the lower league. Being dropped out of the top league comes with financial consequences as less people will watch your games. This is in contrast to many sports leagues in the USA where there is an incentive of placing lower on the seasons point count, which is receiving an earlier choice of new players entering the league aka, a higher draft pick.



## Types of Soccer Bets

Betting on a soccer match can generally take one of three forms.
1. One can bet on the particular outcome of a match.
..* Team A wins, Team B, wins, or Draw.
2. One can bet on 'no draw'.
..* Team A wins, Team B wins or both parties receive their stake back with a Draw
3. What is known as the Asian Handicap; Statisticians will put out odds for a variety of features and you can bet on those odds.
..* This betting form is most commonly take by betting on particular team winning or looseing by a margin larger then 1.

<img alt="Draw or a one goal margin is most common." src="images/two_goal_margin.png" width=450>


<img alt="Home team always has the higher spread on aggregate." src="Home_Team_Spread.png" width=450>

What has been found historically is that betting on a draw is the hardest outcome to predict. However, there are a surprising amount of draws in each season. As seen in the graph below a draw has around a 25% likelihood of happening across all match data.

<img alt="Draw ~ 25%, loss(away) ~ 28%, win(home) ~ 47%." src="Home_Team_Record.png" width=450>

## Analysis

To look at the problem I wanted

## Cleaning my Data

how I found my columns

## Future Directions

### Results

<img alt="ROC Curve" src="Roc_Curve.png" width=450>
# Predicting-Soccer-Outcomes
