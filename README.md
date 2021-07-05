# Cricket-League-Prediction
• Predicted the outcome of a cricket match based on the team’s batting and bowling lineups, and which team bats first.  
• Scraped player vs player (pvp) statistics and consolidated ball by ball data to get pvp probabilities. Players were grouped into clusters based on K-means density clustering. The cluster vs cluster probabilities were calculated using MapReduce with Scala, results were stored using HIVE and was useful to handle scenarios where players didn’t face each other.
