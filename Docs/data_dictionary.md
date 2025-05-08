# 📊 Data Dictionary

| Field              | Type     | Source            | Description                                                               |
|-------------------|----------|-------------------|---------------------------------------------------------------------------|
| Year              | Numeric  | Kaggle            | MLB season year                                                           |
| TeamID            | Text     | Kaggle            | Team abbreviation (e.g., BOS = Boston Red Sox)                            |
| Conference        | Text     | Kaggle            | League (AL or NL)                                                         |
| Games             | Numeric  | Kaggle            | Total games played during the season                                     |
| HomeRuns          | Numeric  | Kaggle            | Total number of home runs hit                                            |
| Walks             | Numeric  | Kaggle            | Total number of walks (base on balls) by the team                        |
| Strikeouts        | Numeric  | Kaggle            | Total number of strikeouts by the team                                   |
| Runs              | Numeric  | Kaggle            | Total number of runs scored                                              |
| Hits              | Numeric  | Kaggle            | Total number of hits by the team                                         |
| AtBats            | Numeric  | Kaggle            | Total number of at-bats by the team                                      |
| Division          | Text     | Kaggle            | Division Code (E = East, C = Central, W = West)                          |
| BallPark          | Text     | Kaggle            | Team's home ballpark                                                     |
| Wins              | Numeric  | BaseballReference | Total games won during the season                                        |
| Losses            | Numeric  | BaseballReference | Total games lost during the season                                       |
| DivisionWinner    | Boolean  | BaseballReference | 1 = team won division, 0 otherwise                                       |
| LeagueWinner      | Boolean  | BaseballReference | 1 = team won ALCS/NLCS, 0 otherwise                                      |
| WorldSeriesWinner | Boolean  | BaseballReference | 1 = team won World Series, 0 otherwise                                   |
| ERA               | Numeric  | BaseballReference | Earned runs average per game                                             |
| WalksPitching     | Numeric  | BaseballReference | Walks allowed by the team throughout the season                          |
| StrikeoutsPitching| Numeric  | BaseballReference | Strikeouts recorded by the team's pitchers                               |
| HRAllowed         | Numeric  | BaseballReference | Home runs allowed by the team                                            |
| HR_diff           | Numeric  | BaseballReference | HomeRuns hit minus HRAllowed                                             |
| MadePlayoffs      | Boolean  | BaseballReference | Y if team made playoffs, N if not                                        |
| HR_per_Game       | Numeric  | Myself            | HomeRuns divided by Games played                                         |
