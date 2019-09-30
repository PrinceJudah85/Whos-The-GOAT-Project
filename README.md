# **Who's the GOAT?**
---
The purpose of this app is to compare NBA players by their career stats and create a value system around those results which would then highlight the "better" player. The app will feature a page where you select two players who's career stats will be  compared to one another.  Once you've selected those two players, their stats will load up on the page side by side.  The app will feature a button that will run thru that data and return to you the player that performed better throughout their career, putting to bed the age old question, "Who's the GOAT?" 
# MVP
The data for the app will be pulled from the open source [Balldontlie API]('https://www.balldontlie.io/#introduction'). Each API call would essentially be requesting more than 10 different data inputs, meeting the 3 minimum requirement. It will feature both a browser and mobile version. 

## Stretch Goals / Advanced features
An added feature to the app would be to have it work in conjunction with the [SportsRadar API]('https://sportradar.us/2018/10/nba-headshots-now-available/') library that would provide the player images for every call. It would provide the user with the entire profile of the player: player headshot, pedigree and career stats.

## API Libraries
The [Balldontlie API]('https://www.balldontlie.io/#introduction') will provide player stats from these categories:
* Points
* Assists
* Rebounds
* Steals
* Blocks 

While also providing the player's pedigree information such as:
* Name
* Height
* Weight
* Position
* University / High School they attended

While the [SportsRadar API]('https://sportradar.us/2018/10/nba-headshots-now-available/') will provide a headshot image of each player.

### Web App Layout
![Web App Layout](https://i.imgur.com/H3jjlvp.png)

### Mobile App Layout
![Mobile App Layout](https://i.imgur.com/ObkftAA.png)
