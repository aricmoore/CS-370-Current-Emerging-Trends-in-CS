# CS 370: Current and Emerging Trends in Computer Science

Arielle Moore
<br>
Bachelor of Science in Computer Science
<br>
Southern New Hampshire University

## Course Description

Students will explore advanced topics in Computer Science through analysis of authentic scenarios. Students will analyze the role of ethics in current trends within the field as well as apply fundamental concepts of the field to solve complex problems in new ways. Course Competencies

This course covers the following competencies, which represent the knowledge and skills relevant to your field:
- CS-30424: Explain the basic concepts and techniques that pertain to artificial intelligence and intelligent systems
- CS-30425: Analyze how algorithms are used in artificial intelligence to solve a variety of complex problems
- CS-30426: Analyze current trends and emerging technologies in Computer Science for their impacts on society 

## Featured Project: Pirate Intelligent Agent

In this project, I implemented a reinforcement learning agent that learns to navigate a maze environment to reach a treasure while avoiding penalties. The goal was to apply key concepts from reinforcement learning and neural networks to train an intelligent agent capable of autonomous decision-making.

I was provided with the environment code (`TreasureMaze.py`) and the experience replay framework (`GameExperience.py`). These files defined the maze structure, reward system, valid actions, and memory handling for training. I was responsible for implementing the deep Q-learning training loop in the Jupyter Notebook, including:
- The ε-greedy action selection strategy
- Experience storage and replay integration
- Target network synchronization
- Q-value updates using the Bellman equation
- Hyperparameter tuning (epochs, memory size, batch size, exploration decay)

I also configured and trained the neural network model that maps maze states to Q-values for each possible action. Through iterative training, the agent achieved a consistent win rate, demonstrating convergence toward an optimal policy.

[Visit the project here →](https://github.com/aricmoore/CS-370-Current-Emerging-Trends-in-CS/tree/main/Jupyter/pirate-intelligent-agent)

### Connecting This Project to Computer Science
<i>What Do Computer Scientists Do and Why Does It Matter?</i>

Computer scientists design systems that solve complex problems through structured logic, algorithms, and data-driven decision-making. This project demonstrates that role clearly: instead of manually coding the path to the treasure, I built a system that learns the solution through interaction and feedback.

This matters because many real-world problems, such as robotics, autonomous vehicles, logistics optimization, and recommendation systems, cannot be solved effectively with hard-coded rules alone. Reinforcement learning enables adaptive, scalable, and data-driven solutions that improve over time.

### How I Approach a Problem as a Computer Scientist

This project reinforced that approaching a problem as a computer scientist involves:
- Understanding the system constraints (state space, actions, rewards).
- Breaking the problem into components (environment, agent, training loop).
- Selecting an appropriate algorithmic approach (deep Q-learning).
- Iteratively testing and refining until performance stabilizes.

Rather than immediately focusing on implementation, I first analyzed how the agent interacts with the environment and how reward shaping influences learning. I then implemented the training loop carefully, ensuring that experience replay and target networks were correctly integrated to stabilize learning. Debugging involved monitoring win rate trends and loss values to confirm convergence.

This structured, iterative, and evidence-based approach reflects how computer scientists solve complex problems across domains.

### Ethical Responsibilities to End Users and Organizations

This project also highlights important ethical responsibilities. When building intelligent systems, developers must ensure:
- Reliability: The system should perform consistently and not produce unstable or unpredictable results.
- Transparency: Stakeholders should understand how decisions are made, especially in AI-driven systems.
- Fairness and Safety: Reward structures and training data must not produce harmful or biased behavior.
- Maintainability: Code should be clear, documented, and reproducible to support long-term organizational use.

Although this project uses a simulated maze, the same principles apply to real-world AI systems. Reinforcement learning agents used in finance, healthcare, or transportation must be carefully designed to prevent unintended consequences.

As a developer, I am responsible not only for building functional systems but also for ensuring that they operate ethically, responsibly, and in alignment with organizational goals.

### Final Reflection

This project strengthened my understanding of reinforcement learning, neural networks, and algorithmic problem-solving. More importantly, it demonstrated how theoretical computer science concepts translate into practical systems that learn from experience. Implementing deep Q-learning from scratch clarified how exploration, exploitation, reward shaping, and experience replay work together to produce intelligent behavior.

This experience reinforces my ability to design adaptive systems and apply machine learning principles to real-world challenges.

## Featured Project: The Cartpole Problem

[Visit the project here →](https://github.com/aricmoore/CS-370-Current-Emerging-Trends-in-CS/blob/main/Jupyter/Moore_Arielle_Assignment5.ipynb)

## Featured Project: Cartpole Revisited

[Visit the project here →](https://github.com/aricmoore/CS-370-Current-Emerging-Trends-in-CS/blob/main/Jupyter/Moore_Arielle_Assignment6.ipynb)

## Academic Written Assignments

[Visit the assignments here →](https://github.com/aricmoore/CS-370-Current-Emerging-Trends-in-CS/tree/main/Written%20Assignments)

- ---

<sub>© 2026 Arielle Moore. All rights reserved. | CS 370: Current and Emerging Trends in Computer Science | View my [portfolio](https://aricmoore.github.io/) for more projects.</sub>
