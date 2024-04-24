# Anime-Analysis
## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on anime from the MyAnimeList Database APIs. For detailed walkthrough, please view the source code in order from:
  1. Data Preparation
  2. Initial Exploration (of ranking and success)
  3. Response Variable
  4. Data Visualization
  5. Random Forest Classifier
  
## Contributors
  - @TanGuiShan - Data Analysis, Data Preparation
  - @Ruijie - Exploration, Problem formation
  - @Yu Zhengwen- Visualisation, Preparation, Deconflicting pull requests :/
  - We all helped one another and this could not be done without all of us :D
  
## Problem Definition
  - What are the key factors that contribute to a well-received anime series, considering aspects of format (structure, pacing, episodes, lengths), content(genre, themes, characters development), and source material (originality, faithfulness to source, adaptation quality)?
- This project seeks to identify and implement strategies that maximize the probability of creating a well-received anime series. By analyzing trends, audience preferences, and series production practices, we can make informed decisions regarding source material selection, narrative development, and show format. The ultimate goal is to produce an anime series that achieves strong viewership numbers worldwide, garners a high number of positive reviews, and fosters audience engagement.


  
## Model Used
- Regressors
  - Linear/polynomial
  - Decision tree
  - Random forest
  - Gradient boosting
  - Extra trees
- Classifiers
  - Random Forest (Main)

## Conclusion
- Popular genres like drama and romance as well as having multiple adaptations can help boost success rate.  
- It is to note that there might be a reverse relationship for sequels and adaptations because sometimes these are only made after an anime is already successful. 
- Adapting from an already popular source material also helps  
- We also believe it is best to use the tried and true, 1 season long, 12 eps 20min format.  
- Of course, it is best to have the better studios work on the anime but this may not always be possible as they often have a strict criteria and lots of demand.
- Lastly, this is only the tip of the iceberg, we had to reduce the entries due to lots of invalid data, and a few variables like gross earnings or TV viewership can help understand our problem better. 
Conclusions for insights and recommendations

## Learning Outcome from this project
- Parsing deeply nested JSON objects
- Breaking down our problem to smaller chunks and steps
- Exposed to more advanced Regression/Classification Techniques
  - Linear/Polynomial Regression, Gradient Boosting, etc.
  - Random Forest Tree
- Working as a team using GitHub
  - Managing merge conflicts
  - Implementing a One-feature-one-branch workflow (Generally)
  - Many times something went wrong but luckily we could diff with previous commits and see what the problem likely was or revert changes if needed :D

## Reference
  - https://www.kaggle.com/datasets/aludosan/myanimelist-anime-dataset-as-20190204
  - https://www.kaggle.com/datasets/azathoth42/myanimelist/data
  - https://www.kaggle.com/datasets/svanoo/myanimelist-dataset/data

SC1015_23/24
