- Gaussian Error Linear Unit
- Combines ideas from : [[ReLU]], [[Dropout]], [[Probabilistic Gating]]
- Instead of completely removing negative values, GELU softly scales them
- Smooth activation
- Better performance
- Better gradient flow 
- Preserves information
- Excellent for transformers
- Computationally expensive
- Slower than  ReLU
- Common in BERT and GPT models

GELU working:
- It weighs inputs probabilistically
- Important values pass more strongly
- Less important values are reduced smoothly

Formula:
f(x)=xΦ(x)
where:
x = input
Φ(x) = cumulative distribution function (CDF) of the standard normal distribution

![[Pasted image 20260520212834.png|425]]