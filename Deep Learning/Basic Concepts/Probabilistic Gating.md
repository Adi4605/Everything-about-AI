- It is a mechanism where neuron, expert, connection, or computational path is activated based on a probability rather than a fixed deterministic rule.
- 'Probabilistic gating uses probabilities to decide whether a neuron, expert or pathway should be active or inactive.'
- Probabilistic gating often uses a [[Bernoulli Distribution]].

Types:
1. Bernoulli Gating: Each neuron path is based on a probability.
	Applications in [[Dropout]], Sparse Neural Network
2. Binary(Hard) Gating: A decision is made from either of the paths.
	Applications in [[Mixture of Experts]](MoE) and [[Sparse Transformers]]
3. Soft Gating: Instead of selecting one expert, assigns probabilities to all experts.
	Applications in Attention Mechanisms, MoE, Ensemble Models.
4. Top-K Gating: Top experts with highest probabilities are activated.
	Applications in Sparse MoE Models and [[Large Language Models]]
5. Sparse Gating: Goal is to activate only few experts from all.
	Applications in Modern LLMs and Sparse Transformers
6. Dense Gating: Opposite of Sparse Gating, All experts participate
	Applications in Traditional Ensemble Models, Early MoE systems
7. Sigmoid Gating: Uses the [[Sigmoid]] function to determine information flow
	Applications in LSTM, GRU and Highway Networks
8. Attention-Based Gating: Attention weights act like probabilities.
	Applications in [[Transformers]], Large Language Models and [[Vision Transformers]]
9. Stochastic Gating: Randomized gating during training.
	Application in Neural Architecture Search, Bayesian Neural Networks
10. Learned Gating: The gating probabilities themselves are learned.
	Applications in Mixture of Experts, Adaptive Neural Networks, Dynamic Routing Networks
11. Dynamic Gating: The gate changes depending on input.
	Applications in [[Multi-modal AI]] and Adaptive Networks
12. Hierarchical Gating: Gating occurs are multiple levels.
	Applications in Large Expert Names, Hierarchical MoE Models
13. Reinforcement Learning Gating: The gate learns decisions using rewards.
	Applications in RL Agents and [[Adaptive Routing]]