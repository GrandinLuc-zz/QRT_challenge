# QRT_challenge

This is my code for the data challenge proposed by QRT, you can check out the modalities of the challenge and a thorough description of the project here: 
https://challengedata.ens.fr/participants/challenges/44/

In this challenge, the objective is to clusterize classes of assets that are liquid and that behaves like illiquid assets so the company can use their own buying signals on the illiquid ones to invest on the liquid one. This is because investing a lot of money in illiquid assets will change the price so prominently that it would impede the market too much and make the strategy it less perfomant. Therefore, if you invest in liquid assets that are on the same cluster as illiquid ones that you get a buying signal, you will make gains much more close to the theorical no-market impact stategy you came up with.

In this notebook, I first got familiar with the different datasets by using different data visualization techniques and toying around with the data. Once I got the hang of the data, I splitted the train data into two subsets in order to train and test my machine learning algorithms. I used the following algorithms:
- Random forest
- Cat boost
- XG boost

I had accuracy ranging from 65% to 70% and I then saved the results in a .csv file following the guidelines for formatting that were asked for the challenge.
