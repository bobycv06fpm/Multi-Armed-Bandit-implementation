# Multi-Armed-Bandit-implementation
Building multi-armed bandits from scratch

An implementation of epsilon greedy, UCB, and contextual multi-armed bandits, and an off-policy evaluator.

## Dataset
2 MB dataset.txt

- 10,000 lines (i.e., rows) corresponding to distinct site visits by users—events in the language of this part; 

- Each row comprises 102 space-delimited columns of integers:

   – Column 1: The arm played by a uniformly-random policy out of 10 arms (news articles);

   – Column 2: The reward received from the arm played—1 if the user clicked 0 otherwise; and

   – Columns 3–102: The 100-dim flattened context: 10 features per arm (incorporating the content of the article and its match with the visiting user), first the features for arm 1, then arm 2, etc. up to arm 10.

#### To-do
- Improve code
