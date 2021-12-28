# AmExpert-CodeLab

## Description
The project is built during the AmExpert Codelab Hackathon for Credit Card Default Risk Detection

## Dataset
The dataset provided during the contest is added to the repository in the dataset directory

<img width="909" alt="Screenshot 2021-12-29 at 12 12 29 AM" src="https://user-images.githubusercontent.com/67387709/147597095-4db0e08c-69c5-4143-8231-a199aefd8b3d.png">

## Evaluation Metric 
F1 Score
Score on Private dataset = 0.9198

## Feature Engineering
 - Categorical features are encoded to numerical values using Label Encoder
 - Highly correlated features are either removed or merged depending on correlation coefficients
 - Categorical feature NULL values are replaced with the most frequently occuring categories
 - Numerical feature NULL values are filled with the Median

## ML Model Selection
- Various ML Models are testing using different hyperparameters and f1 score
- Extra trees classifier had the highest f1 score.

