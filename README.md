# Recommender System for Steam Games
----------------------------------------------------------------------------------------------------------------

This is a recommender system for Steam. 
Original dataset was downloaded from https://www.kaggle.com/tamber/steam-video-games/data

Steam is the world's most popular PC Gaming hub. With a massive collection that includes everything from AAA 
blockbusters to small indie titles, great discovery tools can be super valuable for Steam. 

This dataset is a list of user behaviors, with columns: user-id, game-title, behavior-name, value. The behaviors included 
are 'purchase' and 'play'. The value indicates the degree to which the behavior was performed - 
in the case of 'purchase' the value is always 1, and in the case of 'play' the value represents the number of hours the user has played the game.

There are 2 files in this repo:
1. steam_recommender.ipynb - this jupyter notebook is the codes to recommend next games to purchase/play based on what you've purchased recently
2. steam-200k.csv - original dataset downloaded from the link above
