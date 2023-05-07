---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# About me
I am a fourth-year Machine Learning Ph.D. student in the H. Milton Stewart School of Industrial and Systems Engineering ([ISyE](https://www.isye.gatech.edu/)) at [Georgia Tech](https://www.gatech.edu/) and a research assistant at NSF Artificial Intelligence Research Institute for Advances in Optimization ([AI4OPT](https://www.ai4opt.org/)). My research with Prof. [Pascal Van Hentenryck](https://sites.gatech.edu/pascal-van-hentenryck/) focuses on fusing **Machine Learning** and **Mathematical Optimization** into large-scale, intelligent systems with applications in energy systems ([Risk-Aware Market Clearing](https://ramc.isye.gatech.edu/)), supply chains (Data-Driven Service Network Design) and ride-hailing systems (Reinforcement Learning for Vehicle Relocation). The research methodologies are the following:
* **Learning Optimization Proxy**: Learning ML surrogate for computationally expensive optimization models
* **Learning to Optimize**: Integrate ML and optimization solvers to accelerate optimization solving
* **End-to-end learning**: Design efficient and scalable differentiable optimization layers for end-to-end optimization learning

My research goal is to design reliable, efficient, and scalable decision-making solutions for systems at a massive scale driven by societal challenges in energy, logistics, and supply chains.

# Education
* Ph.D. in Machine Learning, Georgia Institute of Technology, 2024 (expected)
* Ph.D. Minor: Operation Research
* B.S. in Electrical Engineering, Huazhong University of Science and Technology, 2019

# Work experience
* Jan 2021 - Present: Graduate Research Assistant in [AI4OPT](https://www.ai4opt.org/)
  * Research: Integrating machine learning and optimization to enable reliable intelligent decision making at massive scale,
  * Service: Hosting AI4OPT student ML methodology reading group & Mentoring junior Ph.D. students and undergraduates.
* Jan 2023 - Present: Research Intern in [Kinaxis](https://www.kinaxis.com/en)
  * Developing learning-augmented optimization solver for [rapid response](https://www.kinaxis.com/en/solutions/platform?utm_source=google&utm_medium=ppc&utm_campaign=7015Y000003sEekQAE&utm_term=131899310774&utm_content=project-authority&gclid=EAIaIQobChMIkvuv0PLw_QIVkgKtBh1rMgeyEAAYASAAEgJF5_D_BwE) (Kinaxis core product) in the supply chain planning
* Aug 2022 - Present: Research Assistant for Industrial Collaborator in [UPS](https://www.ups.com/us/en/global.page)
  * Developed symmetry-breaking tactical load planning model to generate consistent load plan for operators,
  * Developed learning optimizaiton proxies for UPS tactical load planning problem,
  * Learning optimizaiton proxies generates near-optimal and feasible solutions with orders of magnitude faster than [Gurobi](https://www.gurobi.com/).
* Jan 2021 - May 2023: Research Assistant for Industrial Collaborator in [MISO](https://www.misoenergy.org/) [5][7][8][9][11]
  * Proposed the first ML surrogate to **large-scale security-constrained economic dispatch** problem on [RTE](https://www.rte-france.com/) system with 6,708 buses in the MISO pipeline. The proposed proxies produce the optimal dispatches with relative errors 0.6% within milliseconds [5].
  * Proposed end-to-end, **self-supervised** ML surrogate for DC optimal power flow on up to **30,000** buses system (the largest open-sourced system) with **feasibility guarantee**. It achieves **5 orders of magnitude faster** than Gurobi (the fastest commercial solver) with the optimality gap less than **0.5%** [11].
  * Proposed confidence-aware graph neural network to accelerate solving **security-constrained unit commit-ment** on [RTE](https://www.rte-france.com/) system (a mixed-integer linear program with millions of decision variables and constraints). It generates feasible solutions with **0.77%** optimality gap with **4 times speedup** than [Gurobi](https://www.gurobi.com/) [8].
* Jun 2020 - Aug 2020: Research Intern in [Ant Financial](https://www.antgroup.com/en/)
* Aug 2019 - Present: Graduate Research Assistant
  * Georgia Institute of Technology
  
# Publication
## Pre-prints and working papers:

[11] **Wenbo Chen**, Mathieu Tanneau and Pascal Van Hentenryck. End-to-End Feasible Optimization Proxies for Large-Scale Economic Dispatch. [[Paper](https://arxiv.org/abs/2304.11726)], submitted to IEEE Transactions on Power Systems.

[10] **Wenbo Chen**, Reem Khir and Pascal Van Hentenryck. Two-Stage Learning For the Flexible Job Shop Scheduling Problem.
[[Paper](https://arxiv.org/abs/2301.09703)]

[9] Seonho Park, **Wenbo Chen**, Terrence W.K. Mak and Pascal Van Hentenryck. Compact Optimization Learning for AC Optimal Power Flow. 
[[Paper](https://arxiv.org/pdf/2301.08840.pdf)], under revision of IEEE Transactions on Power Systems.

[8] Seonho Park, **Wenbo Chen**, Dahye Han, Mathieu Tanneau, Pascal Van Hentenryck. Confidence-Aware Graph Neural Networks for Learning Reliability Assessment Commitments. 
[[Paper](https://arxiv.org/pdf/2211.15755.pdf)], under revision of IEEE Transactions on Power Systems.

[7] Oliver Stover, Pranav Karve, Sankaran Mahadevan, **Wenbo Chen**, Haoruo Zhao, Mathieu Tanneau, Pascal Van Hentenryck. Just-In-Time Learning for Operational Risk Assessment in Power Grids. 
[[Paper](https://arxiv.org/pdf/2209.12762.pdf)], submitted to IEEE Transactions on Power Systems.

## Publications:

[6] Enpeng Yuan, **Wenbo Chen**, Pascal Van Hentenryck. Reinforcement Learning from Optimization Proxy for Ride-Hailing Vehicle Relocation. Journal of Artificial Intelligence Research, 2022. [[Paper](https://www.jair.org/index.php/jair/article/view/13794)]

[5] **Wenbo Chen**, Seonho Park, Mathieu Tanneau, Pascal Van Hentenryck. Learning Optimization Proxies for Large-scale Security-Constrained Economic Dispatch. PSCC-EPSR, 2022. [[Paper](https://www.sciencedirect.com/science/article/pii/S0378779622006629)]

[4] Haoran Sun, **Wenbo Chen**, Hui Li, Le Song. Improving Learning to Branch via Reinforcement Learning. Learning Meets Combinatorial Optimization Workshop, NeurIPS, 2020. 
[[Paper](https://openreview.net/pdf?id=z4D7-PTxTb)]

[3] **Wenbo Chen**, Anni Zhou, Pan Zhou, Liang Gao, Shouling Ji, and Dapeng Oliver Wu.  Privacy-Preserving Online Learning Approach for Incentive-based Demand Response in Smart Grid. IEEE System Journal, 2019, [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8642292&tag=1)]

[2] Pan Zhou, **Wenbo Chen**, Shouling Ji, Hao Jiang, Li Yu and Dapeng Oliver Wu. Privacy-Preserving Online Task Allocation in Edge-Computing-Enabled Massive Crowdsensing. IEEE Internet of Things Journal, 2019. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8662620)]

[1] **Wenbo Chen**, Pan Zhou, Shaokang Dong, Shimin Gong, Menglan Hu, Kehao Wang, and Dapeng Oliver
Wu. Tree-based Contextual Learning for Online Job or Candidate Recommendation with Big Data Support
in Professional Social Networks. IEEE ACCESS, 2018. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8552383)]

<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=450&t=tt&d=egpxRs9v7VzCUiiWU5X_DY0KyHy0rYIzCgDf9wHE8e8'></script>
