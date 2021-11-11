# PUBG_best_strategy_to_win
![alt text](https://www.vga4a.com/wp-content/uploads/youtubegaming2560_1440.jpg)

## Introduction 
Battle Royale style video games have taken over the world. PUBG is very popular it's the fifth best-selling game of all time with millions of players.100 players are dropped on an empty island and must explore, hunt, and eliminate other players to only one player remains until the play area ends. There are 3 playing modes in the game. One can play alone, with a friend (a duo), or with 3 other friends (a squad).

## Motivation <br>
The objective of this project is to find out the best strategy to win in PUBG and infer the probability of the team cheating in the game from this data provided by the PUBG team as they made the official game data available for the public to explore and search for outside the “blue circle”.
Question/need:
•	What is the best strategy to win in PUBG?
•	Should you sit in one place and hide on your way to victory, or do you need to be in the lead?
## Tools
•	Python in Jupyter notebook 
•	Numpy and Pandas for data manipulation
•	Matplotlib and Seaborn for plotting
•	Tableau for interactive visualizations
## Data Description:
Reference: Kaggle Your Machine Learning and Data Science Website here
The dataset contains 4446966 rows and 29 columns, there are 4446966 players participated, they comprised 2026745 groups, and played 47734 matches included in the data folder as CSV file. These numbers are consistent with our commonsense of PUBG a group consisting of 3 or 4 players, about 100 players can play in a single match. its consisting of train and test sets and needed to predict final placement from final in game stats and initial player rate. For better understanding of database there is a columns description below:
groupId - Players team ID
assists - Number of assisted kills. The killed is actually scored for another teammate.
boosts - Number of boost items used by a player. These are for example: energy dring, painkillers, adrenaline syringe.
damageDealt - Damage dealt to the enemy
DBNOs - Down But No Out - when you lose all your HP but you're not killed yet. All you can do is only to crawl.
headshotKills - Number of enemies killed with a headshot
heals - Number of healing items used by a player. These are for example: bandages, first-aid kits
killPlace - Ranking in a match based on kills.
killPoints - Ranking in a match based on kills points.
kills - Number of enemy players killed.
killStreaks - Max number of enemy players killed in a short amount of time.
longestKill - Longest distance between player and killed enemy.
matchDuration - Duration of a mach in seconds.
matchType - Type of match. There are three main modes: Solo, Duo or Squad. In this dataset however we have much more categories.
maxPlace - The worst place we in the match.
numGroups - Number of groups (teams) in the match.
revives - Number of times this player revived teammates.
rideDistance - Total distance traveled in vehicles measured in meters.
roadKills - Number of kills from a car, bike, boat, etc.
swimDistance - Total distance traveled by swimming (in meters).
teamKills - Number teammate kills (due to friendly fire).
vehicleDestroys - Number of vehicles destroyed.
walkDistance - Total distance traveled on foot measured (in meters).
weaponsAcquired - Number of weapons picked up.
winPoints - Ranking in a match based on won matches.

And our target column:
winPlacePerc - Normalised placement (rank). The 1st place is 1 and the last one is 0.


## Algorithms
First, we will clean up the data by finding and removing nulls and duplicate values.
After that, the average of dividing the number of players in one map is calculated, then the average is calculated for each of (Killers, Runners , Drivers, Swimmers, The Healers, Solos, Duos and Squads).
This data helps us determine the highest percentage or strategy for winning players in the first place.
Finally, show and model the data and use what we've learned to improve this game play, answering our questions.

## Communication
Please feel free to let me know if you have any questions.
Email:  tahani.almutery@gmail.com and maram.alfaifi@hotmail.com

