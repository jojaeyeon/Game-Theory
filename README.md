# References for the multi-agent decision-making problem (MADP)
## Theoretical studies
### 1. Nash equilibrium problem (NEP)
#### Rosen, J. Ben. "Existence and uniqueness of equilibrium points for concave n-person games." Econometrica: Journal of the Econometric Society (1965): 520-534. [link](https://www.jstor.org/stable/1911749)
- Existence and Uniqueness of Nash equilibrium for the NEP.

#### Tinti, Federica. "Numerical solution for pseudomonotone variational inequality problems by extragradient methods." Variational analysis and applications. Boston, MA: Springer US, 2005. 1101-1128. [link](https://link.springer.com/chapter/10.1007/0-387-24276-7_63)
- Introduce algorithms to solve the variational inequality problem.
- Khobotov's method, Extragradient method, Solodov and Tseng (S-T) method

#### Frihauf, Paul, Miroslav Krstic, and Tamer Basar. "Nash equilibrium seeking in noncooperative games." IEEE Transactions on Automatic Control 57.5 (2011): 1192-1207. [link](https://ieeexplore.ieee.org/abstract/document/6060862/)
- Locally stable convergence to Nash equilibria in static, noncooperative games.
- The algorithm is based on the extremum-seeking approach.

#### Malitsky, Yu. "Projected reflected gradient methods for monotone variational inequalities." SIAM Journal on Optimization 25.1 (2015): 502-520. [link](https://epubs.siam.org/doi/abs/10.1137/14097238X)
- The projected reflected gradient descent (PRGD) method is introduced to solve the variational inequality problem.

### 2. Generalized Nash equilibrium problem (GNEP)
#### Facchinei, Francisco, and Christian Kanzow. "Generalized Nash equilibrium problems." 4or 5.3 (2007): 173-210. [link](https://link.springer.com/article/10.1007/s10288-007-0054-4)
- Existence and Uniqueness of generalized Nash equilibrium for the GNEP.

#### Lu, Kaihong, Gangshan Jing, and Long Wang. "Distributed algorithms for searching generalized Nash equilibrium of noncooperative games." IEEE transactions on cybernetics 49.6 (2018): 2362-2371. [link](https://ieeexplore.ieee.org/abstract/document/8353496)
- The continuous-time distributed gradient-based projected algorithm is proposed.

#### Nabetani, Koichi, Paul Tseng, and Masao Fukushima. "Parametrized variational inequality approaches to generalized Nash equilibrium problems with shared constraints." Computational optimization and applications 48.3 (2011): 423-452. [link](https://link.springer.com/article/10.1007/s10589-009-9256-3)
- Existence and Uniqueness of generalized Nash equilibrium for the GNEP.

#### Belgioioso, Giuseppe, Angelia Nedić, and Sergio Grammatico. "Distributed generalized Nash equilibrium seeking in aggregative games on time-varying networks." IEEE Transactions on Automatic Control 66.5 (2020): 2061-2075. [link](https://ieeexplore.ieee.org/abstract/document/9130079)
- The algorithm is obtained by combining dynamic tracking, projected-pseudo-gradient, and Krasnosel'sskii-Mann dynamics.

### 3. Single-leader multi-follower (SLMF) problem
#### Jo, Jaeyeon, Jihwan Yu, and Jinkyoo Park. "Computing Algorithm for an Equilibrium of the Generalized Stackelberg Game." arXiv preprint arXiv:2306.05732 (2023). [link](https://arxiv.org/abs/2306.05732)
- Existence and Uniqueness of general Stackelberg equilibrium.
- The PIGD algorithm converges to the general Stackelberg equilibrium.

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

#### Maharjan, Sabita, et al. "Dependable demand response management in the smart grid: A Stackelberg game approach." IEEE Transactions on Smart Grid 4.1 (2013): 120-132. [link](https://ieeexplore.ieee.org/abstract/document/6464552)
- Individual ESS system, SLMF problem (grid vs active users)
- Algorithm: analytical solution for lower-level problem

#### Soliman, Hazem M., and Alberto Leon-Garcia. "Game-theoretic demand-side management with storage devices for the future smart grid." IEEE Transactions on Smart Grid 5.3 (2014): 1475-1485. [link](https://ieeexplore.ieee.org/abstract/document/6782430)
- Individual ESS system, SLMF problem (grid vs active users)
- Algorithm: Interior point solution for minimax, iterative entropic regularization

#### Wang, Yunpeng, et al. "A game-theoretic approach to energy trading in the smart grid." IEEE Transactions on Smart Grid 5.3 (2014): 1439-1450. [link](https://ieeexplore.ieee.org/abstract/document/6798766)
- Individual ESS system, NEP (active users)
- Energy trading; Prove convergence to Nash equilibrium 

