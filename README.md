# Crossfit athletes results exploration

## Dataset description

The dataset contains information about crossfit athletes that were competing in 2015 year. The original dataset was taken from here https://data.world/bgadoci/crossfit-data. The original dataset had information about 423k athletes with 26 characteristics including region, team, results, and other information. It also contained a lot of null values (NaN, NA, -, 0 etc.). Since I wanted to have the complete information about every athlete in my dataset, I decided to keep only those rows that doesn't contain null values. I also decided to keep only information about athlete's results and his parameters, such as age, height, weight and training style. In this project, I want to explore how athlete's parameters affect their results. 

Here is the final set of columns in my dataset:

- **name** : Athlete's name

Athlete Parameteres:
- **gender** : Athlete's gender
- **age** : Athlete's age
- **height** : Athlete's height
- **weight** : Athlete's weight
- **background** : Athlete's sport background (if any)
- **schedule** : Athlete's workout schedule
- **howlong** : Athlete's crossfit experience

Athlete's Results:
- **candj** : Personal record in Clean and Jerk (weightlifting)
- **snatch** : Personal record in Snatch (weightlifting)
- **deadlift** : Personal record in Deadlift 
- **backsq** : Personal record in Back Squat
- **pullups** : Maximum unbroken pull-ups

## Investigation Overview

In the presentation I'll try to prove that the affect of physical characteristics of a crossfit athlete on their results is less significant than the effort that the athlete puts into their training.
