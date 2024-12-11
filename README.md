# References for the multi-agent decision-making problem (MADP)
## Theoretical studies
### 1. Nash equilibrium problem (NEP)
#### Rosen, J. Ben. "Existence and uniqueness of equilibrium points for concave n-person games." Econometrica: Journal of the Econometric Society (1965): 520-534. [link](https://www.jstor.org/stable/1911749)
- Existence and Uniqueness of Nash equilibrium for the NEP.

#### Frihauf, Paul, Miroslav Krstic, and Tamer Basar. "Nash equilibrium seeking in noncooperative games." IEEE Transactions on Automatic Control 57.5 (2011): 1192-1207. [link](https://ieeexplore.ieee.org/abstract/document/6060862/)
- Locally stable convergence to Nash equilibria in static, noncooperative games.
- The algorithm is based on the extremum-seeking approach.

### 2. Generalized Nash equilibrium problem (GNEP)
#### Facchinei, Francisco, and Christian Kanzow. "Generalized Nash equilibrium problems." 4or 5.3 (2007): 173-210. [link](https://link.springer.com/article/10.1007/s10288-007-0054-4)
- Existence and Uniqueness of generalized Nash equilibrium for the GNEP.

#### Lu, Kaihong, Gangshan Jing, and Long Wang. "Distributed algorithms for searching generalized Nash equilibrium of noncooperative games." IEEE transactions on cybernetics 49.6 (2018): 2362-2371. [link](https://ieeexplore.ieee.org/abstract/document/8353496)
- The continuous-time distributed gradient-based projected algorithm is proposed.
  
#### Belgioioso, Giuseppe, Angelia Nedić, and Sergio Grammatico. "Distributed generalized Nash equilibrium seeking in aggregative games on time-varying networks." IEEE Transactions on Automatic Control 66.5 (2020): 2061-2075. [link](https://ieeexplore.ieee.org/abstract/document/9130079)
- The algorithm is obtained by combining dynamic tracking, projected-pseudo-gradient, and Krasnosel'sskii-Mann dynamics.

## Application stuides
### 1. Smart Grid
#### Mohsenian-Rad, Amir-Hamed, et al. "Autonomous demand-side management based on game-theoretic energy consumption scheduling for the future smart grid." IEEE transactions on Smart Grid 1.3 (2010): 320-331. [link](https://ieeexplore.ieee.org/abstract/document/5628271)
- Individual ESS system, NEP
- The cost function should be a quadratic structure.

#### Mohsenian-Rad, Amir-Hamed, et al. "Optimal and autonomous incentive-based energy consumption scheduling algorithm for smart grid." 2010 Innovative Smart Grid Technologies (ISGT). IEEE, 2010. [link](https://ieeexplore.ieee.org/abstract/document/5434752)
- Individual ESS system, NEP
- The cost function should be a quadratic structure.

#### Atzeni, Italo, et al. "Demand-side management via distributed energy generation and storage optimization." IEEE transactions on smart grid 4.2 (2012): 866-876. [link](https://ieeexplore.ieee.org/abstract/document/6297498)
- Individual ESS system, NEP
- Proximal Decomposition Algorithm

#### Nguyen, Hung Khanh, Ju Bin Song, and Zhu Han. "Distributed demand side management with energy storage in smart grid." IEEE Transactions on parallel and distributed systems 26.12 (2014): 3346-3357. [link](https://ieeexplore.ieee.org/abstract/document/6963474)
- Individual ESS system, NEP
- Proximal Decomposition Algorithm

#### Lee, Joohyung, et al. "Distributed energy trading in microgrids: A game-theoretic model and its equilibrium analysis." IEEE Transactions on Industrial Electronics 62.6 (2015): 3524-3533. [link](https://ieeexplore.ieee.org/abstract/document/7001088)
- Individual ESS system, MLMF problem
- Energy trading; price of anarchy

#### Tushar, Wayes, et al. "Energy storage sharing in smart grid: A modified auction-based approach." IEEE Transactions on Smart Grid 7.3 (2016): 1462-1475. [link](https://ieeexplore.ieee.org/abstract/document/7387779)
- Shared ESS system, SLMF problem (residential units vs shared facility controllers)
- Capacity trading; Only focus ESS capacity; Does not consider energy charging/discharging.
- Auction policies consists of (1) a determination rule, (2) a payment rule, and (3) a storage allocation rule.

#### Wytock, Matt, Nicholas Moehle, and Stephen Boyd. "Dynamic energy management with scenario-based robust MPC." 2017 American control conference (ACC). IEEE, 2017. [link](https://ieeexplore.ieee.org/abstract/document/7963253)
- Model predictive control (MPC)

#### Rajasekhar, Batchu, et al. "Collaborative energy management for a residential community: A non-cooperative and evolutionary approach." IEEE Transactions on Emerging Topics in Computational Intelligence 3.3 (2019): 177-192. [link](https://ieeexplore.ieee.org/abstract/document/8721205)
- Individual ESS system, SLMF problem (Communication aggregator vs active users).
- Genetic algorithm to compute Stackelberg equilibrium.

#### Chakraborty, Pratyush, et al. "Sharing storage in a smart grid: A coalitional game approach." IEEE Transactions on Smart Grid 10.4 (2018): 4379-4390. [link](https://ieeexplore.ieee.org/abstract/document/8416778)
- Shared ESS system, coalition game (solution concept: core - shapley value)

#### Alasseur, Clémence, Imen Ben Taher, and Anis Matoussi. "An extended mean field game for storage in smart grids." Journal of Optimization Theory and Applications 184 (2020): 644-670. [link](https://link.springer.com/article/10.1007/s10957-019-01619-3)
- Individual ESS system, extended mean-field game (EMFG)
