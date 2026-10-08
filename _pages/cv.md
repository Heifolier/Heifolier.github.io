---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<p><a href="{{ site.baseurl }}/files/cv.pdf" class="btn btn--primary"><i class="fas fa-download" aria-hidden="true"></i> Download CV (PDF)</a></p>

## Education

<div class="timeline-list compact">
  <div class="timeline-item">
    <div><strong>Peking University</strong><br>M.Eng. in Mechanical Engineering (Robotics), School of Advanced Manufacturing and Robotics<br><span class="muted">Recommended admission · Advisors: Prof. Zhongkui Li and Prof. Meng Guo · Top 20%</span></div>
    <div class="timeline-date">Sep 2024 - Jun 2027 expected</div>
  </div>
  <div class="timeline-item">
    <div><strong>Northeastern University</strong><br>B.Eng. in Automation (Artificial Intelligence), College of Information Science and Engineering<br><span class="muted">Top 1%</span></div>
    <div class="timeline-date">Sep 2020 - Jun 2024</div>
  </div>
</div>

## Publications and Patents

1. **Shuo Zhang**, Zhongkui Li, Meng Guo, and Yanran Wei. “LLM-Guided Hierarchical Belief Planning for Online Semantic Exploration and Task Execution.” *2026 IEEE Chinese Automation Congress (CAC)*, published. **First author.**<br>
   Proposed an LLM-guided hierarchical belief-space planner for long-horizon tasks in partially observable semantic environments. Against the SOTA baseline, it reduced average execution time by 18.6% and travel distance by 16.9%. This work also produced one granted invention patent as first inventor.

2. “Formal Logic-based Cooperative Task Planning for Multi-robot Systems: Survey of Recent Advances and Future Directions.” *Acta Automatica Sinica*, published. **Student third author.**<br>
   Surveyed formal-logic and LLM-based approaches to multi-robot task modeling and planning, including translation from natural-language instructions to formal specifications, task decomposition, plan generation, and verifiability.

## Experience

<div class="timeline-list">
  <div class="timeline-item">
    <div><strong>Embodied Intelligence Algorithm Intern</strong><br>Xinyan Group Robotics Division, Beijing</div>
    <div class="timeline-date">Jun 2026 - Sep 2026</div>
    <p>Developed a multi-task VLA policy based on PI 0.5 for the 100 long-horizon household tasks in the BEHAVIOR 2026 Challenge. Added task embeddings, phase-progress encoding, gated tokens, correlated-noise flow matching, and conditional Gaussian soft inpainting; built teleoperation data collection and automated evaluation pipelines. Improved task success from 13% to 34% and Q-score from 0.26 to 0.49 on the official benchmark.</p>
  </div>
  <div class="timeline-item">
    <div><strong>Embodied Intelligence Algorithm Intern</strong><br>Shanghai MicroPort MedBot &amp; Peking University Joint R&amp;D Project</div>
    <div class="timeline-date">Dec 2025 - May 2026</div>
    <p>Built a respiratory-phase-conditioned P-VLA policy on GR00T for autonomous long-horizon robotic surgery. Developed a sensor-free respiratory-phase estimator and a multimodal training pipeline using demonstrations from 19 ex-vivo specimens and 3 live pigs; contributed to deployment and live-animal experiments on the Toumai multi-arm surgical robot. The work produced a Nature submission, <em>SharpSurg: Foundation-Model-Based Autonomous Long-Horizon Robotic Surgery in Vivo</em>, and two granted invention patents.</p>
  </div>
  <div class="timeline-item">
    <div><strong>Planning and Control Algorithm Engineer</strong><br>Beihang University Institute of Unmanned Systems &amp; Peking University Joint R&amp;D Project</div>
    <div class="timeline-date">Jun 2025 - Oct 2025</div>
    <p>Implemented and deployed a neuro-symbolic planning framework combining LLM reasoning, temporal logic, uncertainty-aware task allocation, and event-triggered human interaction. Experiments with 40+ heterogeneous robots across 41 tasks and 155 subtasks increased task success by 260% and completed tasks by 132%, while reducing operator intervention by 77%. The work led to submissions to <em>Science Robotics</em> and ACCT 2026.</p>
  </div>
</div>

## Projects

### Multi-agent minimum-time collaborative task planning with quasi-posets

**Core member, JWKJW project · Jan 2025 - May 2025.** Modeled long-horizon temporal and collaboration constraints with LTL and task automata, extracted executable subtasks and partial-order relations, and combined capability-aware allocation with branch-and-bound search to minimize makespan.

### Multi-target search and rescue in unknown environments

**Core member, HTCXY project · Sep 2024 - Dec 2024.** Built a ROS/LIMO autonomous exploration system using Gmapping, Frontier exploration, A* global planning, Move Base, and PID tracking; validated the full navigation stack in Gazebo and on a physical LIMO robot.

### Reinforcement-learning-based dynamic coalition formation and path planning

**Project lead, provincial innovation and entrepreneurship conference · Jan 2024 - Jun 2024.** Formulated task allocation, coalition formation, and path planning as sequential decision-making; developed an attention-based, leader-follower reinforcement-learning policy for dynamic team formation and decentralized execution.

### Reinforcement-learning-based online UAV trajectory optimization

**Project lead, Undergraduate Innovation and Entrepreneurship Training Program · Jun 2021 - Jun 2023.** Used PPO to optimize UAV trajectories in a hybrid FSO/RF network under motion, power, and QoS constraints; maintained communication rates within the acceptable range for 89.5% of the evaluated time.

### Hex game-playing agent

**National First Prize, 2022 China University Computer Game Competition · Jun 2022 - Jul 2022.** Built an 11×11 Hex agent using a policy-value network, PUCT Monte Carlo tree search, self-play, symmetry augmentation, experience replay, and MPI-based parallel training.

## Leadership and Service

- Served as undergraduate class monitor for three consecutive years and as captain of Northeastern University's roller-skating team.
- Served as deputy director of the Organization Department of the university volunteer association; completed 100+ hours of volunteer service and received a provincial third prize in the Red Challenge Cup social-practice program.
- Worked as a student-affairs assistant at Peking University.

## Skills

**Programming and development:** Python, C/C++, MATLAB, PyTorch, ROS, Isaac Sim, AI2-THOR, Git, Linux, Docker<br>
**LLM and AI tools:** LangGraph, Harness, Codex, Claude<br>
**Languages and research tools:** Chinese; English (CET-4: 569, CET-6: 472); LaTeX

## Honors

National Scholarship (top 1%); Outstanding Graduate of Liaoning Province (top 1%); Distinguished Scholar, the highest individual honor of the college; Outstanding Student Model of Northeastern University (top 2%); Peking University Zhang Mingwei Scholarship; Dai Qin Scholarship; National Inspirational Scholarship (twice); Northeastern University First-Class Scholarship (three times); Outstanding League Member Model; Outstanding League Cadre Model; Outstanding Volunteer.
