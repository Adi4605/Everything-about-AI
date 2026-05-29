- Process of taking a pre-trained model and training on a further on a new, specific dataset to make it perform better on a particular task.
- Instead of training a model from scratch, we:
	- Start with a pre-trained model
	- Use our own dataset
	- Continue training it
- This saves: Time, Computing power, Data requirements
- Fine-Tuning modifies mainly the higher layers

Workflow:
Large Dataset
      ↓
Pre-Training
      ↓
Pre-Trained Model
      ↓
Task-Specific Dataset
      ↓
Fine-Tuning
      ↓
Specialized Model


Types:
1. Full Fine-Tuning: Trains all model parameters.
2. Partial Fine-Tuning: Freeze some layers and train only a few.
3. Feature Extraction: Use the pre-trained model only as a feature extractor. Trains only the final classifier.

Advantages:
- Less data required
- Faster training
- Lower cost 
- Better Accuracy
- Transfer learning

Disadvantages:
- Risk of overfitting
- [[Catastrophic Forgetting]]
- Large models still need resources
