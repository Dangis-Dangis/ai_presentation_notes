# What is an LLM

Token
- Chunk of text defined by by tokenizer (short word, syllable/subword, punctuation)
- Unit of measure for input, processing, output
- Analogous to "lexical" step taken by compilers
- Mapped to vectors of floating point numbers

Large Language Model (LLM)
- Predicts probability distribution over next token
- Neural network based on transformer model
- Composed of layers with billions of floating point numbers (weights)

Pre-Training
- Imperfect language patterns: "how to sound normal"
- Not "interpreting how to respond to intended user intent"
- Uses input data to determine weights for language and structural patterns
- Crunches trillions of tokens
- Data quality and selection is critical

Post Training
- Optimizing to follow human instructions aligning with human preferences
- Don't answer "what was said", give me "what response was intended"
- Shapes accuracy, tone, and formatting in specific domains
- Includes: 
    - Reinforcement learning from human feedback (RLHF)
    - Safety constraints (e.g. output classifiers)

Inference
- Actual use of a model at runtime
- Text -> Token encoding -> Iterative Neural Network Loop -> Decoding -> Output text

Context Window
- Managed "working memory" through attentive sliding token buffer
- The effective "session state" including input + generated tokens
- Recent or "identified as practical tokens are more influential

# Why Now

Three stars aligned:
1. Cloud infrastructure deployed at scale
2. GPU technology improvements 
3. Breakthrough in neural networks - Transformers

