Q1: In ε-greedy action selection, for the case of two actions and ε = 0.5, what is the probability that the greedy action is selected?

  In the $\epsilon$-greedy action selection algorithm, an agent takes the best-known action ("greedy action") with a probability of $1-\epsilon$ and takes a random action with a probability of $\epsilon$.
  In the case where there are only two actions (let's call them $A$ and $B$ ), and $\epsilon=0.5$ :
  - The probability of taking a random action is 0.5 .
  - Since there are two actions, the random action will be either $A$ or $B$ with a probability of $0.5 \times \frac{1}{2}=0.25$ for each action.
  Therefore, the probability of taking the greedy action can be considered in two parts:
  1. The probability of taking the greedy action directly $(1-\epsilon=0.5)$.
  2. The probability of taking the greedy action when a random action is selected $(0.25)$.
  So, the total probability of taking the greedy action would be:
  $$
  \text { Probability of taking greedy action }=(1-\epsilon)+\left(\epsilon \times \frac{1}{2}\right)
  $$

