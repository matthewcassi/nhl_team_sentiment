# NHL Rankings

After running the team tweets through the final model, the ranking of the teams are shown in the table below.

|Ranking| Team | Positivity Score|
| --------- | ------------- |:-------------:|
|1|![alt text](team_images/ducks.gif "Anaheim Ducks") | 0.707800 |
|2|![alt text](team_images/kings.gif "Los Angeles Kings") | 0.700027 |
|3|![alt text](team_images/preds.gif "Nashville Predators") | 0.694269 |
|4|![alt text](team_images/wings.gif "Detroit Red Wings") | 0.692764 |
|5|![alt text](team_images/avs.gif "Colorado Avalanche") | 0.691150 |
|6|![alt text](team_images/yotes.gif "Arizona Coyotes") | 0.689593 |
|7|![alt text](team_images/knights.gif "Vegas Golden Knights") | 0.688557 |
|8|![alt text](team_images/pens.gif "Pittsburgh Penguins") | 0.685668 |
|9|![alt text](team_images/canes.gif "Carolina Hurricanes") | 0.683068 |
|10|![alt text](team_images/stars.gif "Dallas Stars") | 0.680438 |
|11|![alt text](team_images/wild.gif "Minnesota Wild") | 0.673547 |
|12|![alt text](team_images/flyers.gif "Philadelphia Flyers") | 0.668847 |
|13|![alt text](team_images/jets.gif "Winnipeg Jets") | 0.666481 |
|14|![alt text](team_images/jackets.gif "Columbus Blue Jackets") | 0.660425 |
|15|![alt text](team_images/sharks.gif "San Jose Sharks") | 0.655994 |
|16|![alt text](team_images/bolts.gif "Tampa Bay Lightning") | 0.650761 |
|17|![alt text](team_images/bruins.gif "Boston Bruins") | 0.646160 |
|18|![alt text](team_images/caps.gif "Washington Capitals") | 0.645995 |
|19|![alt text](team_images/blues.gif "St. Louis Blues") | 0.618353 |
|20|![alt text](team_images/leafs.gif "Toronto Maple Leafs") | 0.611547 |
|21|![alt text](team_images/rangers.gif "New York Rangers") | 0.610007 |
|22|![alt text](team_images/isles.gif "New York Islanders") | 0.608599 |
|23|![alt text](team_images/canucks.gif "Vancouver Canucks") | 0.604013 |
|24|![alt text](team_images/panthers.gif "Florida Panthers") | 0.600806 |
|25|![alt text](team_images/sabres.gif "Buffalo Sabres") | 0.593559 |
|26|![alt text](team_images/flames.gif "Calgary Flames") | 0.586288 |
|27|![alt text](team_images/habs.gif "Montreal Canadiens") | 0.578462 |
|28|![alt text](team_images/sens.gif "Ottawa Senators") | 0.570220 |
|29|![alt text](team_images/hawks.gif "Chicago Blackhawks") | 0.568190 |
|30|![alt text](team_images/oilers.gif "Edmonton Oilers") | 0.562418 |
|31|![alt text](team_images/devils.gif "New Jersey Devils") | 0.557760 |


It is surprising to see all teams having more positive tweets than negative tweets. However, the week that the tweets were collected was right before the All-Star break and every team sends one player to the game. I think tweets are a little more positive as every team's fans get to see something good happen, even if their season isn't going well. Also, I collected bloggers' tweets and based on the blogs that I've read, their tweets are generally more positive than regular fans that reply to team accounts.

Despite the tweets being overly positive, the rankings do, for the most part, reflect how the season is going. The teams at the bottom were not playing well (Blackhawks, Oilers, Senators), while the teams at the top were playing well (Kings, Predators, Avalanche). 

## NHL Rankings Comparison
The top three models were used to classify the team tweets. The chart below shows the different rankings.

