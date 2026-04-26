----------------------------------

https://x.com/i/status/2045101393015345212

The people starting AI companies had thought experiments in their head before they started

----------------------------------

https://youtu.be/Sp1EmFRDquA

Reasonable conclusions:
Compared to other technology innovations, LLMs are unusual.
Wireless internet, everyone had same experience. 
Nobody was confused, it was the same. 
Other wireless connections: signal strength is intuitive. The comparison is relatable. 
It's the angle, it's the power, it's the direction. 

But what you said and how you said it is significantly more personal. 

Not fearful. No motivation to criticize wifi when it fails. 

People saying you have to use it. 
You absolutely don't have to use it. 
That's too much. 
You should be using it all the time.
"50% of salary on tokens means 10 times as productive" 
Are people's claims of acceleration accurate?

 Limitations social and physical
Physical:
- cost
- resource availability 
- accessibility to tools
Social:
- legal

Self reported performance improvements are flawed
Poor attribution modeling
Difficult to measure productivity impacts
 
Monkey brain love fast slot machine Gambler don't remember all the failed slots 

People being forced to use something and then it doesn't work. How is their experience when it does rarely work? 

Compared to finding a document on your computer, it will tell you I can't find it. An llm will never 

In the future, one that just gets its own podcast which is the lack of reliability 

---------------------------------- 

Thoughts from arguments with friends - Me

My buddy Tom said today "Why don't we just argue with AI more?" after yet another question brought us to agreement. Both of us sending AI answers to questions we asked. The answers generally agree, at least 80-90% saying the same thing. Tom and I have pretty opposite biases (but certainly ask better questions than average). We ask Gemini, Grok, Claude, ChatGPT. They're all still mostly right, mostly in agreement - even though they range some in precision/accuracy depending on the question. You get an instant answer, and probably wouldn't have done a deep critical reading from a variety of sources.

It's like, sure billionaire's make money but anyone can use this technology and undercut. It's probably the most healthy add to discourse for years. It might become captured and become super biased/sensored. Those ones will be used as much as Truth Social. We hear about the one person led to suicide or isolation, but may not hear about the 50 who were encouraged to reach out for help. These kinds of policies are incentivized through "safety" advancements, I hear about it from every company. Safer, better, more accurate, more balanced responses are all incentivized under a "pay for API access" system. Nobody wants to use a "we know it's loaded with ad sponsored crap like everything else" system. 

Free access to these tools, at some level, will always be economically encouraged. Even if the best companies don't provide free access to anything, there will be free models widely available and filling the gap. Why wouldn't another emerging competitor or open source project have a chance if the technology becomes paywalled? You can already download full LLMs from META (like Llama) for free. It comes optimized for local inference (quantized) and pre-trained. It does well 

------------------------------

Claude:
Here's a deep dive into the landscape of locally executable LLMs and how the three access tiers compare.

Freely available, locally runnable LLMs

Company-backed (open weights, but not fully open source)
These models are released by commercial companies with some restrictions on use (e.g., no competing AI products, usage caps for commercial licensing):
- Meta — Llama family (Llama 3.1, 3.2, 3.3) — The most popular local LLM lineage. Llama 3.3 70B punches near GPT-4o class on many benchmarks. Available in 1B–405B sizes. Released under Meta's custom license (not OSI-approved, but very permissive in practice).
- Google — Gemma 3 — Released in 1B, 4B, 12B, and 27B sizes. Notably multimodal (the 4B+ variants handle images). Strong performance per parameter. Apache 2.0 license — one of the cleaner permissive licenses from a big lab.
- Microsoft — Phi-4 — The "small but mighty" family (3.8B–14B). Phi-4 Mini is remarkable for edge/mobile use. MIT licensed.
- Mistral AI — Mistral, Mixtral, Mistral Small — European lab. Models range from 7B to the 8x22B MoE Mixtral. Apache 2.0 for most releases. Mistral Small 3.1 (24B) is highly competitive locally.
- Alibaba — Qwen 3 — The Qwen 3 family (0.6B–235B) is extremely strong, especially for coding and multilingual tasks. Apache 2.0 for most sizes.
- Cohere — Command R — Optimized for RAG and enterprise tool use. Open weights for research/non-commercial.

More genuinely open source
- Falcon (TII / UAE) — Apache 2.0, truly open including training data disclosure. Falcon 180B was a landmark open release.
- OLMo (Allen AI) — Apache 2.0 with full training data, code, and checkpoints released. The most transparently "open" large model from a research-forward org.
- SmolLM (HuggingFace) — Tiny models (135M–1.7B) with Apache 2.0, fully open pipeline. Great for embedded/edge.
- BLOOM (BigScience) — 176B multilingual model, fully open training data, RAIL license (permissive with responsible AI clauses).

How the three tiers compare
The chart below summarizes the tradeoffs across cost, capability ceiling, privacy, and flexibility.

<insert attached screenshot>

Key takeaways on performance
The gap between tiers is narrowing fast. As of early 2026, the best open-weight local models (Llama 3.3 70B, Qwen 3 72B, DeepSeek-R1) sit roughly at GPT-4 (2023 vintage) quality — strong enough for most professional tasks, but still behind frontier models like Claude Opus, Gemini 2.5 Pro, or GPT-4o on complex multi-step reasoning, long-context tasks, and tool use.

On cost, Tier 2 API pricing has dropped dramatically — GPT-4o mini, Claude Haiku, and Gemini Flash are now in the sub-$1/million token range, making "cheap cloud" very competitive with the real (electricity + hardware amortization) cost of running a 70B model locally on consumer GPUs.

Running local models
The easiest way to get started is Ollama (cross-platform, one command to pull and run most popular models) or LM Studio (GUI-friendly, good for Mac). For production deployment, vLLM and llama.cpp are the go-to inference engines. Most quantized (4-bit) models in the 7–13B range run on a modern gaming GPU or even Apple Silicon Macs with unified memory.


------------------------------


https://pytorch.org/blog/a-primer-on-llm-post-training/