--
title: "Common Ground Modling with a Computational Cognitive Model"
excerpt: "We use a computational cognitive architecture to develop models of both the AI and human performers, in a common modeling framework, in a reinforcement learning context. We use a cognitive salience algorithm to introspect upon both model to get a comparable descriptoin of the mental model."
tags: # Select from this set
  - Autonomy
  - Reinforcement Learning
  - Saliency

   
submission_details:
  resources: # List any resources associated with the contribution. Not all sections are required
    papers:
      - https://baicsworkshop.github.io/pdf/BAICS_36.pdf
      - https://iccm-conference.neocities.org/2019/proceedings/papers/ICCM2019_paper_53.pdf
      - https://iccm-conference.neocities.org/2020/papers/Contribution_255_final.pdf
    software:
      - https://halle.psy.cmu.edu/pyactup/
    demos:
      - https://colab.research.google.com/drive/1tf5gYVab3GSpPsTUxp34PVxNCIbA19FC?usp=sharing

   
  
  authors:
    - Sterling Somers, Constantinos Mitsopolous, Christian Lebiere
  organizations:
    - Carnegie Mellon University (Psychology)
  point_of_contact:
    name: Sterling Somers
    email: sterling@sterlingsomers.com
---
   
## Overview
The methodology is provide insight into the mental model of human performers, particularly in tasks where cognitive properties affect player performance. 
   
## Intended Use
In an RL context, this approach is particularly useful when human participants are involved in the task. It can be used any time during their learning trajectory (one of the strengths) and would be particularly useful in a human-machine teaming context. 

This work has been applied to RL in simple game settings (StarCraft II simple mission, gridworld strategy game). 
   
## Model/Data
The model uses symbolic states/value pairs and outputs actions (or distributions over actions). 

The model uses behavioral data (state,action) from agents (human or AI). 
   
## Limitations
In feature-rich scenarios, a suitable feature ontology is required. Creating a suitable ontology could require significant investment.
   
