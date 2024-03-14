# Project Summary
In this project, our team tries to apply data analysis concepts to the video game industry. More specifically, we focused on preprocessing popular and up-to-date game data along with implementing classification models to predict their ratings.

## Model Design 
We chose to use classification models because they are excellent at predicting outcomes from categorical data. In the context of video games, a lot of features are already compatible with popular classification models. However, we want to also see how the genre, type and reputation of the game can also affect its average rating.

## Dataset and characteristics
We got our data from the very popular game distribution service Steam. We used data collected from Steam API and with other third party resources. It has data for all games up until 12/01/2024 with a sample size of 85113 games.

Below is a list of important features from the dataset that we believe can help us:
- Price: cost of buying the game
- Publishers/developers: entities that have created and distributed the game
- Total ratings: number of users who rated the game
- Date of release: game launch date
- Genre (action, indie, casual, board games)
- Categories (single vs multiplayer, steam achievements)

Label to try and predict:
- Average rating: mean rating from all users in total ratings

We plan to add the following features from our dataset to help with the accuracy of our models:
- Weighted rating: this will use a standard normalized formula to penalize high average but low number of rating games (essentially trying to remove outliers).
- Publisher/developer popularity: this helps us get a better grasp of the influence of publishers in the popularity of their games. We also enable classification models to categorize the publisher by a popularity score, rather than by their unique name.

## Algorithms
- Random forest: combination of multiple independently trained decision trees, very popular and effective for training structured data. We expect this algorithm to perform very well.
- Support vector machine: attempts to find optimal separating hyperplane that separates different classes situated in potentially high dimensions. It is a supervised learning algorithm often used for classification as well.

### Research Question
Our ultimate aim in the completion of this project is to try and predict the rating of games (either existing and unrated). In the process, we would also like to analyze how a publisher's popularity can affect the ratings and average playtime of its new games. By exploring these questions, we hope to help developers and publishers get a better idea of reasons behind success and popularity in games.

*Credits for the amazing people who collected the dataset:


