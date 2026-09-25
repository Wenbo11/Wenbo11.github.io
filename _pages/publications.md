---
layout: default
title: Publications
permalink: /publications/
---

<h1 class="page-title">Publications</h1>

<p style="margin-bottom: 2rem; color: var(--color-text-light);">
  See also: <a href="{{ site.author.google_scholar }}">Google Scholar</a>
</p>

<div class="pub-section">
<h3>LLM &amp; Agent Evaluation</h3>
<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks</div>
  <div class="pub-authors">X. Li*, Y. Liu*, <span class="me">W. Chen*</span>, B. You*, Z. Di, Y. He, S. Zheng, K.W. Choe, J. Sun, et al. <span class="pub-note">(*co-first authors)</span></div>
  <div class="pub-venue">NeurIPS 2026</div>
  <p class="pub-tldr">87 expert tasks with deterministic verifiers and paired with/without-skill runs: curated skills lift agent pass rates by +16.6 pp, and focused skills beat exhaustive ones.</p>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2602.12670">Paper</a>
    <a href="https://www.skillsbench.ai">Website</a>
    <a href="https://github.com/benchflow-ai/skillsbench">Code</a>
  </div>
  <div class="pub-award">Adopted by Meta Muse Glimmer, Qwen, HY3</div>
</li>

<li class="pub-item">
  <div class="pub-title">ClawsBench: Evaluating Capability and Safety of LLM Productivity Agents in Simulated Workspaces</div>
  <div class="pub-authors">X. Li, K.W. Choe, Y. Liu, X. Chen, C. Tao, B. You, <span class="me">W. Chen</span>, Z. Di, J. Sun, et al.</div>
  <div class="pub-venue">COLM 2026</div>
  <p class="pub-tldr">Stateful mock Gmail, Slack, Calendar, Docs, and Drive: top agents succeed on 39-64% of tasks yet take unsafe actions 7-33% of the time.</p>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2604.05172">Paper</a>
    <a href="https://clawsbench.benchflow.ai/">Website</a>
    <a href="https://github.com/benchflow-ai/ClawsBench">Code</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">BenchShield: Formal Model-Backed Instrumentation for Reward Integrity in LLM-Agent Evaluation Infrastructure</div>
  <div class="pub-authors">S. Zheng, Z. Di, Y. Liu, K.W. Choe, J. Sun, H. Lin, P. Jiang, Y. He, X. Cheng, J. Wang, <span class="me">W. Chen</span>, A. Yates, et al.</div>
  <div class="pub-venue">Preprint, 2026</div>
  <p class="pub-tldr">Reward-integrity layer for agent benchmarks: static taint analysis finds hacking paths before a run, and runtime evidence detects hacking at 96% accuracy across 31k+ runs on SkillsBench, ClawsBench, and Terminal-Bench 3.</p>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2609.11028">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Rethinking Evaluation for LLM Hallucination Detection: A Desiderata, A New RAG-based Benchmark, New Insights</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, V. Padmanabhan, T. Giyahchi, E. Wong, L. Akoglu</div>
  <div class="pub-venue">ACL 2026 (Main Conference)</div>
  <p class="pub-tldr">A desiderata for hallucination benchmarks and TRIVIA+, a long-context RAG benchmark with realistic label noise; LLM-as-a-Judge stays competitive.</p>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2605.11330">Paper</a>
    <a href="https://github.com/amazon-science/hallucination-benchmark-trivialplus">Code &amp; Data</a>
  </div>
</li>

</ul>
</div>

<div class="pub-section">
<h3>RL &amp; LLM Reasoning</h3>
<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">MARS: Margin-Adversarial Risk-controlled Stopping for Parallel LLM Test-time Scaling</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, P. Li, M. Liu, W. Su, T. Xie</div>
  <div class="pub-venue">Preprint, 2026</div>
  <p class="pub-tldr">Stop parallel reasoning early once the majority vote is provably safe: 25-47% fewer self-consistency tokens at full-budget accuracy.</p>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2606.12935">Paper</a>
    <a href="https://github.com/Wenbo11/MARS">Code</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Latent Spherical Flow Policy for Reinforcement Learning with Combinatorial Actions</div>
  <div class="pub-authors">L. Kong, A. Satish, H. Jiang, A. Kangaslahti, A. Ma, <span class="me">W. Chen</span>, M. Song, L. Xu, et al.</div>
  <div class="pub-venue">ICML 2026 (Spotlight)</div>
  <p class="pub-tldr">A stochastic flow-matching policy in latent space, with a solver guaranteeing feasible actions: +20.6% over state-of-the-art combinatorial RL.</p>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2601.22211">Paper</a>
  </div>
  <div class="pub-award">Spotlight</div>
</li>

