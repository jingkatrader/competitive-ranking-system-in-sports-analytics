# competitive-ranking-system-in-sports-analytics

## Data Descriptions
1. HP comp: contains the origianl Halfpipe competition data from 1995 - 2020.
2. ranking list: contains the both original FIS officially published bi-weekly athlete rankings and two organized Excel files for easier data processing and viewing.
3. chronological: contains the Halfpipe data organized by the year of competition.


## Code descriptions
1. Data cleaning.ipynb:
   - Developed for data cleaning of the Halfpipe competition data and FIS official ranking lists.
    
2. Multiplayer elo.ipynb:
    - Train the new athletes score using the Elo system and evaluate the system’s prediction accuracy on athletes ranking.
    - Hyperparameter tuning is included to search for the best accuracy.
    - Compute the year-end elo scores for all athletes and filter the podium winners.
3. Multiplayer Glicko.ipynb:
    - Train the new athletes score using the Glicko system and evaluate the system’s prediction accuracy on athletes ranking.
    - Hyperparameter tuning is included to search for the best accuracy.
4. TrueSkill_final.ipynb:
    - Train the new athletes score using the Microsoft TrueSkill system and evaluate the system’s prediction accuracy on athletes ranking. 
5. KNN classification.ipynb:
    - The complete python code that organizes year-end Elo scores by athlete and previous podium winners. Followed by the KNN algorithm to predict athletes’ potential to win podiums using combinations of different numbers of years of data and K values.
