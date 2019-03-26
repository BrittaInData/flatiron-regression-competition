
## Introduction

You have just received a hologram message from a droid:

    Future Data Science Jedi Knight! Years ago, you served with my father in the Clone Wars.  Now he begs you to help him in his struggle against the Empire. The Rebellion is under siege from a new division of the Empire – propaganda video games!  We need you to predict the sales of a collection of their video games. We'll use this information to bring peace to the Galaxy.

    This is our most desperate hour.  Help me, Future Data Science Jedi Knight. You’re my only hope.  [looks to the side quickly, then crouches to end the message]

Best of luck to everyone and don’t forget your Jedi Knight Training:

- Be Scrappy
- Radiate Positivity
- Pursue Mastery
- Work Together
- Make No Little Plans

## Evaluation

#### Goal

It is your job to predict the North American Sales for each video game. For each Id in the test set, you must predict the value of the Prediction variable. You can see an example submission file on the Data page.

#### Metric

Submissions are evaluated on the Mean-Squared-Error (MSE) between the predicted sales and the actual sales of each video game.

#### Submission Format

For every game in the dataset, submission files should contain two columns: Id and Prediction. The Id is the unique ID for each video game and Prediction is the predicted number of sales for that video game.

The file should contain a header and have the following format:

    Id, Prediction
    11703, 2.39

## Data Description

Here is all the data that you will need for this project. You will need to build your model with the train.csv file to predict NA_Sales. Once you are confident in your model, use it to predict sales on the test.csv file. Your submission should look like the df_sample_submission.csv file. Best of luck!

#### File descriptions

    train.csv - The training set
    test.csv - The test set
    df_sample_Submission.csv - A sample submission file in the correct format

#### Data fields

    Id - A unique ID for each game in the dataset
    NA_Sales - Game sales in North America (in millions of units)
    Platform - Console on which the game is running
    Year_of_Release - Year the game was released
    Genre - Game category
    Publisher - Publisher
    JP_Sales - Game sales in Japan (in millions of units)
    Critic_Score - Aggregate score compiled by Metacritic staff
    Critic_Count - The number of critics used in coming up with the Critic_score
    User_Score - Score by Metacritic's subscribers
    User_Count - Number of users who gave the user_score
    Developer - Party responsible for creating the game
    Rating - The ESRB ratings (E.g. Everyone, Teen, Adults Only, etc.)