<li class="pub-item">
  <div class="pub-title">Reinforcement Learning from Optimization Proxy for Ride-Hailing Vehicle Relocation</div>
  <div class="pub-authors">E. Yuan, <span class="me">W. Chen</span>, P. Van Hentenryck</div>
  <div class="pub-venue">Journal of Artificial Intelligence Research, 2022 / IJCAI 2023 (Journal Track)</div>
  <div class="pub-links">
    <a href="https://www.jair.org/index.php/jair/article/view/13794">Paper</a>
    <a href="https://www.ijcai.org/proceedings/2023/796">IJCAI</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Improving Learning to Branch via Reinforcement Learning</div>
  <div class="pub-authors">H. Sun, <span class="me">W. Chen</span>, H. Li, L. Song</div>
  <div class="pub-venue">NeurIPS 2020 Workshop (Learning Meets Combinatorial Algorithms)</div>
  <div class="pub-links">
    <a href="https://openreview.net/pdf?id=M_KwRsbhi5e">Paper</a>
  </div>
</li>

</ul>
</div>

<div class="pub-section">
<h3>Data-Driven Decision Making &amp; Earlier Work</h3>
<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">Boosting Column Generation with Graph Neural Networks for Joint Rider Trip Planning and Crew Shift Scheduling</div>
  <div class="pub-authors">J. Lu, T. Ye, <span class="me">W. Chen</span>, P. Van Hentenryck</div>
  <div class="pub-venue">Transportation Research Part E, 2025</div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2401.03692">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Outbound Load Planning in Parcel Delivery Service Networks Using Machine Learning and Optimization</div>
  <div class="pub-authors">R. Ojha, <span class="me">W. Chen</span>, H. Zhang, R. Khir, A. Erera, P. Van Hentenryck</div>
  <div class="pub-venue">Transportation Science, 2025</div>
  <div class="pub-links">
    <a href="https://pubsonline.informs.org/doi/abs/10.1287/trsc.2024.0672">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Compact Optimality Verification for Optimization Proxies</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, H. Zhao, M. Tanneau, P. Van Hentenryck</div>
  <div class="pub-venue">ICML 2024</div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2405.21023">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Real-Time Risk Analysis with Optimization Proxies</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, M. Tanneau, P. Van Hentenryck</div>
  <div class="pub-venue">PSCC 2024 / Electric Power Systems Research, 2024</div>
  <div class="pub-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S0378779624007089">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">End-to-End Feasible Optimization Proxies for Large-Scale Economic Dispatch</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, M. Tanneau, P. Van Hentenryck</div>
  <div class="pub-venue">IEEE Transactions on Power Systems, 2023</div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2304.11726">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Compact Optimization Learning for AC Optimal Power Flow</div>
  <div class="pub-authors">S. Park, <span class="me">W. Chen</span>, T.W.K. Mak, P. Van Hentenryck</div>
  <div class="pub-venue">IEEE Transactions on Power Systems, 2023</div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2301.08840">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Confidence-Aware Graph Neural Networks for Learning Reliability Assessment Commitments</div>
  <div class="pub-authors">S. Park, <span class="me">W. Chen</span>, D. Han, M. Tanneau, P. Van Hentenryck</div>
  <div class="pub-venue">IEEE Transactions on Power Systems, 2023</div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2211.15755">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Two-Stage Learning for the Flexible Job Shop Scheduling Problem</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, R. Khir, P. Van Hentenryck</div>
  <div class="pub-venue">Preprint, 2023</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2301.09703">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Learning Optimization Proxies for Large-Scale Security-Constrained Economic Dispatch</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, S. Park, M. Tanneau, P. Van Hentenryck</div>
  <div class="pub-venue">PSCC 2022 / Electric Power Systems Research, 2022</div>
  <div class="pub-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S0378779622006629">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Privacy-Preserving Online Task Allocation in Edge-Computing-Enabled Massive Crowdsensing</div>
  <div class="pub-authors">P. Zhou, <span class="me">W. Chen</span>, S. Ji, H. Jiang, L. Yu, D. Wu</div>
  <div class="pub-venue">IEEE Internet of Things Journal, 2019</div>
  <div class="pub-links">
    <a href="https://ieeexplore.ieee.org/ielaam/6488907/8863548/8662620-aam.pdf">Paper</a>
  </div>
</li>

<li class="pub-item">
  <div class="pub-title">Privacy-Preserving Online Learning Approach for Incentive-based Demand Response in Smart Grid</div>
  <div class="pub-authors"><span class="me">W. Chen</span>, A. Zhou, P. Zhou, L. Gao, S. Ji, D. Wu</div>
  <div class="pub-venue">IEEE Systems Journal, 2019</div>
  <div class="pub-links">
    <a href="https://ieeexplore.ieee.org/abstract/document/8642292/">Paper</a>
  </div>
</li>

</ul>
</div>
