- Model forgets previously learned knowledge when it is trained on new data or a new task.
- During training:
	  New task
	     ↓
	Weight Update
		 ↓
Old knowledge Overwritten
- The parameters that represented old knowledge get modified.
- Occurs in :
	- Continual Learning: Learning tasks sequentially.
	- [[Fine-Tuning]]: A pre-trained model may lose general knowledge.
	- [[Reinforcement Learning]]: Learning new environments can overwrite old policies.
	- Robotics: Robots learning new skills may forget old ones.
Effects:
- Reduced accuracy
- Loss of knowledge
- Poor [[Continual Learning]]
- Instability

Solutions:
1. Rehearsal (Replay)
2. Experience Replay
3. Elastic Weight Consolidation (EWC): Important weights are protected
4. Progressive Networks
5. Knowledge Distillation
6. Parameter-Efficient Fine-Tuning (PEFT)
