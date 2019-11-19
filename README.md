# Reinforcement Learning and Multi-Armed Bandits

A bandit is defined as someone who steals your money. A one-armed bandit is a simple slot machine wherein you insert a coin into the machine, pull a lever, and get an immediate reward. But why is it called a bandit? It turns out all casinos configure these slot machines in such a way that all gamblers end up losing money!

A multi-armed bandit is a complicated slot machine wherein instead of 1, there are several levers which a gambler can pull, with each lever giving a different return. The probability distribution for the reward corresponding to each lever is different and is unknown to the gambler.

The task is to identify which lever to pull in order to get maximum reward after a given set of trials. This problem statement is like a single step Markov decision process.

Solution strategies:

* No Exploration (Greedy Approach)
* Epsilon Greedy
* Decayed Epsilon Greedy
* Softmax Exploration
* Upper Confidence Bound (UCB




## Installation Using Anaconda

### Create environment
conda env create -f environment.yml

### Activate environment
source activate RLtalk

### Set up Twitter API credentials
In order to run the streaming Twitter examples, you will need a set of developer keys stored in a file called keys.txt. Go [here](https://apps.twitter.com/) to get your own credentials.