#### Nguyen, Hung Khanh, Ju Bin Song, and Zhu Han. "Distributed demand side management with energy storage in smart grid." IEEE Transactions on parallel and distributed systems 26.12 (2014): 3346-3357. [link](https://ieeexplore.ieee.org/abstract/document/6963474)
- Individual ESS system, NEP
- Proximal Decomposition Algorithm

#### Lee, Joohyung, et al. "Distributed energy trading in microgrids: A game-theoretic model and its equilibrium analysis." IEEE Transactions on Industrial Electronics 62.6 (2015): 3524-3533. [link](https://ieeexplore.ieee.org/abstract/document/7001088)
- Individual ESS system, MLMF problem (sellers vs buyers)
- Energy trading; price of anarchy

#### Powell, Warren B., and Stephan Meisel. "Tutorial on stochastic optimization in energy—Part I: Modeling and policies." IEEE Transactions on Power Systems 31.2 (2015): 1459-1467. [link](https://ieeexplore.ieee.org/abstract/document/7097741)
#### Powell, Warren B., and Stephan Meisel. "Tutorial on stochastic optimization in energy—Part II: An energy storage illustration." IEEE Transactions on Power Systems 31.2 (2015): 1468-1475. [link](https://ieeexplore.ieee.org/abstract/document/7100937)
- Algorithm: Control theory, dynamic programming, stochastic programming, robust optimization

#### Tushar, Wayes, et al. "Energy storage sharing in smart grid: A modified auction-based approach." IEEE Transactions on Smart Grid 7.3 (2016): 1462-1475. [link](https://ieeexplore.ieee.org/abstract/document/7387779)
- Shared ESS system, SLMF problem (residential units vs shared facility controllers)
- Capacity trading; Only focus ESS capacity; Does not consider energy charging/discharging.
- Auction policies consists of (1) a determination rule, (2) a payment rule, and (3) a storage allocation rule.

#### Dimitrov, Petio, Luigi Piroddi, and Maria Prandini. "Distributed allocation of a shared energy storage system in a microgrid." 2016 American Control Conference (ACC). IEEE, 2016. [link](https://ieeexplore.ieee.org/abstract/document/7525464)
- Shared ESS system, NEP
- Capacity trading; negotiation process for the optimization of the resoure shares.
- Possible for the small number of users; heuristic policies should be enforced.

#### Wytock, Matt, Nicholas Moehle, and Stephen Boyd. "Dynamic energy management with scenario-based robust MPC." 2017 American control conference (ACC). IEEE, 2017. [link](https://ieeexplore.ieee.org/abstract/document/7963253)
- Model predictive control (MPC)

#### Li, Chaojie, et al. "Efficient computation for sparse load shifting in demand side management." IEEE Transactions on Smart Grid 8.1 (2016): 250-261. [link](https://ieeexplore.ieee.org/abstract/document/7406760)
- Individual ESS system, NEP
- Algorithm: Newton's method

#### Rajasekhar, Batchu, et al. "Collaborative energy management for a residential community: A non-cooperative and evolutionary approach." IEEE Transactions on Emerging Topics in Computational Intelligence 3.3 (2019): 177-192. [link](https://ieeexplore.ieee.org/abstract/document/8721205)
- Individual ESS system, SLMF problem (Communication aggregator vs active users).
- Genetic algorithm to compute Stackelberg equilibrium.

#### Chakraborty, Pratyush, et al. "Sharing storage in a smart grid: A coalitional game approach." IEEE Transactions on Smart Grid 10.4 (2018): 4379-4390. [link](https://ieeexplore.ieee.org/abstract/document/8416778)
- Shared ESS system, coalition game (solution concept: core - shapley value)

#### Etesami, S. Rasoul, et al. "Stochastic games for the smart grid energy management with prospect prosumers." IEEE Transactions on Automatic Control 63.8 (2018): 2327-2342. [link](https://ieeexplore.ieee.org/abstract/document/8267262)
- Individual ESS system, stochastic SLMF problem (grid vs prosumers)
- Prospect theory + Algorithm: distributed learning + no-regret algorithm

#### Alasseur, Clémence, Imen Ben Taher, and Anis Matoussi. "An extended mean field game for storage in smart grids." Journal of Optimization Theory and Applications 184 (2020): 644-670. [link](https://link.springer.com/article/10.1007/s10957-019-01619-3)
- Individual ESS system, extended mean-field game (EMFG)

