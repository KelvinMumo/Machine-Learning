# Description
The data is obtained from [Kaggle's Titanic ML Prediction competition](https://www.kaggle.com/competitions/titanic/data).
 The challenge is to use 
use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.


| Variable  | Definition                               | Key                                                      |
|-----------|------------------------------------------|----------------------------------------------------------|
| Survived  | Survival                                 | 0 = No, 1 = Yes                                           |
| Pclass    | Ticket class                             | 1 = 1st, 2 = 2nd, 3 = 3rd                                 |
| Sex       | Sex                                      |                                                          |
| Age       | Age in years                             |                                                          |
| SibSp     | # of siblings / spouses aboard the Titanic |                                                          |
| Parch     | # of parents / children aboard the Titanic |                                                          |
| Ticket    | Ticket number                            |                                                          |
| Fare      | Passenger fare                           |                                                          |
| Cabin     | Cabin number                             |                                                          |
| Embarked  | Port of Embarkation                      | C = Cherbourg, Q = Queenstown, S = Southampton            |

### Variable Notes

- **Pclass:** A proxy for socio-economic status (SES)
  - 1st = Upper
  - 2nd = Middle
  - 3rd = Lower

- **Age:** Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5

- **SibSp:** The dataset defines family relations in this way...
  - Sibling = brother, sister, stepbrother, stepsister
  - Spouse = husband, wife (mistresses and fiancés were ignored)

- **Parch:** The dataset defines family relations in this way...
  - Parent = mother, father
  - Child = daughter, son, stepdaughter, stepson
  - Some children travelled only with a nanny, therefore parch=0 for them.
