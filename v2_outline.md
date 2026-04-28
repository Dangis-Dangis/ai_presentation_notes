# Presentation Goals
[Jump to draft section](iterative_full_draft.md#iteration-1---presentation-goals)

- Calibrate expectations.
- It is happening; two options:
  - Wait for better models.
  - Learn now.
- Defeat polarization through learning.
- Not about AGI, singularity, or politics.

Why not listen to me?
- I am only one person
- I am not an expert in ML
- I have a long history of being fooled
- AI is a rapidly evolving frontier

Why listen to me?
- I am skeptical, curious, and disagreeable
- I am a huge enthusiast with:
  - little personal responsibilities (avg 40 hrs of YouTube/week)
  - heavy attraction to opposing viewpoints
  - strong aversion to unfounded doomerism/utopian thinking

# What is an LLM

Token
- Chunk of text defined by tokenizer (short word, syllable/subword, punctuation)
- Unit of measure for input, processing, output
- Analogous to "lexical" step taken by compilers
- Mapped to vectors of floating point numbers

Large Language Model (LLM)
- Predicts probability distribution over next token
- Neural network based on transformer model
- Composed of layers with billions of floating point numbers (weights)
- Nondeterministic behavior

Pre-Training
- Imperfect language word/structure patterns: "how to sound normal"
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
- Text -> Token encoding -> Iterative Neural Network Loop -> Sampling/Decoding -> Output text

Context Window
- Managed "working memory" through attentive sliding token buffer
- The effective "session state" including input + generated tokens
- Recent or "identified as practical tokens are more influential"

# Why Now?

Three stars aligned
1. Cloud infrastructure deployed at scale
2. GPU/TPU hardware improvements
3. Breakthrough in neural networks - Transformer architecture

# Who?

Primary US players
- Claude - Opus, Sonnet, Haiku (Mythos?)
- OpenAI - ChatGPT
- Google - Gemini
- xAI - Grok
- Meta - Llama

China
- DeepSeek - DeepSeek v3.2/v4 (MIT license)

France
- Mistral - Mistral mMedium 3 (Apache 2.0 license)

# What about it?

Predictions are often wrong in time or rate of adoption. 
- Predicted harms end up harmless or different harms nobody predicted. 
- Predicted benefits fall flat but it fits a perfect and unexpected use case.

The "Obvious Place This Is Going" throughout history:
- Every decade since the 60s: Flying cars are coming in ____ years! (Always 20-30 years out, increasing skepticism)
- Y2K
- Early 2000s, nobody will go to the retail store! Up from 0.7% in 1999 to 16.7% in 2026  (ref pew research img^, up from 0.7% in 1999 to 16.7% in 2026)
- Video games will make people violent!
- You won't always have a calculator!

What makes you so confident in your predictions, exactly?

# Perspective Bias
[Jump to draft section](iterative_full_draft.md#iteration-2---perspective-bias)

Predictions are often wrong:
- Loudest voices are rarely the best informed. 
- Media selects for shock, anger, hyperbole.
- Those voices are not representative.
- Avoid headline-chasing.
- Telephone effect across layers: Engineer <-> Manager <-> Marketing.
- Listen to technical experts who use more precision.

AI Evangelist
- May be motivated by self interest. 
- Might be making predictions that are correct in result, but wrong in timeline or pricing or scale. 
- May be a charlatan (NFT hype). 
- May speak on results with very different assumptions on workflow (building purposed agents, improved prompting techniques, more well matched expectations) - often not well communicated. 
- The Useless viral content washes out boring but important developments. 
- The future is now.

Decel (chad meme framing).
- Is drawing on past hype cycles, knows better. 
- Has made well placed criticisms based on own experience. 
- 'it failed so it must be the tool' (not me!). 
- I know this, it doesn't, so I'm better and I don't need it. 
- AI syncophancy is evidence it doesn't know things. 
- The loud AI pushers (all I'm hearing) are lying so it must all be wrong. 
- Generally incurious about best practices, dismissive. Unwilling to understand the shortcomings/limitations to calibrate use. 
- Is threatened and wants to protect their craft - fears replacement often subconsciously.
- Strongly favors deterministic systems. Must see to believe, may set arbitrary limits on capability and ignore trends. w
- The past is now.

What drives bias?
- Evaluating consequences and contextualization of a problem is highly subjective
- Level of interest and availability strongly determine the size of exposure. Time makes familiarity and informs expectations. Direct use improves skill in using a tool more appropriately and effectively. These all influence the observed success or failures. (or brainwashing)
- Trends in immediate environment vary. What are the people and situations most frequently interacted with?
- Informational asymmetry in exposure to diverse viewpoints: rate of quality or volume in each direction.
- Differences in respect or deference to perceived TRUE authority, while informed experts may reasonably disagree or change positions over time
- Risk analysis and predictions are difficult. 
- They requires a lot of time, effort, and critical thinking to deeply understand. Even if the statistics are agreed upon, the integrity of source data is questioned. Who collected what data and how was it selected? Was it measured sufficiently for a strong evaluation? What exactly is the proportional impact of all of these interconnected causal or correlated factors?
- "This shouldn't exist" or "It shouldn't be used this way" can be strongly motivated by opinions of the actors who control it and the power of their grip.
- The optimal solution is rarely an early iteration.


- "Boy who cried wolf" effect entrenches positions.
- Speaker incentives
- Reference: "Stop Using Human Language."
- Dancing bear effect.

# Limitations
[Jump to draft section](iterative_full_draft.md#iteration-4---limitations)

- Non-deterministic behavior.
- Weak at math and logic.
- Hallucination causes:
  - Limited context window.
  - Insufficient confidence assessment.
- Sycophancy:
  - "World traveler" problem.
  - Cost of being wrong and confident.
- Domain knowledge is irreplaceable for evaluation.
- Benchmarks:
  - Inexact.
  - Hackable.
  - Still directionally useful across sets.
- Volume of training data affects what appears in models.

# How to Use More Effectively
[Jump to draft section](iterative_full_draft.md#iteration-5---how-to-use-more-effectively)

- Three kinds of mindsets.
- Vibe coding vs augmented learning.
- Vibe coding without looking at code (own it).
  - Do not stop when it works; stop when you understand.
  - Ask for steps and reasoning.
    - Better for your learning.
    - Often better outputs (less than before).
  - Assume junior engineer capability; do not blindly trust.
  - It can feel addictive; writing by hand may feel painful, but preserves capability.
- Iterate on the plan before taking action.
- If workflow goes wrong:
  - Ask how the prompt could have been better.
  - Get mad or learn; your choice.

# Prompt Engineering
[Jump to draft section](iterative_full_draft.md#iteration-6---prompt-engineering)

- Use fewer tokens for higher information density.
- Avoid "dead zone" prompt drift:
  - Plan A derails.
  - Midstream mind changes pollute context.
- Write prompts like high-quality Jira tickets:
  - No assumptions.
  - Unambiguous and specific.
  - Include examples.
- Tone options:
  - Spartan.
  - Caveman.
  - Researcher.
  - Industry terms.
  - Medium polite.
  - Third person.
- Find the Goldilocks zone:
  - Brief and direct.
  - Add relevant constraints and examples.
- Give an out when unknown:
  - Ask for sources.
  - Ask for confidence level.
- Avoid leading tone; request balanced comparison.
- Avoid contradiction-heavy summaries:
  - Wastes tokens.
  - Adds little value.
- Prompt ordering:
  - Put the question first.
- Use paid models where appropriate:
  - Value your time.
  - Do not bazooka a fly.
- Try modalities:
  - Add picture or song to enrich narrative.

# Risks
[Jump to draft section](iterative_full_draft.md#iteration-7---risks)

- Cybersecurity:
  - Faster zero-day discovery.
  - Faster cat-and-mouse cycle.
- Bug bounty and application spam overload.
- Inappropriate use cases:
  - Psychology (human isolation risk).
  - Defense, finance, and manufacturing (cannot fail).
  - Fabricated legal cases.
  - PII exposure.
- Jailbreaking:
  - Universal vs targeted.
  - Constitutional classifiers add compute cost.
- May reflect gender/race bias from training data.
- Reviews can over-prioritize specific concerns; stay aware.

# Long-Term Impacts
[Jump to draft section](iterative_full_draft.md#iteration-8---long-term-impacts)

- Software cost plummets.
  - Graph themes: "more code," "cost per SLOC down," "quality per line down," "KPIs up."
- In less critical applications:
  - Already some slop but "good enough" (daily SQL automation, low-traffic sites).
  - More empowered refactors; stretch goals feel closer.
- Writing code by hand becomes like guitar:
  - Skill remains.
  - More hobby/craft energy.
- More time in high-level thinking than syntax.
- Accelerated learning/training:
  - Less negative learning.
  - Data is more accessible with context.
- Critical industries adopt more slowly.
- CEO lock-in risk.
- Lower moat effects:
  - Bring domain knowledge closer to implementation.
  - Break silos.
  - Encourage curiosity.
  - Experience can become a disability; conventional wisdom can become a barrier.
- Eventual ceiling:
  - Data limits (Stack Overflow, legal, ethical).
  - Hardware limits.
  - Algorithmic blockers.
- Strong use cases:
  - Improved medical imaging.
  - Doctors spend more time with people than data entry.
