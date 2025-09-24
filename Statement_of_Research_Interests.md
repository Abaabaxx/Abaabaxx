## Research Interests: From Engineering Challenges to Academic Exploration

My hands-on experiences in robotics competitions have allowed me to build and fine-tune complete robot systems based on the classical **“Perception–Planning–Control”** framework. These valuable projects revealed the rigor and strengths of traditional methods, but more importantly, exposed their **fragility and complexity** when deployed in real-world scenarios. These challenges sparked my deep interest in the paradigm of **learning-based embodied intelligence**.

Some representative challenges I encountered include:

- **Fragility of Perception:** In the Intelligent Vehicle Competition, I developed a visual lane-following controller (V-FTW) whose performance heavily depended on precise inverse perspective mapping, sensitive threshold parameters, and extensive state-machine rules. Minor changes in lighting or lane color could break the entire perception pipeline. When I observed other teams addressing such challenges elegantly with **end-to-end learning approaches**, I was profoundly inspired.
- **Insufficient Understanding of Unstructured Environments:** While employing LiDAR-based clustering to detect targets, the system often failed when targets were adjacent to walls, merging them into a single cluster. This revealed the limitations of relying solely on geometric sensing, and convinced me that robots must build **rich 3D representations** of their environment to act robustly in unstructured spaces.
- **Limits of Understanding and Reasoning:** In the Innovation and Entrepreneurship Competition, I implemented an offline voice command system using the iFlytek SDK and BNF grammar rules. Although precise for template-based instructions, it failed to handle synonyms (e.g., “restroom” vs. “toilet”) or commonsense reasoning. This experience motivated me to explore how **large language models (LLMs)** could empower robots with genuine semantic understanding and flexible planning.
- **The Simulation-to-Reality Gap:** In the RAICOM ROS challenge, I faced firsthand the significant Sim-to-Real gap. Navigation parameters and control strategies that performed flawlessly in simulation often suffered from localization drift and collisions in real-world robots. This highlighted **Sim-to-Real **transfer as a fundamental bottleneck for deploying advanced algorithms, and a challenge I am eager to address in research.

These practical “pain points” guided me toward the field of **Learning-based Embodied AI**, and shaped my aspiration to evolve from a rules-driven **engineer** into a paradigm-shifting **researcher**. Specifically, I am interested in the following directions:

1. **How can robots learn robust perception and control strategies?**
   I aim to study **end-to-end imitation learning and reinforcement learning**, with particular attention to **Vision-Language-Action (VLA)** architectures. My goal is to enable robots to directly learn control policies from high-dimensional sensory input, replacing fragile hand-engineered pipelines.
2. **How can robots build profound understanding of the real world?**
   I am drawn to **neural scene representations** such as **NeRF and 3D Gaussian Splatting,** and aspire to explore how robots can use them to construct rich, continuous world models, achieving resilience beyond simple geometric heuristics.
3. **How can robots acquire commonsense and advanced reasoning?**
   I seek to investigate the integration of **world models** with **LLMs**, enabling robots not only to process human language but also to “see” and “understand” the 3D world they inhabit. This would allow for reliable task planning and natural handling of ambiguous or generalized human instructions.
4. **How can robots master complex and general motor skills?**
   Extending beyond wheeled platforms, I am eager to study **legged robots**, focusing on how to train policies in simulation that transfer to robust locomotion in challenging terrains. By tackling the **Sim-to-Real gap**, I hope to contribute to the deployment of general-purpose motor skills in embodied agents.

