# PINN

Optimisation in
- space trajectory
- time trajectory

Many optimisation problems are inverse problems. Traditional optimisation is trying to solve this by multiple forward passes and gradient descend methods to converge to a solution. PINNs can solve the inverse problem. Incorporating physics into the learning process narrows the parameter space. Traditional optimisation like GA, MC use forward methods in a trial and error fashion. The physics equation loss can be replaced with learned physics equations (SINDY) and are equally usable (future application in fusion).

In vanilla optimisation algorithms, the time trajectory is uncontrolled and explores much parameter space with randomness. PINN's implement a variational principle (Fermats principle, Feynmans path integral). Applications are in chip design.

1. [Solving real-world optimization tasks using physics-informed neural computing](https://doi.org/10.1038/s41598-023-49977-3) [https://github.com/jaem-seo/pinn-optimization](https://github.com/jaem-seo/pinn-optimization)
2. MAxwellNet: https://github.com/limjoowon/maxwellnet

Atomistic models

1. Pun, G.P.P., Batra, R., Ramprasad, R. et al. Physically informed artificial neural networks for atomistic modeling of materials. Nat Commun 10, 2339 (2019). [https://doi.org/10.1038/s41467-019-10343-5](https://doi.org/10.1038/s41467-019-10343-5)
   
3. [https://ntrs.nasa.gov/api/citations/20200002821/downloads/20200002821.pdf](https://ntrs.nasa.gov/api/citations/20200002821/downloads/20200002821.pdf)
[https://wise-materials.org/wp-content/uploads/2024/03/MercadoZhang-WISE-Dialogue-2024.pdf](https://wise-materials.org/wp-content/uploads/2024/03/MercadoZhang-WISE-Dialogue-2024.pdf)   
5. [https://www.lammps.org/workshops/Aug19/talk_hickman.pdf](https://www.lammps.org/workshops/Aug19/talk_hickman.pdf)

6. Long range interactions with delta learning: Data-efficient machine learning for molecular crystal structure prediction [https://pubs.rsc.org/en/content/articlehtml/2021/sc/d0sc05765g](https://pubs.rsc.org/en/content/articlehtml/2021/sc/d0sc05765g)
   
8. SciANN


**Symmetry in Machine Learning, Hamiltonian physics **
Steve Brunton (2022):https://arxiv.org/pdf/2311.00212

