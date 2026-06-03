- An agent learns by interacting with an environment and receiving rewards or penalties for its actions.
- Does not requires labeled data.
- 'Reinforcement Learning is a machine learning paradigm in which an agent learns to make decisions by performing action in an environment and receiving rewards or penalties.'
- The goal is to maximize the total rewards over time.

Components:
1. Agent : A learner or decision-maker.
2. Environment : Everything the agent interacts with.
3. State (S) : Current situation of the environment.
4. Action (A) : What the agents can do.
5. Reward (R) : Feedback received after action.

![[Pasted image 20260603163153.png]]

Important aspects in Reinforcement Learning:
-  Policy: Tells the agent, what action should be taken in given state
	Types: 
		1. Deterministic Policy : One state -> One action
		2. Stochastic Policy : One state -> Multiple possible actions
-  Value function: Measures how good is a state
-  Action value function: Measures how good is taking action 'a' in state 's'. Notation -> Q(s,a)
-  Bellman Equation: Most important equation in RL.
	State Value:
	![[Pasted image 20260603164029.png]]
	Meaning: Current value = Immediate reward + Future value
	[[Discount Factor]] is an important term
- Exploration vs Exploitation: 
	Exploration: Try new things
	Exploitation: Use known best action
	Trade-off: Too much exploration -> slow learning
			Too much exploitation -> may miss better solutions
- [[Markov Decision Process]]: Most RL problems are modeled as an MDP

Types of Reinforcement Learning:
1. [[Model-Based Reinforcement Learning]]
2. [[Model-Free Reinforcement Learning]]
3. [[Positive Reinforcement Learning]]
4. [[Negative Reinforcement Learning]]

Algorithms: 
- [[Value-Based Algorithms]]
- [[Policy-Based Algorithms]]
- [[Actor-Critic Algorithms]]
- [[Deep Reinforcement Learning]]
- [[Model-Based Algorithms]]
- [[Multi-Armed Bandit Algorithms]]