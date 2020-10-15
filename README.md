# Pubg_Data_Analysis_2020
# About:
Analysis of the data of one the most played battle royale game known as Player Unknown Battleground(PUBG).I am Working on the Exploratory Data Analysis according to the different aspects like Killers,Runners,Drivers,Swimmers,Healers and other aspects also.
# Data grabed from Kaggle Link : https://www.kaggle.com/c/pubg-finish-placement-prediction/data
# Exploring the columns- Defining😎 each column meaning.😃
groupId: Integer ID to identify a group within a match. If the same group of players plays in different matches, they will have a different groupId each time
matchId: Integer ID to identify match
assists: Number of enemy players this player damaged that were killed by his teammates
boosts: Number of boost items used in the match during the game of PUBG.
DamageDealt: Total damage dealt. Self inflicted damage is subtracted
DBNOs: Number of enemy player knocked during the match.
headshotKills: Number of enemy killed by headshots
heals: number of healing items used
KillPlace: Ranking in match of number of enemy players killed.
killPoints: Kills-based external ranking of player. (Think of this as an Elo ranking where only kills matter.)
kills: Number of enemy players killed.
killStreaks: Max number of enemy players killed in a short amount of time.
longestKill: Longest distance between player and player killed at time of death. This may be misleading, as downing a - player and driving away may lead to a large longestKill stat.
maxPlace: Worst placement we have data for in the match. This may not match with numGroups, as sometimes the data skips over placements.
numGroups: Number of groups we have data for in the match.
revives: Number of times this player revived teammates.
rideDistance: Total distance traveled in vehicles measured in meters.
roadKills: Number of kills while in a vehicle.
swimDistance: Total distance traveled by swimming measured in meters.
teamKills: Number of times this player killed a teammate.
vehicleDestroys: Number of vehicles destroyed.
walkDistance: Total distance traveled on foot measured in meters.
weaponsAcquired: Number of weapons picked up.
winPoints: Win-based external ranking of player. (Think of this as an Elo ranking where only winning matters.)
winPlacePerc: The target of prediction. This is a percentile winning placement, where 1 corresponds to 1st place, and 0 corresponds to last place in the match. It is calculated off of maxPlace, not numGroups, so it is possible to have missing chunks in a match.
