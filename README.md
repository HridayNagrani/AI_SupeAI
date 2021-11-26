# AI_SupeAI
## Introduction
The  finical  security  investment  market  is  tradi-tionally  dominated  by  the  people  with  a  skillset  inquantitative  modelling  which  has  an  ultimate  goalfor  getting  the  best  prediction  of  future’s  price,  asthat  can  involve  a  high  level  of  automation,  dueto  advancement  into  technology  and  computationresources,  leveraging  machine  learning  for  quanti-tative  programming  become  the  hot  topic  in  themarket, also the real world finical data is very noisyand  non-stationary  which  make  this  pretty  hardand  also  the  security  price  provides  details  abouta very small part of the market which put us in thesituation  where  we  can  not  observe  actual  marketstates,  that’s  why  some  methods  of  quantitativemodelling  like  technical  analysis  with  dual  thruststrategy,  Machine  learning-based  approach,  deepneural network-based predictor and latest reinforce-ment learning-based approaches are in practice
## Approach
![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/unknown.png)
Different RL techniques were used while implimention. 
### DQN
![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/A2C.jpg)

DQN(Deep Q learning) is a reinforcement learn-ing algorithm that combines Q-Learning with deepneural  networks  thus  letting  RL  work  for  com-plex and high-dimensional environments, like videogames, or robotics.
### A2C
![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/DQN.jpg)

A2C (Advantage Actor Critic) - Merger of Value based and Policy based techniques.
A2C Model has 2 parts:
a) Compute action based on state
b) Produce Q values of action
Actor: input = state ; output = action; Behaviour of learning the optimal policy (Policy Based)
Critic: input=  environment  and  action  by  actor;output  =  action  value  (Q-value)  .  Evaluates  actionby computing value function (Value based) 
Q value= State value + Advantage value (How good actionis  compared  to  others  at  a  given  state).

## Results

Comparision Table for different models and datasets and tuning of window size.

![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/table.png)

Bitcoin,A2C,window_size=10

![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/Result_1_dummy.jpg)

Nifty-50,A2C,window_size=8

![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/Result_2_1.jpg)

Bitcoin,DQN,window_size=8

![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/dqnBit.JPG)

Nifty-50,DQN,window_size=8

![Image](https://github.com/HridayNagrani/AI_SupeAI/blob/main/DQN.png)

### Installation
You can vie the requirnments.txt file for installation purposes. Also you can run files directly into Google Colaboratory https://colab.research.google.com/.

All the work was done on Colab only for this project.

### References 
1)Y. Liu, Q. Liu, H. Zhao, Z. Pan, and C. Liu, “Adaptive Quantitative Trading: An Imitative Deep Reinforcement Learning Approach”, AAAI, vol. 34, no. 02, pp. 2128-2135, Apr. 2020..

2)Sutton, R. S.; McAllester, D. A.; Singh, S. P.; and Mansour, Y.
2000. Policy gradient methods for reinforcement learning with
function approximation. In NeurIPS, 1057–1063

3)Yu, P.; Lee, J. S.; Kulyatin, I.; Shi, Z.; and Dasgupta, S. 2019.
Model-based deep reinforcement learning for dynamic portfo-
lio optimization. arXiv preprint arXiv:1901.08740.

4)Dataset (Midesem): https://www.kaggle.com/psheon/quantitative-trading

5)MDP:https://towardsdatascience.com/understanding-the-markov-decision-process-mdp-8f838510f150

6)OpenAIGym: https://gym.openai.com/

7)StableBaselines: https://stable-baselines.readthedocs.io/en/master/

8)TensorTrade: https://github.com/tensortrade-org

9)Nifty-50 Dataset: https://www.kaggle.com/abhishekkoshta/6-year-nifty50-historical-data-of-5-30-min-candle?select=5min$_$N50$_$10yr.csv

10)Bitcoin Dataset: https://developers.coinbase.com/api/v2

