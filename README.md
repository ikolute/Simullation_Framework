# Simullation_Framework
Tendermint algorithn https://github.com/tendermint/tendermint/blob/v0.34.x/spec/consensus/proposer-selection.md
Задача:
Test # 1
1.	For a given number of validators and for a given range of maximum voting power for 1 validator (e.g. from 10% to 90%) simulate VP (in percentage from 0% to 100%) for other validators (so as the sum of VP equals to 1). Distributions to consider: uniform, truncated normal, power law – all normalized to get numbers from 0 to 1 so as the sum equals to 1.
2.	Run the round-robin algorithm and calculate the number of subsequent wins for each validator. Number of rounds (total stake amount) = 1000.
3.	Define the number of subsequent wins for the validator with maximum VP. 
4.	Get a graph of the dependence of the number of the subsequent wins on the corresponding maximum VP. Save dataframe.
5.	Define a VP threshold under which the number of subsequent wins equals to zero.
6.	Run many simulations and defined average threshold.
7.	Repeat calculations for different number of validators.
8.	Get a graph of the dependence of the VP threshold on the number of validators.
Дальше выпатилсь описать появления валидаторов с помощью функций рапсределения файл Erlang.ipynb

P.S. Выложен не весь код, только разрешенное со стороны работодателя.