#### Jo, Jaeyeon, and Jinkyoo Park. "Demand-side management with shared energy storage system in smart grid." IEEE Transactions on Smart Grid 11.5 (2020): 4466-4476. [link](https://ieeexplore.ieee.org/abstract/document/9033984)
- Shared ESS system, GNEP
- Capacity trading; Focus both ESS capacity trading and energy charging/discharging.

#### Mediwaththe, Chathurika P., et al. "An incentive-compatible energy trading framework for neighborhood area networks with shared energy storage." IEEE Transactions on Sustainable Energy 11.1 (2019): 467-476. [link](https://ieeexplore.ieee.org/abstract/document/8626171)
- Shared ESS system, SLMF
- Incentive design, Vickrey-Clarke-Groves Mechanism

#### Jo, Jaeyeon, Jihwan Yu, and Jinkyoo Park. "Incentive Design of Shared ESS Energy Trading Game." IEEE Transactions on Control Systems Technology (2024). [link](https://ieeexplore.ieee.org/abstract/document/10745120)
- Shared ESS system, SLMF problem (shared ESS operator vs active users)
- Incentive design

### 2. EV charging/dispatching, Ride-sharing/hailing
#### Ma, Zhongjing, Duncan S. Callaway, and Ian A. Hiskens. "Decentralized charging control of large populations of plug-in electric vehicles." IEEE Transactions on control systems technology 21.1 (2011): 67-78. [link](https://ieeexplore.ieee.org/abstract/document/6081962)
- EV charging schedule to reduce PAR, NEP, decentralized control

#### Gan, Lingwen, Ufuk Topcu, and Steven H. Low. "Optimal decentralized protocol for electric vehicle charging." IEEE Transactions on Power Systems 28.2 (2012): 940-951. [link](https://ieeexplore.ieee.org/abstract/document/6313962)
- EV charging schedule to reduce PAR, NEP, decentralized control

#### Tushar, Wayes, et al. "Economics of electric vehicle charging: A game theoretic approach." IEEE Transactions on Smart Grid 3.4 (2012): 1767-1778. [link](https://ieeexplore.ieee.org/abstract/document/6295695)
- EV charging schedule, SLMF problem, Stackelberg equilibrium
- Analytical solution can be computed

#### Banerjee, Siddhartha, Carlos Riquelme, and Ramesh Johari. "Pricing in ride-share platforms: A queueing-theoretic approach." Available at SSRN 2568258 (2015). [link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2568258)
- Ride-sharing platform, incentive design
- Queueing theory

#### Xu, Zhe, et al. "Large-scale order dispatch in on-demand ride-hailing platforms: A learning and planning approach." Proceedings of the 24th ACM SIGKDD international conference on knowledge discovery & data mining. 2018. [link](https://dl.acm.org/doi/abs/10.1145/3219819.3219824)
- Ride-hailing, real-time algorithm, combinatorial algorithm, value function-based

#### Lu, Wei, and Luca Quadrifoglio. "Fair cost allocation for ridesharing services–modeling, mathematical programming and an algorithm to find the nucleolus." Transportation Research Part B: Methodological 121 (2019): 41-55. [link](https://www.sciencedirect.com/science/article/pii/S019126151730944X)
- Ride-sharing, coalition game, simple case

#### Sadeghi, Armin, and Stephen L. Smith. "On re-balancing self-interested agents in ride-sourcing transportation networks." 2019 IEEE 58th Conference on Decision and Control (CDC). IEEE, 2019. [link](https://ieeexplore.ieee.org/abstract/document/9030043)
- Ride-sharing platform management (NP-hard), matching rule
- Provide algorithms to find near-optimal control

#### Ma, Hongyao, Fei Fang, and David C. Parkes. "Spatio-temporal pricing for ridesharing platforms." ACM SIGecom Exchanges 18.2 (2020): 53-57. [link](https://dl.acm.org/doi/abs/10.1145/3440968.3440975)
- Ride-sharing platform management, incentive design
- simple case

#### Afeche, Philipp, Zhe Liu, and Costis Maglaras. "Ride-hailing networks with strategic drivers: The impact of platform control capabilities on performance." Rotman School of Management Working Paper 3120544 (2022): 18-19. [link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3120544)
- Ride-hailing platform management, game-theoretic fluid model

### 3. Cloud
#### Wolke, Andreas, Martin Bichler, and Thomas Setzer. "Planning vs. dynamic control: Resource allocation in corporate clouds." IEEE Transactions on Cloud Computing 4.3 (2014): 322-335. [link](https://ieeexplore.ieee.org/abstract/document/6910277)
- Static, dynamic resource allocation
- Algorithm: round robin, optimization and overbooking, reactive control, proactive control
