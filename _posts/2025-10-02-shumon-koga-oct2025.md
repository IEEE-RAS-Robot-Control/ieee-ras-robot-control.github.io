---
title: "Shumon Koga advances active sensing control to enhance robot’s perception capability"
categories:
  - Spotlights
# tags:
  # - 
---

![researcher_spotlight_oct2025.jpg](/assets/images/researcher_spotlight/2025-10/Shumon_pic1.jpg){: .align-center style="width: 60%;"}

He tackles the challenge of visibility-constrained active sensing while ensuring safety, by leveraging both model-based control theory and data-driven learning.

## What is your role and what does it involve?
I am an Associate Professor in the Department of Computer Science and Systems Engineering at Kobe University. 
I direct the CINAPS lab, an acronym for 'Control and INtelligent Autonomy for Physical Systems.'
Broadly, our lab focuses on creating novel intelligent methods that bridge sensing and action, much like a synapse in a neuron. 
I am currently supervising three undergraduate students at CINAPS. 
For our lab's internal study, I lead a project-based group focused on Simultaneous Localization and Mapping (SLAM) using the foundational textbook 'Probabilistic Robotics'. 
In my teaching role for the department, I am instructing an undergraduate course on 'Signals and Systems' this fall, covering everything from the wave equation to the fundamentals of Fourier analysis. 
Beyond the university, I am also dedicated to growing the robot control community. 
I have co-organized [ICRA workshop on robot safety](https://iscicra25.github.io/){:target="_blank"} in 2025 and 2021, which brought together leading speakers and poster presenters to showcase the state-of-the-art and new frontiers in safe control.

## What do you find most interesting or enjoyable about your work?
Since becoming a faculty member from this year, I find it incredibly rewarding to see students become excited and self-motivated in their robotics research. 
For example, one student at CINAPS, driven by a strong interest in autonomous driving, has rapidly established a new driving simulator in our lab. He consistently shows me his original implementations based on research papers and has even taken the initiative to enter a new vision-language-action competition held at IROS 2025. 
Another student is more passionate about fundamental academic research. He has conducted a deep survey of diffusion models for robotics, is implementing novel methodologies, and is working towards a conference submission. 
Supervising those self-motivated students is what I find most enjoyable. 

## Tell us about your research (include an explicitly stated long-term goal)
My primary research interest is robot active sensing with safety, where a robot with onboard sensors must intelligently move to collect information about its environment. 
This applies to objectives like SLAM, pursuit-evasion, and object recognition in domains such as search-and-rescue and environmental monitoring. 
While this is a classic problem, fundamental challenges remain, particularly in providing formal guarantees for uncertainty reduction and safety, especially under unstructured and cluttered environments. 

My work specifically tackles active sensing under field-of-view constraints with occlusion from obstacles. 
My approach has been to represent the robot's visibility using Signed Distance Functions (SDFs), named as visibility barrier. 
With the visibility barrier function, I have developed techniques involving iterative optimization on the Lie group of the robot's pose, a model-based reinforcement learning with attention-based network architectures, and a set-invariance-based control methods to maintain visibility with ensuring safety. 
Most recently, I've been working to make active sensing more versatile and explainable, specifically by applying diffusion models trained on diverse trajectory datasets and developing vision-language-guided policies for semantic map construction.

My long-term goal is to establish ubiquitous methods that allow robots to be utilized safely and effectively anytime, anywhere, and for anyone. 
I'm inspired by the progress of autonomous driving and am excited for the near-future impact of humanoid and surgical robots. 
I also envision my work enabling new applications for earth and climate, such as robots that monitor wildfire risks or make new discoveries undersea and in space.

## What led you to pursue a research career in this field?
In short, it's the multimodality of challenges in robotics that has always fascinated me. 
Robotics demands expertise across theory, practical implementation, and societal application, and I find that intersection incredibly stimulating. 
My career path has reflected this multimodal interest. 
During my PhD at UC San Diego (UCSD), I was deeply focused on control theory for Partial Differential Equations (PDEs), where my passion was developing new theorems with rigorous proofs through advanced control designs. 
I was honored to receive the [O. Hugo Schuck Best Paper Award at American Control Conference in 2019](https://a2c2.org/paper-award/o-hugo-schuck-best-paper-award#recipients-2019){:target="_blank"}, which initiated my interest in research career. 
I then transitioned into robotics as a postdoc in a different lab at UCSD, which gave me new perspectives on problem definition and method evaluation, from high-fidelity simulators to hardware. 
After that, I joined Honda as an engineer, where I led a software development team for autonomous driving. 
In this March, I returned to academia to start my faculty position at Kobe University. 
I believe that in robotics research, all of these past experiences—from abstract theory to industry software development—are invaluable in developing a unique, formal, and practical methods with a team. 
The robotics field constantly requires me to draw on that diverse background, which is why I find it so compelling.

## What working achievement and/or initiative are you most proud of?
I am truly proud of achieving the position of Associate Professor at Kobe University, a top-notch institution in Japan with a world-leading research environment. 
Earning this tenured role and directing my own lab, particularly without first serving as an assistant professor, was a significant personal achievement. 
This achievement was only possible thanks to the many people who have supported me, especially my PhD advisor, Professor Miroslav Krstic, and my postdoc advisor, Professor Nikolay Atanasov. 
Now, it's my turn to educate and mentor my students to help them build the successful careers they aspire to, and that's the next great challenge I'm passionate about.  

## What's next on the research horizon for you?
I envision expanding my research on active sensing by integrating it with foundation models—specifically vision-language schemes and diffusion models—which is a rapidly advancing direction in robotics. 
In particular, I am interested in how mathematical or optimization-based approaches in active sensing can be aligned with natural language to enhance explainability for users. 
Active sensing often involves the classic exploration-exploitation dilemma—for example, whether to prioritize maintaining visibility of a moving target or exploring a new region. 
This problem often lacks a single deterministic solution under diverse environments. 
Showing language-based reasoning in the decision-making stage is a very intriguing and promising direction. 
I've recently started focusing on new methods for active sensing with language and multimodal solutions. 
Once a method is developed, the next challenges will be data collection for real-world testing and, ultimately, hardware demonstration in the field.

## Can you share some interesting work that you read about recently?
Though there are many, one that stands out is 'Diffusion Policy: Visuomotor Policy Learning via Action Diffusion' by Chi et al., published in IJRR in 2024. 
This was the first paper to apply diffusion models to policy learning for robot control, and it cleverly incorporated ideas from receding horizon control. 
The performance evaluation is very intensive, and what particularly caught my interest was the connection it draws to the Linear Quadratic Regulator, which speaks directly to my background in control theory. 

## How do you balance research with the other demands of your position?
Haha, there’s definitely no deterministic policy for it! 
A stochastic policy trained over my experience might exist, but the loss function is certainly unknown. 
In practice, when my schedule is packed with multiple duties, I just do my best!

## Shumon Koga's Links
- [Personal website](https://shumon0423.github.io/){:target="_blank"}
- [Lab website](https://cinapslab.com/){:target="_blank"}
- [LinkedIn](https://www.linkedin.com/in/shumon-koga-742b6565){:target="_blank"}
- [Google Scholar](https://scholar.google.com/citations?user=5UMyBR8AAAAJ&hl=ja&oi=ao){:target="_blank"}
