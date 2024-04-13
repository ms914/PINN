# PINN

Optimisation in
- space trajectory
- time trajectory

Many optimisation problems are inverse problems. Traditional optimisation is trying to solve this by multiple forward passes and gradient descend methods to converge to a solution. PINNs can solve the inverse problem. Incorporating physics into the learning process narrows the parameter space.

In vanilla optimisation algorithms, the time trajectory is uncontrolled and explores much parameter space with randomness. PINN's implement a variational principle (Fermats principle, Feynmans path integral). Applications are in chip design.

1. [Solving real-world optimization tasks using physics-informed neural computing](https://doi.org/10.1038/s41598-023-49977-3)
