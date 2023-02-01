# Data

## World cup general information (`worldcups.csv`)

`year` - Year of the World Cup (1930-2022).

`host` - Nation hosting the World Cup.

`winner` - Champion of the World Cup.

`second` - Runner up in the World Cup.

`third` - Third place in the World Cup.

`fourth` - Fourth place in the World Cup.

`goals_scored` - Total amount of goals scored in the World Cup.

`teams` - Amount of national teams participating in the World Cup.

`games` - Amount of matches played in the World Cup.

`attendance` - Total attendance for matches in the World Cup.

## World cup matches dataset (`matches.csv`)

`year` - The year in which the World Cup match was played. 

`country` - The country where the World Cup match was played.

`city` - The city where the World Cup match was played.  

`stage` - The level of the competition the match was played at. Options include "Group " followed by a letter or number for group stage matches, "Round of 16", "Quarterfinals", "Semifinals", "Final" or "Final Round" for the match to win the tournament, and "Third place" for the match to win third place.         

`home_team` - The stated home team for a given match.      

`away_team` - The stated away team for a given match.
"home_score" - The number of goals scored by the home team (not including penalties scored from a penalty shootout if there was one).

`away_score` - The number of goals scored by the away team (not including penalties scored from a penalty shootout if there was one).

`outcome` - An indcator of who won a match. "H" if the home team won, "A" if the away team won, and "D" if the match finished as a draw.      

`win_conditions` - Text describing the outcome of a match if it did not finish in regular time. Format is "Country A won in AET" when a match is completed in extra time and "Country A won in penalties (x - y)" when a match is completed after a penalty shootout, with x being the number of penalties scored by the winning team and y being the number of penalties scored by the losing team.

`winning_team` - The name of the country that won the match (NA if the match ended in a draw).   

`losing_team` - The name of the country that lost the match (NA if the match ended in a draw).    

`date` - Date the match took place  as a string in the format YYYY-MM-DD.  

`month` - The month the match took place using the month's three letter abbreviation.      

`dayofweek` - Day of the week the match was played on.   
