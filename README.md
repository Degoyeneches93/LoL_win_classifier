# Predictive Analysis of Matches in League of Legends

League of Legends is one of the most popular and competitive games in the world, with millions of players and a highly professionalized esports ecosystem. As players climb the ranked ladder, the factors that determine success in a match become more complex and less obvious.
This project aims to analyze over 9,000 matches from players in high Diamond to low Master elo—a range where decision-making, macro-strategy, and team coordination play a significant role.

**Audience:**

- Competitive players looking to optimize their decision-making.
- Esports coaches or analysts.
- Data scientists interested in applying predictive analytics to multiplayer games.
- Anyone interested in understanding how data can explain performance in complex video games.

**Analytical Context**

The dataset includes detailed per-match metrics for both teams (red and blue), such as:
- Vision statistics (wards)
- KDA (kills, deaths, assists)
- Objectives taken (dragons, heralds, towers)
- Gold and experience differences
- Farming pace and gold per minute

**Important:**
**The information is aggregated at the team level, not by individual player.**

This allows us to build models that evaluate collective performance and predict match outcomes based on these objective metrics.  
Note: Later sections will include a basic dictionary describing each variable.

**Hypotheses and Key Questions**

- Hypothesis 1 (Exploratory Analysis):
"There are certain key indicators that significantly increase the probability of victory, such as control of neutral objectives (dragons/heralds) and vision (wards)."

- Hypothesis 2 (Predictive Modeling):
"It is possible to predict the winning team with good accuracy using only the team's objective performance data throughout the match."

These two hypotheses are designed such that the first one guides exploratory and univariate/bivariate analysis of the dataset, and its findings serve as input for modeling the second hypothesis.

**Guiding Questions**

Exploration:

- What statistical differences exist between winning and losing teams?
- What factors are most associated with victory?
- Does controlling dragons/heralds/towers have more impact than kills?
- Are there systematic differences between red and blue teams?

Prediction:

- Can we build a model that predicts match outcome based on final statistics?
- Which variables are most important for the model?
- How accurate can predictions be without information on champions or picks?

**General Objective**

Analyze matches in the Diamond–Master elo to identify key factors that determine victory and build a predictive model based on objective team data.

**Specific Objectives:**

- Conduct a comparative exploratory analysis between winning and losing teams.
- Identify the metrics most correlated with match outcomes.
- Design a classification model to predict whether the red or blue team will win.
- Evaluate the relative importance of each variable in determining the outcome.