|Rank| Team | Positivity Score Final | | Team | Positivity Second Model | | Team | Positivity Third Model |
|-------------| :-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
|1|![alt text](team_images/ducks.gif "Anaheim Ducks")|0.707800| |![alt text](team_images/ducks.gif "Anaheim Ducks")| 0.719829| |![alt text](team_images/ducks.gif "Anaheim Ducks")|0.670547|
|2|![alt text](team_images/kings.gif "Los Angeles Kings")|0.700027| |![alt text](team_images/kings.gif "Los Angeles Kings")|0.701100| |![alt text](team_images/kings.gif "Los Angeles Kings")|0.653072|
|3|![alt text](team_images/preds.gif "Nashville Predators")|0.694269| |![alt text](team_images/wings.gif "Detroit Red Wings")|0.699509| |![alt text](team_images/wings.gif "Detroit Red Wings")|0.652494|
|4|![alt text](team_images/wings.gif "Detroit Red Wings")|0.692764| |![alt text](team_images/preds.gif "Nashville Predators")|0.697628| |![alt text](team_images/knights.gif "Vegas Golden Knights")|0.649031|
|5|![alt text](team_images/avs.gif "Colorado Avalanche")| 0.691150 | |![alt text](team_images/avs.gif "Colorado Avalanche")|0.697170| |![alt text](team_images/canes.gif "Carolina Hurricanes")|0.641504|
|6|![alt text](team_images/yotes.gif "Arizona Coyotes")|0.689593||![alt text](team_images/knights.gif "Vegas Golden Knights")|0.691941| |![alt text](team_images/pens.gif "Pittsburgh Penguins")|0.640676|
|7|![alt text](team_images/knights.gif "Vegas Golden Knights")|0.688557| |![alt text](team_images/yotes.gif "Arizona Coyotes")|0.690950| |![alt text](team_images/avs.gif "Colorado Avalanche")|0.638772|
|8|![alt text](team_images/pens.gif "Pittsburgh Penguins")|0.685668| |![alt text](team_images/pens.gif "Pittsburgh Penguins")|0.689943| |![alt text](team_images/stars.gif "Dallas Stars")|0.637880|
|9|![alt text](team_images/canes.gif "Carolina Hurricanes")|0.683068| |![alt text](team_images/stars.gif "Dallas Stars")|0.687407| |![alt text](team_images/flyers.gif "Philadelphia Flyers")|0.626945|
|10|![alt text](team_images/stars.gif "Dallas Stars")|0.680438| |![alt text](team_images/canes.gif "Carolina Hurricanes")|0.687347| |![alt text](team_images/yotes.gif "Arizona Coyotes")|0.622624|
|11|![alt text](team_images/wild.gif "Minnesota Wild")|0.673547| |![alt text](team_images/wild.gif "Minnesota Wild")|0.676351| |![alt text](team_images/jackets.gif "Columbus Blue Jackets")|0.620871|
|12|![alt text](team_images/flyers.gif "Philadelphia Flyers")|0.668847| |![alt text](team_images/flyers.gif "Philadelphia Flyers")|0.673444| |![alt text](team_images/wild.gif "Minnesota Wild")|0.619521|
|13|![alt text](team_images/jets.gif "Winnipeg Jets")|0.666481| |![alt text](team_images/jets.gif "Winnipeg Jets")|0.670385| |![alt text](team_images/preds.gif "Nashville Predators")|0.611067|
|14|![alt text](team_images/jackets.gif "Columbus Blue Jackets")|0.660425| |![alt text](team_images/jackets.gif "Columbus Blue Jackets")|0.663791| |![alt text](team_images/caps.gif "Washington Capitals")|0.607235|
|15|![alt text](team_images/sharks.gif "San Jose Sharks")|0.655994| |![alt text](team_images/sharks.gif "San Jose Sharks")|0.660867| |![alt text](team_images/sharks.gif "San Jose Sharks")|0.606925|
|16|![alt text](team_images/bolts.gif "Tampa Bay Lightning")|0.650761| |![alt text](team_images/bolts.gif "Tampa Bay Lightning")|0.650761| |![alt text](team_images/bolts.gif "Tampa Bay Lightning")|0.601785|
|17|![alt text](team_images/bruins.gif "Boston Bruins")|0.646160| |![alt text](team_images/bruins.gif "Boston Bruins")|0.648605| |![alt text](team_images/bruins.gif "Boston Bruins")|0.580566|
|18|![alt text](team_images/caps.gif "Washington Capitals")|0.645995| |![alt text](team_images/caps.gif "Washington Capitals")|0.648292| |![alt text](team_images/blues.gif "St. Louis Blues")|0.579117|
|19|![alt text](team_images/blues.gif "St. Louis Blues")|0.618353| |![alt text](team_images/blues.gif "St. Louis Blues")|0.623070| |![alt text](team_images/rangers.gif "New York Rangers")|0.574480|
|20|![alt text](team_images/leafs.gif "Toronto Maple Leafs")|0.611547| |![alt text](team_images/leafs.gif "Toronto Maple Leafs")|0.615678| |![alt text](team_images/isles.gif "New York Islanders")|0.574450|
|21|![alt text](team_images/rangers.gif "New York Rangers")|0.610007| |![alt text](team_images/rangers.gif "New York Rangers")|0.613891| |![alt text](team_images/leafs.gif "Toronto Maple Leafs")|0.567691|
|22|![alt text](team_images/isles.gif "New York Islanders")|0.608599| |![alt text](team_images/isles.gif "New York Islanders")|0.613162| |![alt text](team_images/canucks.gif "Vancouver Canucks")|0.567657|
|23|![alt text](team_images/canucks.gif "Vancouver Canucks")|0.604013| |![alt text](team_images/canucks.gif "Vancouver Canucks")|0.611404| |![alt text](team_images/panthers.gif "Florida Panthers")|0.558468|
|24|![alt text](team_images/panthers.gif "Florida Panthers")|0.600806| |![alt text](team_images/panthers.gif "Florida Panthers")|0.607863| |![alt text](team_images/sabres.gif "Buffalo Sabres")|0.555252|
|25|![alt text](team_images/sabres.gif "Buffalo Sabres")|0.593559| |![alt text](team_images/sabres.gif "Buffalo Sabres")|0.597558| |![alt text](team_images/habs.gif "Montreal Canadiens")|0.555150|
|26|![alt text](team_images/flames.gif "Calgary Flames")|0.586288| |![alt text](team_images/flames.gif "Calgary Flames")|0.585763| |![alt text](team_images/bolts.gif "Tampa Bay Lightning")|0.553976|
|27|![alt text](team_images/habs.gif "Montreal Canadiens")|0.578462| |![alt text](team_images/habs.gif "Montreal Canadiens")|0.582985| |![alt text](team_images/flames.gif "Calgary Flames")|0.539795|
|28|![alt text](team_images/sens.gif "Ottawa Senators")|0.570220| |![alt text](team_images/sens.gif "Ottawa Senators")|0.573461| |![alt text](team_images/sens.gif "Ottawa Senators")|0.527908|
|29|![alt text](team_images/hawks.gif "Chicago Blackhawks")|0.568190| |![alt text](team_images/hawks.gif "Chicago Blackhawks")|0.570918| |![alt text](team_images/oilers.gif "Edmonton Oilers")|0.521430|
|30|![alt text](team_images/oilers.gif "Edmonton Oilers")|0.562418| |![alt text](team_images/oilers.gif "Edmonton Oilers")|0.566910| |![alt text](team_images/hawks.gif "Chicago Blackhawks")|0.511663|
|31|![alt text](team_images/devils.gif "New Jersey Devils")|0.557760| |![alt text](team_images/devils.gif "New Jersey Devils")|0.554229| |![alt text](team_images/devils.gif "New Jersey Devils")|0.508828|


You can see the average rankings between the top three models. The rankings for the teams are relatively the same with the Naive Bayes model being the most different. The two Logisitic Regression models performed almost the same, which was to be expected.

# NHL Sentiment Analysis
This NHL Sentiment Analysis aims to rank all 31 NHL teams according to the positivity/negativity (sentiment) of Twitter tweets. The tweets were collected from January 20th through January 25th 2018, which was right before the All-Star break.
<br><br>
The repository contains the files for the gathering tweets about all 31 NHL teams from Twitter, cleaning the Twitter data, and exploring the initial dataset. It also contains the images that were not used in the Milestone Report, including tweets by hour of the day and word clouds.
