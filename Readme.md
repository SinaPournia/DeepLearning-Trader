
# DeepLearning Trader

the porpuse of this project is make a neural network model to buy and sell in stock or forex market 

# how it works :


Reinforcement learning ==> its a technique to make a model ( a neural network ) witch act with enviroment and try to find out how treat with enviroment to get maximum reward  

agent produce action and get reward for given action from enviroment and updated it self with that reward for produce better action

![](images/ReinforcementLearning.png)

So in our situation backtrader is enviorment, witch simulates stock or forex market with real data history 

for example single row of data frame included :

[Open,High,Low,Close,Volume]


then action given by model in that state to decide buy or sell and get reward
if we buy that means price will increase and if we sell that means price will be decrease 



PPO ==> its technique inside reinforcement learning field 
there is two different model whitch feedbacks each other to achive better result 

![](images/ACtorCritic.jpg)

for train model better and maximize performance inside agent two model acts together and feedback each other to how to acts

its like two people in one team,

Critic => predict the maximum reward can get from this situation base on latest experince 
Actor  => predict the best action in that situation whitch leads to maximum reward 

this two works parallel and feedback each other to have a better sight for present state 





for more information : 
https://www.youtube.com/watch?v=e3Jy2vShroE&t=125s


for more information : 

https://www.youtube.com/watch?v=5P7I-xPq8u8&t=7s


