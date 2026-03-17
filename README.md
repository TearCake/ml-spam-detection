# SMS Spam Detection

## Results
| Model | Accuracy | Precision |
|-------|----------|-----------|
| Multinomial NB | 97.09% | 1.00 |
| KNN | 90.52% | 1.00 |
| Random Forest | 97.38% | 0.98 |
| Extra Trees | 97.48% | 0.97 |
| XGBoost | 96.80% | 0.95 |

## Best Model
Multinomial Naive Bayes — Precision of 1.0 with 97% accuracy

## Why Precision Over Accuracy
For spam detection, a false positive (legitimate email flagged as spam) 
is far more costly than a false negative (spam reaching inbox). 
Missing an important email from your bank or college is worse than 
receiving one extra spam message. High precision ensures the model 
never wrongly flags legitimate messages as spam.

## What I Learned (Different From Previous Projects)
- In spam detection, we consider precision over accuracy because a false
  positive (legitimate email flagged as spam) is far more costly than a
  false negative (spam reaching inbox).
- Voting Classifier and Stacking combine multiple models but don't always 
  beat a single well chosen model
