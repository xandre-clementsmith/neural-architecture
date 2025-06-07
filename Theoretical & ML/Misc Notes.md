Risks from Learned Optimization in Advanced Machine Learning Systems
https://arxiv.org/abs/1906.01820
https://www.alignmentforum.org/posts/FkgsxrGf3QxhfLWHG/risks-from-learned-optimization-introduction

The ground of optimization
https://www.alignmentforum.org/posts/znfkdCoHMANwqc2WE/the-ground-of-optimization-1
https://www.alignmentforum.org/posts/mL8KdftNGBScmBcBg/optimization-concepts-in-the-game-of-life

NIST Autonomy Framework & RMF & Systems Assurance
https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=822679
https://www.nist.gov/itl/ai-risk-management-framework 
https://www.nist.gov/programs-projects/autonomous-systems-assurance 

Components
- State complexity
- Observation complexity
- Information encoding
- Evaluative component
- Planning space
- Actuator enablement

### Cell Types
- https://www.nature.com/articles/nrn.2017.85
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8195859/ 
- Granular neurons running pattern separation and pattern convergence (https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006932)
	- granular layer of the cerebellum, the dentate gyrus of the hippocampus, the superficial layer of the dorsal cochlear nucleus, the olfactory bulb, and the cerebral cortex



##### Part 1
- Optimizer / Base Objective (Base Objective): A system that internally searches through a search space (consisting of possible outputs, policies, plans, strategies, etc.) looking for elements that score high according to some objective function
- Meta-Optimization: Any system whose task is optimization; produces a base optimizer that is itself good at optimizing systems to achieve particular goals
- Mesa-Optimization (Mesa-Objective): Learned optimization that occurs when a learned model (e.g., neural network) is itself an optimizer
	- AI systems are optimized for something / have a purpose
	- Some AI systems optimize for something / pursue a goal
- Behavioral Objective: Object that appears to be optimized by behavior (Teleological Objective)
- Outer alignment is the reward gap between human and base objectives; inner alignment is the reward gap between base and mesa objectives
--- NOTES ---
- Is a thermometer an optimizer?
- How does an RL algorithm's mesa-objective compare to biological objectives? Consider reflexes. 

Learn the following authors:
- https://bams1.org/
- https://www.nature.com/articles/s41593-019-0520-2 

Deep Learning Framework: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7115933/
Geometric Constraints: [https://www.nature.com/articles/s41586-023-06098-1](https://www.nature.com/articles/s41586-023-06098-1 