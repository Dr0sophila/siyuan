---
title: "Deterministic World Models for Verification of Closed-loop Vision-based Systems"
collection: publications
category: manuscripts
permalink: /publication/Deterministic_World_Models_for_Verification_of_Closed-loop_Vision-based_Systems
excerpt: 'we propose a Deterministic World Model (DWM) that maps system states directly to generative images,effectively eliminating uninterpretable latent variables to ensure precise input bounds. '
date: 2025-12-08
# venue: 'Journal 1'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://dr0sophila.github.io/siyuan/files/Deterministic_World_Models_for_Verification_of_Closed-loop_Vision-based_Systems.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Verifying closed-loop vision-based control systems remains a fundamental challenge due to the high dimensionality of images and the difficulty of modeling visual environments. While generative models are increasingly used as camera surrogates in verification, their reliance on stochastic latent variables introduces unnecessary overapproximation error. To address this bottleneck, we propose a Deterministic World Model (DWM) that maps system states directly to generative images, effectively eliminating uninterpretable latent variables to ensure precise input bounds. The DWM is trained with a dual-objective loss function that combines pixel-level reconstruction accuracy with a control difference loss to maintain behavioral consistency with the real system. We integrate DWM into a verification pipeline utilizing Star-based reachability analysis (StarV) and employ conformal prediction to derive rigorous statistical bounds on the trajectory deviation between the world model and the actual vision-based system. Experiments on standard benchmarks show that our approach yields significantly tighter reachable sets and better verification performance than a latent-variable baseline.
