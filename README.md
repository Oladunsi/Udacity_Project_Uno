# Udacity Nanodegree Project1: Investigate a Dataset - [European Soccer Database]
**Name** : **Oke** Oladunsi

## Dataset Overview

><br/> This soccer database comes from Kaggle which is well suited for data analysis and machine learning. It contains data for soccer matches, players, and teams from 11 European countries from 2008 to 2016. 
   > - The database is stored in a SQLite database.which consist of:
   > - +25,000 matches
   > - +10,000 players
   > - 11 European Countries with their lead championship
   > - Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
   > - Seasons 2008 to 2016
   > - Players attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
   > - Betting odds from up to 10 providers
   > - Detailed match events (goal types, possession, corner, cross, fouls, cards etc…)<br/><br/>

   ## Investigation Overview


><br/> This was my first nanodegree program project, Which is intended to assist budding data analyst develop the skill of questioning (i.e Relevant ones to the problem) from the dataset. Therefore, the questions below where developed initially to assist probe the dataset.
> - What are the top 20 teams with the most goals in the 2009-2010 season in europe top five leagues.
> - What are the top 20 performing teams (per goals conceeded) in european top 5 (five) leagues for the 2009/2010 season.
> -  Are there significance relationships between the amount of home games won and the the team position at the end of the season.
> - Are there any correlations between goals scored and games won per team
><br/><br/>

I hope this piece of work be of assistance to as many aspiring data analyst as possible. Also the scope investigated for this work is limited to Europe top five leagues to allow me do a comprehensive work yet not wearying me out during that includes:
- Spanish Laliga
- English Premier League
- German Budesliga
- Italian Serie A
- French League 1

# Packages 
For this project the following packages are were used during the course of work:

 <ul>
        <li><a href="#"> pandas </a></li>
        <li><a href="#">sqlite3</a></li>
        <li><a href="#"> numpy</a></li>
        <li><a href="#"> matplotlib</a></li>
 </ul>

## Key Insights for Presentation
><br/> Except for **Wolfburg**.<br/>
> - most teams with greater than 1.5 chance of scoring (more a goal) in a match end up in the european competion zones(Champions League or Europa League).
> - most teams with greater than 1.5 chance of conceeding in a match end up in the relegation zone or eventually get relegated. 
> - in all of europe Chelsea Fc is the most potent attacking side with close to 3 goals per match (2.71).
> - in all of europe FC Barcelona is the best defending team  with a goal conceeding rate of 0.63 goal per match.
> - in all of europe Burnley Fc is the worst defending team with goal conceeding rate of 2.16 goal per match.
> - Real Madrid and Barcelona are joint top teams with the most win in the season with (31) games.
> - Grenoble Foot 38 and Hertha BSC Berlin are joint top teams with the least wins in the season with (5) games.
> - Real Madrid and Barcelona are joint top teams with the most Home wins in the season with (18) games.
> - Hertha BSC Berlin are the team with the least Home wins in the season with (1) game.
> - Real Madrid and Barcelona are joint top teams with the most Away wins in the season with (13) games.
> - Hull City are the team with the least Away wins in the season with **NONE**.
> - Teams that won 9 games and below are within relegation zones.
> - Teams that won 20 games and above mostly in the champions league and Europa league spots (1-6). 
> - Barcelona top teams with the least amount of loses win in the season with (1).
> - Grenoble Foot 38 top teams with the most loses in the season with (25) games.
> - Portmouth top teams with the most Home loses in the season with (11) games.
> - Barcelona, Inter Milan, Palermo, Sampdoria  are the team with the least Home loses in the season with (0) **NONE**.
> - Burnley top teams with the most Away loses in the season with (17) games.
> - Barcelona is the team with the least Away loses in the season with (1).

<br/><br/>



