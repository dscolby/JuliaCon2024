![CausalELM Logo](https://github.com/dscolby/dscolby.github.io/blob/main/github_logo.jpg)
![JuliaCon 2024 Logo](https://media.licdn.com/dms/image/D560BAQFv7-xPeMvPRw/company-logo_200_200/0/1702315068225/teamjuliacon_logo?e=2147483647&v=beta&t=MZ_TCC8_Ci_Tf3Li6PHAerbdurM3hrY3CQWZXj6kxi8)

This repo contains all the notebooks and slides for the JuliaCon 2024 talk Causal Machine Learning with CausalELM. If you would like to follow along with the presentation, you can run the notebooks by following the instructions below.
## Setup
1. Clone this repository.
   ```bash
   git clone https://www.github.com/dscolby/JuliaCon2024.git
   ```
2. In the directory you just cloned, open Julia from a terminal and activate the environment.
   ```bash
   $julia
   ```
   ```Julia
   julia> ]
   (@v1.10) pkg> activate .
   (JuliaCon2024) pkg>
   ```
3. Install the dependencies.
   ```Julia
   (JuliaCon2024) pkg> instantiate
   ```
4. From VS Code or another IDE, open the double_machine_learning.ipynb and doubly_robust_estimation.ipynb notebooks.
## Questions and Contributions
Feel free to ask me questions here or submit issues here and on the CausalELM repository. Also, please consider contributing to CausalELM or helping develop a causal ML API for Julia.
