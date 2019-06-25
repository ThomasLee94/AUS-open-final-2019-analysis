# Australian Open 2019 Analysis

## Context

Data anlaysis between two players competing in the mens ATP grand slam Australian Open, Novack Djokovic and Rafael Nadal.

Visualisations will also be included.

The data consists of all points played in the match. It is build hierarchically from events, to rallies, to actual points. 
    - **Points:** a list of all points played in the final with information about the server, receiver, point type, number of strokes, time of rally, new score of the game. 
    - **Rallies:** A list of all rallies with Server, Returner, etc. 
    - Events: Each time a player hit the ball, the stroke type, position of the player, and position of the opponent were recorded. 
    - **Serves:** For each successful serve, which was no failure, the position of the serve in the service box was recorded (whenever possible)
    
Figure 1:

![alt text](https://www.dropbox.com/s/gakg677f0uvhmb2/Screenshot%202019-03-02%2021.44.11.png?raw=1)
    
The x & y coordinates represents a tennis court like Figure 1. 

If you are curious as to how the data was collected, please refer to the [source](https://www.kaggle.com/robseidl/tennis-atp-tour-australian-open-final-2019)

## Player Info (As of the competition)

### Rafael Nadal:
    - Nationality: Spanish
    - Height: 1.85 M (6 ft 1 inches)
    - Age: 32 years
    - Dominant hand: left handed
    - Backhand style: double handed
    - Career titles: 82
    - Best ranking: 1
    - Ranking at tournament: 2 (5th of November 2018)

### Novak Djokovic:
    - Nationality: Serbia
    - Height: 1.88m (6 ft 2 inches)
    - Age: 32
    - Dominant hand: right
    - Backand style: double handed
    - Career titles: 74
    - Best ranking: 1
    - Ranking at tournament: 1 (5th of November 2018)

