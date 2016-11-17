# Predicting Political Lean or Bias in Text

## Ask
- Where on the political spectrum am I according to what I read?
- How can I use this to balance my perspective?

## Collect
- Pulled roughly 27,000 articles from the web that were already labeled with one of 5 politibal leans (left, lean left, center, lean right, right, other/mixed)
- Dumped in local postgres db

## Explore
#### Hypothesis
- NLP is a difficult subject area, likely leading to lack of accuracy
- nclean text will lead to poor accuracy
- Domain will be highly relevant
- Naive Bayes will probably be best

#### Notebook
- https://github.com/Stanleyyork/sfdat28-stevens/blob/master/projects/political_lean/Exploration.ipynb

## To-Do
#### Explore
- Continue exploring
- Testing out new features and models
- Finding out why existing models work so well

#### Model
- Settle on a model to use

#### Communicate + Apply
- Use model to predict 11k personal articles and another 80k articles
- Grab other content, such as analyzing the articles that my friends post on facebook or twitter
