# Reddit Topic Modeling

## Latent Dirichlet Allocation

Documents have been constructed out of a collection of comments for each post on a subreddit. Comments aren't ordered in any particular way as context does not matter for a probabilistic topic model as context is lost.

Comments were extracted using the PRAW and PSAW libraries in another notebook I've made, this will be commited at some point in the future.

### Documents

#### `lda_comparisons.ipynb`

This is the main notebook containing most of the interesting code relating to different LDA topic models that I've tried, and a variety of different visualizations as well.

#### `lda_testing.ipynb`

This notebook is where I was testing some LDA topic models before moving them to the comparisons notebook, I may remove this in the future.

#### `topic_modeling_playground.ipynb`

A quick and easy notebook to run to create an LDA topic model. This was used to create models for small datasets from r/leagueoflegends and r/SecurityAnalysis

#### `hyperparam_tuning.ipynb`

This notebook contains hyperparameter tuning code for use with gensim LDA models.
