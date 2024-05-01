# Game Engine recommendation
Goal is to return a list of recommendations based on a selected game id

Please check [games.csv](https://github.com/laithnurie/GameEngineRecommendation/blob/main/games.csv) file, this is the raw csv file from database

Currently I am brute forcing to create the recommendations in a high computational manner, instead I want to use Content-Based Recommendation Algorithm.

Currently I am able to get the [recommendations.json](https://github.com/laithnurie/GameEngineRecommendation/blob/main/recommendations.json) using game id of 1942, using the parameters below: 
```
'themes','genres','keywords','platforms','total_rating_count','total_rating','game_modes' 
```

Demo of app:

https://github.com/laithnurie/GameEngineRecommendation/assets/717269/cb6b67fa-5d83-44fe-a48f-9bb90ca68e49


We will measure success by getting similar results using that id (we will test with multiple ids to confirm that it will work)
