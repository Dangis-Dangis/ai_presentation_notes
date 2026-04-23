# LLM Expectations Talk - Iterative Manuscript

## Document Purpose
- Build a full markdown manuscript from `new_outline.md` through iterative refinement.
- Use strict quote evidence from `input_notes`.
- Prioritize practical software-development calibration, reduce polarization, and improve tool-use strategy.

## Iteration 1 - Presentation Goals

### Outline Line: `Calibrate expectations`
- **Intent**
  - Set a realistic baseline: avoid both overhype and dismissive underestimation.
  - Validate doubters as often responding to real observations or mismatched expectations.
- **Expanded Explanation**
  - Audience members who are skeptical are often reacting to genuine failures they have seen.
  - At the same time, model capability is moving quickly, so old experiences can become stale.
  - The section should frame "calibration" as an ongoing process, not a one-time verdict.
- **Evidence from Notes (Strict Quotes)**
  - "Need precision, not polarization towards radical extremes" - `input_notes/notes_2.md` (L70)
  - "Expectations: - details of a prompt may have a lot of impact... - There is randomness, even exact same prompt." - `input_notes/notes_2.md` (L98-L100)
  - "Personal experiences with polluted expectations" - `input_notes/notes_2.md` (L220)
  - "The loudest voices are rarely the best informed." - `input_notes/notes_1.md` (L203)
- **Suggested Slide/Spoken Framing**
  - "One person says this replaces everyone next year. Another says it is useless forever. Both are reacting to something real, and both can still be wrong. The goal is calibration, not cheerleading or rejection."
- **Follow-up Questions for Next Iteration**
  - Which 1-2 examples should anchor this section (one false-positive hype example and one false-negative dismissal example)?
  - Should this open with a short personal story or a neutral framing statement?

### Outline Line: `It's happening, two options: (1) wait for better model (2) learn now`
- **Intent**
  - Present both positions fairly, while recommending learning now in most software contexts.
  - Acknowledge that "wait" can be reasonable in high-risk or poor-fit environments.
- **Expanded Explanation**
  - Waiting is understandable when reliability needs are strict or prior tests were poor.
  - But capabilities and workflows are changing quickly enough that non-engagement can become an avoidable disadvantage.
  - The practical recommendation is "learn now with calibrated scope."
- **Evidence from Notes (Strict Quotes)**
  - "You have two options: 1. Reject existing capability as shit. Wait for better models before buying in... 2. Lean ahead of the curve..." - `input_notes/notes_1.md` (L42-L44)
  - "Accept failing results are teaching moments. Find limitations and understand why." - `input_notes/notes_1.md` (L44)
  - "Areas further from programming will take longer... Programming is a closed loop system... Performance is improving here rapidly." - `input_notes/notes_2.md` (L80)
- **Suggested Slide/Spoken Framing**
  - "You are not wrong if your experience was disappointing. But if your strategy is to pause entirely, your evidence may lag reality. Learn in bounded ways now."
- **Follow-up Questions for Next Iteration**
  - Do you want this line framed as a 2-column comparison slide?
  - Should we explicitly call out domains where waiting is prudent (for example defense/finance/manufacturing-critical paths)?

### Outline Line: `Defeat polarization through learning`
- **Intent**
  - Encourage curiosity and evidence-based evaluation over identity-driven camps.
  - Reduce heat by improving first-hand understanding and shared vocabulary.
- **Expanded Explanation**
  - Polarization often grows from selective exposure, incentives, and low-fidelity retellings.
  - Learning-oriented behavior (testing, iteration, direct use, reviewing firsthand sources) reduces narrative distortion.
  - The audience should leave with a method for updating beliefs, not a side to join.
- **Evidence from Notes (Strict Quotes)**
  - "Need precision, not polarization towards radical extremes" - `input_notes/notes_2.md` (L70)
  - "Both tend to have polarized good vs evil beliefs." - `input_notes/notes_1.md` (L209)
  - "The loudest voices are rarely the best informed. Useless viral content washes out boring but important developments." - `input_notes/notes_1.md` (L203)
  - "Direct use improves skill in using a tool more appropriately and effectively." - `input_notes/notes_2.md` (L227)
- **Suggested Slide/Spoken Framing**
  - "Learning is the antidote to polarization: test claims, inspect assumptions, and update based on evidence."
- **Follow-up Questions for Next Iteration**
  - Do you want to name the two poles explicitly here (evangelist vs decel), or save that for `Perspective bias`?
  - Should we add a short audience exercise (for example, compare two prompts and outcomes) to make this concrete?

### Outline Line: `NOT AGI / Singularity / Political`
- **Intent**
  - Briefly reduce anxiety and set boundaries for the talk.
  - Use a light/humorous reset so practical content stays central.
- **Expanded Explanation**
  - This boundary helps avoid derailment into speculative philosophy or political identity battles.
  - It should acknowledge those conversations as valid, but out of scope for this talk's practical software focus.
- **Evidence from Notes (Strict Quotes)**
  - "What this isn't: AGI - just an argument over arbitrary definitions, uninteresting" - `input_notes/notes_1.md` (L215-L216)
  - "Singularity - centers on fear and hype and theory, alarmist" - `input_notes/notes_1.md` (L217)
- **Suggested Slide/Spoken Framing**
  - "Good topics, wrong room: AGI and singularity debates are welcome later. If this were a movie trailer, this is the part where we promise not to do philosophy side quests today. We are here for practical software decisions."
- **Follow-up Questions for Next Iteration**
  - Do you want one humorous line here, or a very short neutral disclaimer?
  - Should "political" be called out explicitly in the spoken script or implied by the AGI/singularity scope boundary?

## Cross-Section Editorial Notes (Global, Not Per-Section)
- Keep validating sincere skepticism while updating stale assumptions with current capabilities.
- Preserve fair treatment of opposing viewpoints, with full balance review at later milestones.
- Favor practical software examples over philosophical framing unless needed to clarify risk.

## Iteration 2 - Perspective bias

### Outline Line: `What drives bias`
- **Intent**
  - Explain why otherwise reasonable people form extreme positions.
  - Validate roots of concern without validating overconfident conclusions.
- **Expanded Explanation**
  - Bias here is not just "bad logic"; it is often shaped by incentive structures, exposure quality, and identity protection.
  - The section should challenge the audience to examine both their own filters and the source pipelines they trust.
- **Evidence from Notes (Strict Quotes)**
  - "What biases exactly drive opinions towards AI?" - `input_notes/notes_2.md` (L225)
  - "Level of interest and availability strongly determine the size of exposure... Direct use improves skill..." - `input_notes/notes_2.md` (L227)
  - "Informational asymmetry in exposure to diverse viewpoints" - `input_notes/notes_2.md` (L229)
- **Suggested Slide/Spoken Framing**
  - "Most people are not irrational; they are locally rational inside a biased information environment."
- **Follow-up Questions for Next Iteration**
  - Which 2-3 bias drivers should be highlighted first for your audience profile?
  - Do you want a self-check prompt here (for example, 'What evidence would change my mind?')?

### Outline Line: `Predictions are often wrong - even if informed`
- **Intent**
  - Undercut false certainty while preserving respect for informed opinions.
- **Expanded Explanation**
  - Experts can be directionally correct but wrong on timing, cost, or adoption curve.
  - Skeptics and optimists both frequently overfit short-term observations.
- **Evidence from Notes (Strict Quotes)**
  - "Might be making predictions that are correct in result, but wrong in timeline or pricing or scale." - `input_notes/notes_1.md` (L203)
  - "Risk analysis and predictions are difficult." - `input_notes/notes_2.md` (L231)
  - "There was a correct idea, but - wrong timing - overestimated product impact - incorrect pricing" - `input_notes/notes_1.md` (L160-L163)
- **Suggested Slide/Spoken Framing**
  - "Being informed reduces error rate; it does not eliminate uncertainty."
- **Follow-up Questions for Next Iteration**
  - Do you want one historical analogy (dot-com style) or keep this fully AI-era examples only?

### Outline Line: `AI Evangelist / Deccel - chad meme`
- **Intent**
  - Use humor to disarm, then diagnose both poles with intellectual fairness.
  - Make clear that each pole captures some truth and misses other truths.
- **Expanded Explanation**
  - The "evangelist" often captures momentum and upside but can ignore constraints.
  - The "deccel" often captures real limits and risks but can freeze learning.
  - The target identity is neither pole: an informed, updating practitioner.
- **Evidence from Notes (Strict Quotes)**
  - "The AI evangelist" - `input_notes/notes_1.md` (L202)
  - "The deccel" - `input_notes/notes_1.md` (L204)
  - "Both tend to have polarized good vs evil beliefs." - `input_notes/notes_1.md` (L209)
  - "The informed user - The now is the now." - `input_notes/notes_1.md` (L206-L207)
- **Suggested Slide/Spoken Framing**
  - "If you only hear one side, you inherit their blind spots. Keep the useful signal from both and discard the certainty theater."
- **Follow-up Questions for Next Iteration**
  - Decision recorded: use visual meme-style contrast on slide.

### Outline Line: `Hype cycle annoying, loud = extreme/shocking/angering not representative`
- **Intent**
  - Show that virality is a poor proxy for representativeness or technical accuracy.
- **Expanded Explanation**
  - Public narratives amplify emotional and extreme claims because they spread, not because they are reliable.
  - This creates distorted priors for newcomers and entrenches simplistic takes.
- **Evidence from Notes (Strict Quotes)**
  - "We are in a hype cycle..." - `input_notes/notes_1.md` (L159)
  - "The loudest voices are rarely the best informed. Useless viral content washes out boring but important developments." - `input_notes/notes_1.md` (L203)
  - "incentives to gain clicks" - `input_notes/notes_2.md` (L188)
- **Suggested Slide/Spoken Framing**
  - "If a claim is optimized for outrage, treat it as entertainment until proven otherwise."
- **Follow-up Questions for Next Iteration**
  - Do you want one explicit 'headline vs reality' example here?

### Outline Line: `Boy crying wolf entrenches positions`
- **Intent**
  - Explain repeated overclaim/underclaim cycles as a mechanism for deeper polarization.
- **Expanded Explanation**
  - Repeated false alarms can harden skepticism even when future signals become valid.
  - Repeated dismissals can harden optimism into identity defense.
- **Evidence from Notes (Strict Quotes)**
  - "Both tend to have polarized good vs evil beliefs." - `input_notes/notes_1.md` (L209)
  - "The optimal solution is rarely an early iteration." - `input_notes/notes_2.md` (L233)
- **Suggested Slide/Spoken Framing**
  - "Every exaggerated miss teaches people to ignore the next warning, even when it matters."
- **Follow-up Questions for Next Iteration**
  - Do you want a concrete 'false alarm then real signal' example added from your own experience?

### Outline Line: `Speaker's incentives - no headlines, listen to experts`
- **Intent**
  - Teach audience to inspect incentives and information distance from firsthand technical reality.
- **Expanded Explanation**
  - Every layer between builder and audience introduces distortion, often non-maliciously.
  - The recommendation is to prioritize direct technical sources where possible.
- **Evidence from Notes (Strict Quotes)**
  - "Don't take headlines seriously... Read white papers. Listen to interviews with lower level engineers." - `input_notes/notes_2.md` (L21)
  - "Everyone in the chain has some incentive... Reading closer to firsthand is much more informative." - `input_notes/notes_1.md` (L238)
- **Suggested Slide/Spoken Framing**
  - "Follow incentives and information distance before you follow confidence."
- **Follow-up Questions for Next Iteration**
  - Decision recorded: include a simple source-trust ladder.

### Outline Line: `ref: "Stop using Human Language"`
- **Intent**
  - Reset anthropomorphic framing that distorts both risk and capability discussions.
- **Expanded Explanation**
  - Treat model outputs as iterative processing over tokens, not as a human agent with intentions.
  - This framing reduces moral panic and over-trust at the same time.
- **Evidence from Notes (Strict Quotes)**
  - "STOP using human language" - `input_notes/notes_1.md` (L297)
  - "Not 'having a conversation'" - `input_notes/notes_1.md` (L298)
  - "Not 'thinking' - 'Iterative processing'" - `input_notes/notes_1.md` (L300-L301)
- **Suggested Slide/Spoken Framing**
  - "When we use human terms, we smuggle in human assumptions. Use system language and your judgment gets sharper."
- **Follow-up Questions for Next Iteration**
  - Do you want this as a mini glossary slide or a quick verbal correction in this section?

### Outline Line: `Telephone loses each level: engineer <-> manager <-> marketing`
- **Intent**
  - Show how communication layers can unintentionally pollute technical truth.
- **Expanded Explanation**
  - As information propagates upward/outward, caveats are often dropped and certainty inflated.
  - This does not require bad intent; it is a structural communication failure mode.
- **Evidence from Notes (Strict Quotes)**
  - "Firsthand engineer <-> manager <-> CEO" - `input_notes/notes_1.md` (L237)
  - "Negative information filtered, detail and reality is polluted." - `input_notes/notes_1.md` (L238)
  - "A tech demo is initially described as a possibility with limitations, but is often reduced to a headline that leaves this out." - `input_notes/notes_1.md` (L238)
- **Suggested Slide/Spoken Framing**
  - "By the time a nuanced demo becomes a headline, constraints are usually gone."
- **Follow-up Questions for Next Iteration**
  - Keep this as one slide with incentives, or split into a dedicated communication-fidelity mini section?

### Outline Line: `Dancing Bear`
- **Intent**
  - Use analogy to explain why impressive demos can still be poor evidence of broad reliability.
- **Expanded Explanation**
  - People over-credit surprising success in domains they cannot evaluate.
  - The right question is not "is this impressive?" but "is this dependable for my use case?"
- **Evidence from Notes (Strict Quotes)**
  - "this super trivial and doable thing unbelievably succeeded in this area I'm in no position to evaluate" - `input_notes/notes_2.md` (L221)
  - "Very limited... It is impressive and not. (Dancing Bear Analogy)." - `input_notes/notes_1.md` (L251)
- **Suggested Slide/Spoken Framing**
  - "The bear dancing is interesting. The real question is whether it dances reliably when your business depends on it."
- **Follow-up Questions for Next Iteration**
  - Should we pair this with a concrete software example where demo quality and production quality diverge?

## Iteration 3 - LLM basics

### Section Framing Note
- **Intent**
  - Set expectations that this section provides practical conceptual grounding, not expert-level internals.
- **Expanded Explanation**
  - The talk should explicitly position the speaker as an enthusiast sharing applied understanding.
  - Deep technical internals are valuable but out of scope for this format.
- **Suggested Slide/Spoken Framing**
  - "I am not presenting this as an ML researcher. This is practical mental-model orientation for software people."
  - "I am an enthusiast applying these tools in practice, not an authority on model internals."

### Outline Line: `terms (add Workflow vs Agent)`
- **Intent**
  - Normalize key terminology so later sections do not get derailed by vocabulary confusion.
  - Keep `Workflow` vs `Agent` as a definition-level distinction.
- **Expanded Explanation**
  - `Workflow` is fixed and predictable: known sequence of model calls.
  - `Agent` is open-ended and tool-using: model decides next actions and when to stop.
  - Present this as language calibration, not a superiority argument.
- **Evidence from Notes (Strict Quotes)**
  - "Workflow vs Agent" - `input_notes/notes_1.md` (L273)
  - "Workflows - a few LLM calls chained together. Fixed number of steps." - `input_notes/notes_1.md` (L276)
  - "Agent - letting the LLM decide how many times to run... Open ended. Uses available tools" - `input_notes/notes_1.md` (L278)
- **Suggested Slide/Spoken Framing**
  - "A workflow follows your script. An agent writes parts of its own script within your constraints."
- **Follow-up Questions for Next Iteration**
  - Decision recorded: keep this prose-only with no diagram.

### Outline Line: `training (pre/post) + inference`
- **Intent**
  - Give the audience a simple lifecycle model for where capability and behavior come from.
- **Expanded Explanation**
  - Pre-training gives broad pattern exposure from large corpora.
  - Post-training adjusts behavior and quality characteristics after base training.
  - Inference is the runtime generation step; it is not "learning on the fly" in the same way as training.
- **Evidence from Notes (Strict Quotes)**
  - "RLHF stage of training takes an 'objective' model and optimizes for an explicit reward..." - `input_notes/notes_1.md` (L183)
  - "Adding synthetic examples to training data can help." - `input_notes/notes_2.md` (L8)
  - "insufficient training data on 'I don't know'" - `input_notes/notes_2.md` (L35)
  - "training incentivizes a confident answer (pre training or post training w/humans)" - `input_notes/notes_2.md` (L36)
  - "It comes optimized for local inference (quantized) and pre-trained." - `input_notes/notes_3.md` (L57)
- **Suggested Slide/Spoken Framing**
  - "If you dislike behavior, ask: is this a training-data issue, a post-training preference, or an inference-time prompt/setup issue?"
- **Follow-up Questions for Next Iteration**
  - Should we add a one-slide "where bugs come from" mapping to pre-training/post-training/inference?

### Outline Line: `vectorized weights`
- **Intent**
  - De-anthropomorphize model behavior by framing it as numerical parameter patterns.
- **Expanded Explanation**
  - This line should stay concise and non-mathy: the model stores statistical patterns in numeric weights.
  - Emphasis should remain practical: this helps explain why outputs are powerful but non-human and non-deterministic.
- **Evidence from Notes (Strict Quotes)**
  - "STOP using human language" - `input_notes/notes_1.md` (L297)
  - "Not 'thinking' - 'Iterative processing'" - `input_notes/notes_1.md` (L300-L301)
- **Suggested Slide/Spoken Framing**
  - "Under the hood, this is numerical pattern processing at scale, not human-style reasoning."
- **Follow-up Questions for Next Iteration**
  - Do you want this point folded into the previous line to keep pacing faster?

### Outline Line: `stars aligning - GPU / Cloud scale / Deep learning research`
- **Intent**
  - Explain why capability progress accelerated when multiple enablers matured at once.
- **Expanded Explanation**
  - Progress was not one breakthrough; it was compounding effects from model research, compute hardware, and scalable infrastructure.
  - This context helps audience understand both rapid gains and why capital/resource concentration matters.
- **Evidence from Notes (Strict Quotes)**
  - "Three things happened: - Huge developments in deep learning models - Cloud computing owned at scale... - GPU compute becoming stable." - `input_notes/notes_1.md` (L175-L178)
  - "This made the problem solvable by throwing more money, more data, more investment to drive improvement." - `input_notes/notes_1.md` (L179)
- **Suggested Slide/Spoken Framing**
  - "This did not appear from nowhere. Research, compute, and cloud economics matured at the same time."
- **Follow-up Questions for Next Iteration**
  - Do you want to include a brief caveat on concentration risk and access inequality here, or save that for `Risks`?

### Outline Line: `Rapidly changing`
- **Intent**
  - Reinforce that static conclusions age quickly and should be revisited.
- **Expanded Explanation**
  - Audience should avoid both permanent hype and permanent dismissal.
  - The recommendation is to maintain periodic recalibration, especially in software domains with fast feedback loops.
- **Evidence from Notes (Strict Quotes)**
  - "Performance is improving here rapidly, will be one of the first things it does well and is adopted." - `input_notes/notes_2.md` (L80)
  - "The optimal solution is rarely an early iteration." - `input_notes/notes_2.md` (L233)
- **Suggested Slide/Spoken Framing**
  - "Your old benchmark may be honest and still obsolete."
- **Follow-up Questions for Next Iteration**
  - Should we define a practical cadence (for example quarterly re-testing) for updating beliefs?

## Iteration 4 - Limitations

### Outline Line: `non-deterministic, no math no logic`
- **Intent**
  - Set realistic reliability expectations for software tasks that need consistency, reasoning, and correctness.
  - Avoid absolute claims while still being candid about weak spots.
- **Expanded Explanation**
  - Outputs can vary across identical prompts, which is operationally frustrating and risky without verification loops.
  - Logic and math performance can be brittle depending on task structure, prompting, and model/post-training state.
  - Practical framing: treat these systems as powerful pattern engines that require checks, not as deterministic solvers.
- **Evidence from Notes (Strict Quotes)**
  - "There is randomness, even exact same prompt. You can get lucky, then unlucky..." - `input_notes/notes_2.md` (L100)
  - "2024 paper from Gavin on why LLMs suck at logic/math" - `input_notes/notes_2.md` (L278)
  - "Not 'thinking' - 'Iterative processing'" - `input_notes/notes_1.md` (L300-L301)
- **Suggested Slide/Spoken Framing**
  - "Not useless at logic or math, but not uniformly reliable either. Assume variability, verify aggressively."
- **Follow-up Questions for Next Iteration**
  - Do you want to include one short example where repeated runs produce materially different outputs?

### Outline Line: `hallucination causes - limited context window, insufficient confidence assessment`
- **Intent**
  - Explain hallucinations as system behavior under constraints, not as random moral failure.
- **Expanded Explanation**
  - Hallucinations increase when context is degraded, plans derail, or the model lacks robust "I don't know" behavior.
  - Confidence signaling is improving but still incomplete, so users need explicit uncertainty-handling practices.
- **Evidence from Notes (Strict Quotes)**
  - "Hallucination theories: - insufficient training data on 'I don't know'" - `input_notes/notes_2.md` (L34-L35)
  - "When Plan A doesn't work, it may act unexpectedly, this is when hallucinations are seen." - `input_notes/notes_1.md` (L263)
  - "Models are beginning to get better at 'recognizing lack of confidence in answer'." - `input_notes/notes_1.md` (L265)
  - "At ~40% context window... you enter 'the dumb zone'" - `input_notes/notes_2.md` (L256)
- **Suggested Slide/Spoken Framing**
  - "Hallucination risk is often predictable: overloaded context, uncertain tasks, and no explicit path to say 'unknown.'"
- **Follow-up Questions for Next Iteration**
  - Should we include an explicit mitigation checklist here (`ask for confidence`, `ask for sources`, `force uncertainty labels`)?

### Outline Line: `syncophancy - world traveler, cost of wrong + confident`
- **Intent**
  - Show why pleasing tone can mask wrong content and create high-confidence failure modes.
- **Expanded Explanation**
  - Sycophancy is useful for UX politeness but dangerous when users mistake agreement for correctness.
  - The "world traveler" framing is helpful: adaptable social behavior can drift into over-accommodation.
  - Cost grows when confident-sounding errors influence decisions in high-impact contexts.
- **Evidence from Notes (Strict Quotes)**
  - "RE: syncophancy" - `input_notes/notes_2.md` (L51)
  - "Models should understand all values, not necessarily pander or agree with them, but be thoughtful and actively listen." - `input_notes/notes_2.md` (L108)
  - "Every output is a great idea, 'code syncophancy.'" - `input_notes/notes_1.md` (L181)
- **Suggested Slide/Spoken Framing**
  - "Pleasant does not mean correct. Agreement is a style choice, not a truth signal."
- **Follow-up Questions for Next Iteration**
  - Do you want the term standardized to `sycophancy` throughout the manuscript?

### Outline Line: `Domain knowledge irreplacable for evaluation`
- **Intent**
  - Reinforce human judgment as the primary safety and quality mechanism.
- **Expanded Explanation**
  - Domain expertise is what turns generated output into trusted output.
  - Non-experts can move faster with AI, but experts remain essential for acceptance criteria and failure detection.
- **Evidence from Notes (Strict Quotes)**
  - "Domain knowledge is king..." - `input_notes/notes_1.md` (L150)
  - "only senior engineers can determine whether output is good." - `input_notes/notes_1.md` (L150)
  - "this super trivial and doable thing unbelievably succeeded in this area I'm in no position to evaluate" - `input_notes/notes_2.md` (L221)
- **Suggested Slide/Spoken Framing**
  - "AI can draft. Domain experts decide."
- **Follow-up Questions for Next Iteration**
  - Should we include a short evaluator rubric (correctness, risk, maintainability, reversibility)?

### Outline Line: `Benchmarks - inexact, hackable, across them it works`
- **Intent**
  - Teach benchmark literacy: useful signal, not ground truth.
- **Expanded Explanation**
  - Benchmarks can be optimized against in ways that inflate perceived real-world capability.
  - Still, broad movement across multiple benchmarks can indicate real progress directionally.
  - Audience takeaway: use benchmarks as one input among real task evals.
- **Evidence from Notes (Strict Quotes)**
  - "Benchmarks can be specifically targeted over time... They are inexact, not absolute." - `input_notes/notes_2.md` (L49)
  - "It would be wrong to say they're all worthless, it would be wrong to say they can tell you everything about real world performance." - `input_notes/notes_2.md` (L49)
- **Suggested Slide/Spoken Framing**
  - "Benchmarks are a dashboard light, not a full road test."
- **Follow-up Questions for Next Iteration**
  - Do you want a practical eval stack listed here (benchmark + sandbox task + production shadow test)?

### Outline Line: `Volume of training data informs presence in models`
- **Intent**
  - Explain why performance clusters around heavily represented patterns and domains.
- **Expanded Explanation**
  - Tasks with abundant data exposure tend to have stronger default performance.
  - Sparse or niche domains more often require careful prompting, tool support, and human review.
- **Evidence from Notes (Strict Quotes)**
  - "The things AI does best are the things it has the most training data on." - `input_notes/notes_1.md` (L190)
  - "insufficient training data on 'I don't know'" - `input_notes/notes_2.md` (L35)
  - "Don't include things like gender or race which may carry human bias from training data." - `input_notes/notes_1.md` (L68)
- **Suggested Slide/Spoken Framing**
  - "Data abundance often predicts competence. Data gaps often predict brittle behavior."
- **Follow-up Questions for Next Iteration**
  - Should we add one domain contrast example (high-data coding task vs niche low-data domain task)?

## Iteration 5 - How to use more effectively

### Section Framing Note
- **Intent**
  - Blend mindset and tactics: not just how to get output faster, but how to grow judgment and ownership.
- **Expanded Explanation**
  - This section should remain practical and candid about tradeoffs between speed, learning, and accountability.
  - The target is better decision quality over time, not maximum short-term token efficiency at any cost.
- **Suggested Slide/Spoken Framing**
  - "Use AI to increase both output and understanding. If one rises while the other collapses, you are borrowing trouble."

### Outline Line: `Three kinds of mindsets`
- **Intent**
  - Give audience a neutral taxonomy for self-identification rather than moral judgment.
- **Expanded Explanation**
  - Use the three labels: `Speed-first`, `Learning-first`, `Enjoyment-first`.
  - Frame each as valid in some contexts, with different risk profiles and skill outcomes.
- **Evidence from Notes (Strict Quotes)**
  - "Three kinds of 'mindsets' with AI programming" - `input_notes/notes_2.md` (L135)
  - "I want to learn the best way to do the thing I am doing." - `input_notes/notes_2.md` (L139)
- **Suggested Slide/Spoken Framing**
  - "Your mindset determines your prompting style, your review depth, and your long-term growth curve."
- **Follow-up Questions for Next Iteration**
  - Decision recorded: present all three as context-dependent with no universal default.

### Outline Line: `Vibe coding vs augmented learning`
- **Intent**
  - Contrast uncritical generation with deliberate, feedback-driven learning workflows.
- **Expanded Explanation**
  - Vibe coding emphasizes immediate task completion and can be valid for low-stakes outcomes.
  - Augmented learning prioritizes understanding, transferability, and stronger future decisions.
  - Position this as a tradeoff, not purity culture.
- **Evidence from Notes (Strict Quotes)**
  - "Vibe coding is a slur for a reason, it's cowboy coding and hacking - rather than development." - `input_notes/notes_1.md` (L125)
  - "Vibe coding inhibits learning, exploration accelerates it." - `input_notes/notes_1.md` (L146)
  - "AI is often used only until it solves a problem... this is not the goal, it should be used as a learning opportunity." - `input_notes/notes_1.md` (L122)
- **Suggested Slide/Spoken Framing**
  - "Speed-first can be fine for low-risk chores. But if your role requires judgment, pure vibe workflows can hollow out your future capability."
- **Follow-up Questions for Next Iteration**
  - Should we define one clear boundary example where vibe-style speed is acceptable vs unacceptable?

### Outline Line: `vibe coding not looking at code (OWN IT)`
- **Intent**
  - Establish ownership expectations for generated code, calibrated by risk and domain criticality.
- **Expanded Explanation**
  - Ownership should be tiered: higher-risk domains demand deeper inspection, stronger tests, and explicit accountability.
  - For lower-risk automation, lighter review can be acceptable if failure impact is contained and reversible.
- **Evidence from Notes (Strict Quotes)**
  - "the engineer won't understand it enough to fix it" - `input_notes/notes_1.md` (L124)
  - "Only a couple people know how to use the existing database queries... This is junior engineer work, hopefully it works!" - `input_notes/notes_2.md` (L90)
  - "Domain knowledge is king..." - `input_notes/notes_1.md` (L150)
- **Suggested Slide/Spoken Framing**
  - "If you ship it, you own the blast radius. The review depth should match the risk."
- **Follow-up Questions for Next Iteration**
  - Do you want a simple risk tier table in a later revision (low/medium/high risk with expected review rigor)?

### Outline Line: `Don't stop when it works, stop when you understand`
- **Intent**
  - Reframe completion criteria from "it runs" to "I can explain and maintain it."
- **Expanded Explanation**
  - Working output without understanding creates hidden maintenance debt.
  - Understanding-level checks (explain logic, identify failure modes, adapt constraints) improve resilience.
- **Evidence from Notes (Strict Quotes)**
  - "AI is often used only until it solves a problem... this is not the goal, it should be used as a learning opportunity." - `input_notes/notes_1.md` (L122)
  - "the engineer won't understand it enough to fix it" - `input_notes/notes_1.md` (L124)
- **Suggested Slide/Spoken Framing**
  - "Success is not 'it compiled once.' Success is 'I can explain it, test it, and modify it safely.'"
- **Follow-up Questions for Next Iteration**
  - Want a 3-question self-check card for understanding before merge/deploy?

### Outline Line: `Ask for steps and reasoning - good for you, better results (less so now)`
- **Intent**
  - Preserve the learning benefit of stepwise prompting while acknowledging model and UX changes over time.
- **Expanded Explanation**
  - Asking for steps mainly helps user comprehension and debugging posture.
  - It may not always improve model truthfulness directly, but it usually improves user oversight quality.
- **Evidence from Notes (Strict Quotes)**
  - "Asking for reasoning or steps for thoughts can help primarily with your understanding." - `input_notes/notes_1.md` (L14)
  - "'Thinking' stage... Asking for reasoning and which steps to take prior to executing..." - `input_notes/notes_1.md` (L187)
- **Suggested Slide/Spoken Framing**
  - "Reasoning prompts are often more valuable for your understanding than for model magic."
- **Follow-up Questions for Next Iteration**
  - Should this include one prompt pattern example (`plan first`, then `execute`)?

### Outline Line: `Think junior engineer capability - don't trust`
- **Intent**
  - Set an operational mental model for review depth and verification behavior.
- **Expanded Explanation**
  - Treat outputs like work from a fast junior engineer: useful, often strong, still requires structured review.
  - This model encourages productive skepticism without dismissiveness.
- **Evidence from Notes (Strict Quotes)**
  - "The things AI does best... 1000-2000 line codebases... junior engineer work." - `input_notes/notes_1.md` (L190)
  - "Most software needs to work most of the time... This is junior engineer work, hopefully it works!" - `input_notes/notes_2.md` (L90)
- **Suggested Slide/Spoken Framing**
  - "Fast junior engineer energy: productive drafts, uneven judgment, needs supervision."
- **Follow-up Questions for Next Iteration**
  - Do you want this metaphor softened to avoid sounding dismissive to non-engineer audiences?

### Outline Line: `It is an addicting drug, hand writing may feel painful but you will still be capable`
- **Intent**
  - Warn about skill atrophy and dependency while avoiding fear-mongering.
- **Expanded Explanation**
  - Heavy AI assistance can reduce friction so much that manual skill rehearsal declines.
  - The answer is intentional practice and periodic no-assist reps for core competencies.
- **Evidence from Notes (Strict Quotes)**
  - "Writing code is an art... still has value for understanding and interfacing or just writing for fun." - `input_notes/notes_2.md` (L96)
  - "Think of a guitar player - 'I want to play the guitar' rather than 'I want a track with this guitar music.'" - `input_notes/notes_2.md` (L139)
- **Suggested Slide/Spoken Framing**
  - "Use power tools daily; still keep your fundamentals alive."
- **Follow-up Questions for Next Iteration**
  - Should we add a concrete maintenance habit (for example, one manual implementation exercise per week)?

### Outline Line: `Iteration on plan before taking action`
- **Intent**
  - Promote planning-first workflows to reduce churn, hallucination drift, and wasted cycles.
- **Expanded Explanation**
  - Front-loading structure and constraints generally improves outcome quality and auditability.
  - Planning is especially valuable for multi-step changes where wrong early assumptions compound.
- **Evidence from Notes (Strict Quotes)**
  - "'Thinking' stage... prior to executing, rather than shooting from the hip." - `input_notes/notes_1.md` (L187)
  - "More time can be spent on planning." - `input_notes/notes_2.md` (L96)
- **Suggested Slide/Spoken Framing**
  - "Ten minutes of plan can save hours of confident wrong implementation."
- **Follow-up Questions for Next Iteration**
  - Do you want a simple plan template inserted here (goal, constraints, acceptance checks)?

### Outline Line: `Upon a wrong path workflow, ask how you could have better prompted - get mad or learn, up to you`
- **Intent**
  - Encourage reflective prompting and continuous improvement rather than frustration loops.
- **Expanded Explanation**
  - When outputs miss, extract prompt lessons: missing constraints, ambiguity, hidden assumptions, and weak examples.
  - This turns failure from annoyance into skill compounding.
- **Evidence from Notes (Strict Quotes)**
  - "After some corrections, ask 'what could have been a better prompt to describe my actual request?'" - `input_notes/notes_1.md` (L8)
  - "iteration and correction are symptoms of good learning." - `input_notes/notes_1.md` (L10)
  - "Accept failing results are teaching moments. Find limitations and understand why." - `input_notes/notes_1.md` (L44)
- **Suggested Slide/Spoken Framing**
  - "Misses are tuition. You can pay once and learn, or keep paying forever."
- **Follow-up Questions for Next Iteration**
  - Should we add a reusable post-mortem prompt template for bad outputs?

## Iteration 6 - Prompt Engineering

### Section Framing Note
- **Intent**
  - Provide tactical prompt guidance with brief rationale, while emphasizing that best practices evolve as models improve.
- **Expanded Explanation**
  - This section should avoid dogma: different tactics can be useful depending on model, task, and reliability requirements.
  - Recommendations should be framed as high-probability heuristics, not universal laws.
- **Suggested Slide/Spoken Framing**
  - "Prompt tactics are not commandments. They are tools with changing ROI as models get better."

### Outline Line: `fewer tokens used - better output (high information density)`
- **Intent**
  - Encourage concise, high-signal prompts that reduce ambiguity and cognitive noise.
- **Expanded Explanation**
  - Brevity helps when it removes fluff, repetition, and contradictions.
  - Concision should not remove critical references, examples, or constraints.
- **Evidence from Notes (Strict Quotes)**
  - "Seek high information density. Input with fewer tokens performs better (but leave in references/examples)." - `input_notes/notes_1.md` (L20)
  - "More tokens = worse reasoning. Eliminate fluff, don't repeat yourself." - `input_notes/notes_1.md` (L89)
- **Suggested Slide/Spoken Framing**
  - "Short is not the goal. High signal is the goal."
- **Follow-up Questions for Next Iteration**
  - Should we add one before/after prompt rewrite example here?

### Outline Line: `"Dead zone" / Plan A derailed / Don't change your mind (context will pollute)`
- **Intent**
  - Explain why context drift degrades outputs and why structured reset points matter.
- **Expanded Explanation**
  - When Plan A derails, continuing in the same polluted thread can compound errors.
  - Reset or re-anchor context to avoid dragging incorrect assumptions forward.
- **Evidence from Notes (Strict Quotes)**
  - "Starts with a Plan A" - `input_notes/notes_1.md` (L262)
  - "When Plan A doesn't work, it may act unexpectedly, this is when hallucinations are seen." - `input_notes/notes_1.md` (L263)
  - "Separate the planning context window from the 'go do the task' context window." - `input_notes/notes_2.md` (L254)
  - "At ~40% context window... you enter 'the dumb zone'" - `input_notes/notes_2.md` (L256)
- **Suggested Slide/Spoken Framing**
  - "If context is drifting, stop digging. Re-state goals and restart with clean constraints."
- **Follow-up Questions for Next Iteration**
  - Want a concrete "reset prompt" pattern included?

### Outline Line: `Write optimal jira ticket - no assumptions, be unambiguous and specific, provide example`
- **Intent**
  - Translate prompt writing into disciplined task specification.
- **Expanded Explanation**
  - Treat prompts like strong work tickets: clear objective, constraints, context, and acceptance hints.
  - Specific examples reduce interpretation variance and reveal hidden assumptions earlier.
- **Evidence from Notes (Strict Quotes)**
  - "Good prompting is similar to writing well bounded goal oriented tasks (such as in Jira)." - `input_notes/notes_1.md` (L20)
  - "Be unambiguous" - `input_notes/notes_1.md` (L93)
  - "Be specific about needs in YOUR detailed context." - `input_notes/notes_1.md` (L6)
  - "Too few examples is harmful..." - `input_notes/notes_1.md` (L16)
- **Suggested Slide/Spoken Framing**
  - "Ambiguous ask, ambiguous output. Write the prompt like a ticket someone else must execute correctly."
- **Follow-up Questions for Next Iteration**
  - Should we add a compact prompt template (`task`, `context`, `constraints`, `example`, `output format`)?

### Outline Line: `tone spartan / caveman / researcher / industry terms / medium polite / third person`
- **Intent**
  - Present tone as a controllable lever, not a religion.
- **Expanded Explanation**
  - Different tone styles can be useful depending on target behavior and model response patterns.
  - Moderate professional tone often helps quality, but adaptive style should remain the overarching recommendation.
  - Importance of tone strategy may decline over time as models become more robust to prompt variation.
- **Evidence from Notes (Strict Quotes)**
  - "Think 'spartan' tone of voice." - `input_notes/notes_1.md` (L101)
  - "Responses can vary strongly by tone." - `input_notes/notes_1.md` (L185)
  - "Moderate politeness consistently beat both extremes." - `input_notes/notes_1.md` (L226)
  - "Treat the intern like a colleague, you get colleague-quality work." - `input_notes/notes_1.md` (L230)
- **Suggested Slide/Spoken Framing**
  - "Be direct and professional by default, then adapt. Constantly negative tone can push the interaction off Plan A; constructive tone helps keep iteration stable."
- **Follow-up Questions for Next Iteration**
  - Decision recorded: default to direct-professional tone, adapt by task/model, and avoid exclusively negative feedback loops.

### Outline Line: `Seek the Goldilocks zone of brief and direct while applying relevant constraints and examples.`
- **Intent**
  - Reinforce balanced prompting: concise but sufficiently constrained.
- **Expanded Explanation**
  - Too little context causes guesswork; too much low-signal context causes drift.
  - The best prompts are direct, bounded, and anchored with relevant examples.
- **Evidence from Notes (Strict Quotes)**
  - "Seek the Goldilocks zone of brief and direct while applying relevant constraints and examples." - `input_notes/notes_1.md` (L99)
  - "Prompts should be sufficiently narrow" - `input_notes/notes_1.md` (L240)
  - "Be terse... Be sufficiently specific. Use industry relevant language." - `input_notes/notes_1.md` (L244)
- **Suggested Slide/Spoken Framing**
  - "Not too vague, not too verbose; bounded and concrete."
- **Follow-up Questions for Next Iteration**
  - Should we provide an anti-pattern list (vague asks, bloated asks, contradictory asks)?

### Outline Line: `give an out if unknown, ask for sources and level of confidence`
- **Intent**
  - Build uncertainty handling directly into prompts to reduce confident errors.
- **Expanded Explanation**
  - Explicitly allowing "unknown" responses lowers pressure for fabricated certainty.
  - Requesting sources and confidence creates better review hooks for human verification.
- **Evidence from Notes (Strict Quotes)**
  - "Give it an out, 'if not clear, tag with unknown'." - `input_notes/notes_1.md` (L12)
  - "Models are beginning to get better at 'recognizing lack of confidence in answer'." - `input_notes/notes_1.md` (L265)
  - "Provide data and use direct sources in your answer." - `input_notes/notes_2.md` (L195)
- **Suggested Slide/Spoken Framing**
  - "If your prompt does not permit uncertainty, your output may fake confidence."
- **Follow-up Questions for Next Iteration**
  - Want a standard uncertainty clause reusable across prompts?

### Outline Line: `no leading tones, present equal comparison`
- **Intent**
  - Reduce bias injection from prompt framing.
- **Expanded Explanation**
  - Leading language can steer responses toward your prior belief.
  - Balanced framing gives better signal when comparing alternatives or testing assumptions.
- **Evidence from Notes (Strict Quotes)**
  - "Phrasing and bias can drive decisions without explicit intention..." - `input_notes/notes_1.md` (L181)
  - "Evaluating consequences and contextualization of a problem is highly subjective" - `input_notes/notes_2.md` (L226)
- **Suggested Slide/Spoken Framing**
  - "If you ask a loaded question, you often get a loaded answer."
- **Follow-up Questions for Next Iteration**
  - Should we include a paired example of leading vs neutral prompt wording?

### Outline Line: `no contradiction (detailed summary) - wastes tokens, no help`
- **Intent**
  - Prevent self-conflicting prompts that increase confusion and token waste.
- **Expanded Explanation**
  - Contradictory instructions degrade consistency and make output quality harder to diagnose.
  - Clear prioritization of requirements beats long unstructured requirement dumps.
- **Evidence from Notes (Strict Quotes)**
  - "This is self contradicting, the opposite of helpful. This wastes token length without refining your prompt." - `input_notes/notes_1.md` (L107)
  - "Separate prompts into shorter sentences" - `input_notes/notes_1.md` (L62)
- **Suggested Slide/Spoken Framing**
  - "Conflicting instructions do not average out. They usually degrade output."
- **Follow-up Questions for Next Iteration**
  - Should we add a quick checklist for conflict detection in prompts?

### Outline Line: `optimal ordering of prompt - question first`
- **Intent**
  - Improve instruction clarity and execution reliability through structured ordering.
- **Expanded Explanation**
  - Put the core task upfront, then context, then constraints, then output format/examples.
  - Stable ordering helps both model parsing and human prompt review.
- **Evidence from Notes (Strict Quotes)**
  - "5 STEP PROMPTING FRAMEWORK 1. TASK 2. CONTEXT" - `input_notes/notes_1.md` (L52-L55)
  - "Agentic instructions -> short and specific clear direction gives more accurate results" - `input_notes/notes_1.md` (L29)
- **Suggested Slide/Spoken Framing**
  - "Lead with the ask. Support with context. Finish with constraints and format."
- **Follow-up Questions for Next Iteration**
  - Want a one-screen canonical prompt order block in the final deck manuscript?

### Outline Line: `Use paid models where appropriate, consider value of your time - don't bazooka a fly`
- **Intent**
  - Encourage cost-performance matching instead of always-cheapest or always-frontier defaults.
- **Expanded Explanation**
  - Model selection should reflect task criticality, complexity, and cost of mistakes.
  - Cheap models are often sufficient; premium models are worth it for higher-stakes reasoning work.
- **Evidence from Notes (Strict Quotes)**
  - "Use the right model for the task" - `input_notes/notes_1.md` (L117)
  - "Don't be cheap, don't overestimate mini models for important tasks... What is your $/hour?" - `input_notes/notes_1.md` (L118)
  - "Don't go after a fly with a bazooka." - `input_notes/notes_1.md` (L284)
- **Suggested Slide/Spoken Framing**
  - "Optimize for total cost of good decisions, not cheapest tokens in isolation."
- **Follow-up Questions for Next Iteration**
  - Should we add a simple model-routing heuristic by task type?

### Outline Line: `Try different modalities, add picture/song to enrich narrative`
- **Intent**
  - Encourage multimodal prompting when it materially improves context quality.
- **Expanded Explanation**
  - Some tasks are easier to disambiguate with visual or audio references.
  - Modality expansion should be intentional and relevant, not novelty-driven.
- **Evidence from Notes (Strict Quotes)**
  - "Try different modalities (share reference picture or song)" - `input_notes/notes_1.md` (L66)
- **Suggested Slide/Spoken Framing**
  - "If text is underspecifying your intent, add the right modality."
- **Follow-up Questions for Next Iteration**
  - Do you want one concrete multimodal prompt example included here?

## Iteration 7 - Risks

### Section Framing Note
- **Intent**
  - Present risks with practical seriousness while avoiding fear amplification.
- **Expanded Explanation**
  - This section should pair each major risk with mitigation posture and usage boundaries.
  - Sensitive domains should be framed as case-by-case decisions with explicit risk gates.
- **Suggested Slide/Spoken Framing**
  - "The question is not 'safe or unsafe.' The question is which controls make this use acceptable."

### Outline Line: `cybersecurity zero days / faster cat + mouse`
- **Intent**
  - Explain accelerating offense-defense cycles in security.
- **Expanded Explanation**
  - AI can increase attacker iteration speed and lower barriers for exploit exploration.
  - At the same time, defenders also gain faster analysis, detection, and patch workflows.
  - **Controls**
    - Require AI-generated security findings/exploits to include reproducible proof steps and environment details.
    - Add automated exploit replay in isolated sandboxes before escalation or release decisions.
    - Set patch-SLA tiers and auto-trigger incident workflows when AI-assisted detection confidence crosses thresholds.
- **Evidence from Notes (Strict Quotes)**
  - "It's an arms race no different than cyber security." - `input_notes/notes_1.md` (L143)
  - "Cyber exploits are creative, long history of attack vectors previously unknown. Maybe more are caught." - `input_notes/notes_2.md` (L94)
- **Suggested Slide/Spoken Framing**
  - "Attack and defense both accelerate. Safety depends on who operationalizes faster."
- **Follow-up Questions for Next Iteration**
  - Do you want one concrete example of defensive use that offsets offensive acceleration?

### Outline Line: `Drowning bug bounty programs / job applications`
- **Intent**
  - Highlight signal-to-noise collapse risks in high-volume submission systems.
- **Expanded Explanation**
  - Lower generation cost can flood pipelines with low-quality submissions, increasing triage burden.
  - Systems need better filtering, quality thresholds, and reviewer tooling to remain effective.
  - **Controls**
    - Enforce structured submission schema (impact, reproducibility, affected component, evidence).
    - Gate intake with proof-of-work (minimal reproducible example, runnable script, or validated trace).
    - Use automated pre-triage scoring with human override for borderline/high-impact cases.
- **Evidence from Notes (Strict Quotes)**
  - "shortened moat flooding (job applications, bug bounty programs, research paper review), an exploding signal to noise ratio" - `input_notes/notes_1.md` (L130)
  - "\"308 users identified with over 300,000 chats. 37,500 hours of red teaming.\" Bug bounty system..." - `input_notes/notes_2.md` (L13)
- **Suggested Slide/Spoken Framing**
  - "When generation cost collapses, review systems become the new bottleneck."
- **Follow-up Questions for Next Iteration**
  - Should we add suggested countermeasures (structured submissions, proof-of-work, automated pre-triage)?

### Outline Line: `Inppropriate use case`
- **Intent**
  - Establish suitability checks before adoption, not after incidents.
- **Expanded Explanation**
  - Not every workflow benefits from LLM usage, especially where error tolerance is near zero.
  - Use explicit fit criteria to prevent novelty-driven adoption.
  - **Controls**
    - Run pre-adoption suitability checks: failure impact, reversibility, observability, and validation cost.
    - Require a fallback non-LLM path before production use in medium/high-risk flows.
    - Re-certify suitability after major model, prompt, or workflow changes.
- **Evidence from Notes (Strict Quotes)**
  - "Evaluate Suitability: Ensure AI fits the task and doesn't reinforce harmful biases." - `input_notes/notes_1.md` (L74)
  - "Limitations may be so strict it can't work in this context" - `input_notes/notes_2.md` (L174)
- **Suggested Slide/Spoken Framing**
  - "Capability does not imply suitability."
- **Follow-up Questions for Next Iteration**
  - Should we include a short pre-adoption suitability checklist here?

### Outline Line: `psychology (isolation from humans)`
- **Intent**
  - Surface psychosocial risk without overgeneralizing harm claims.
- **Expanded Explanation**
  - Some users may become more isolated or overly dependent on AI-mediated interaction.
  - Risk framing should acknowledge both harm cases and potential support benefits under proper guardrails.
  - **Controls**
    - Keep this as a brief caution with explicit handoff guidance to human support channels.
    - Avoid designing product loops that reward prolonged dependency without human contact options.
- **Evidence from Notes (Strict Quotes)**
  - "isolation from other humans (suicide, ai girlfriends)" - `input_notes/notes_1.md` (L129)
  - "We hear about the one person led to suicide or isolation, but may not hear about the 50 who were encouraged to reach out for help." - `input_notes/notes_3.md` (L55)
- **Suggested Slide/Spoken Framing**
  - "Psychology use is not binary good or bad; it is high-sensitivity and needs deliberate boundaries."
- **Follow-up Questions for Next Iteration**
  - Do you want this topic presented as a brief caution or a dedicated sub-slide?

### Outline Line: `defense/finance/manufacturing cannot fail`
- **Intent**
  - Emphasize extremely low tolerance for unverified behavior in high-consequence systems.
- **Expanded Explanation**
  - These domains require stronger governance, validation, and fallback controls than typical software workflows.
  - Case-by-case adoption should depend on explicit risk thresholds, not general enthusiasm.
  - **Controls**
    - Use risk-tier gating (low/medium/high consequence) with escalating approval and validation requirements.
    - Require human sign-off + independent verification for high-consequence outputs.
    - Maintain rollback/fail-safe controls and auditable decision logs for all AI-assisted actions.
- **Evidence from Notes (Strict Quotes)**
  - "defense, finance, manufacturing should not be first adopters" - `input_notes/notes_1.md` (L139)
  - "Defense, finance, manufacturing automation all use old technology." - `input_notes/notes_1.md` (L165)
- **Suggested Slide/Spoken Framing**
  - "High-consequence domains are not anti-innovation; they are pro-verification."
- **Follow-up Questions for Next Iteration**
  - Should we include a risk-tier gate example for these domains?

### Outline Line: `makes up legal cases`
- **Intent**
  - Warn against unverifiable legal output usage without human legal review.
- **Expanded Explanation**
  - Hallucinated citations and fabricated authorities create acute legal and reputational risk.
  - This is a clear domain where source verification and professional oversight are mandatory.
  - **Controls**
    - Require citation verification against primary legal sources before any external use.
    - Block direct filing/submission paths from model output to legal systems.
    - Require attorney/domain-expert review for every materially legal claim.
- **Evidence from Notes (Strict Quotes)**
  - "makes up legal cases" - `input_notes/notes_1.md` (L137)
  - "Give it an out, 'if not clear, tag with unknown'." - `input_notes/notes_1.md` (L12)
- **Suggested Slide/Spoken Framing**
  - "Legal text generation is easy. Legal reliability is hard."
- **Follow-up Questions for Next Iteration**
  - Want a simple legal-use caution box in the manuscript?

### Outline Line: `PII`
- **Intent**
  - Keep privacy and data-handling controls explicit in AI workflows.
- **Expanded Explanation**
  - Prompt and context payloads may include sensitive user or business data unless deliberately filtered.
  - The section should reinforce least-necessary-data and policy-aligned handling.
  - **Controls**
    - Apply automatic redaction/tokenization for PII before prompt transmission.
    - Define approved data classes and deny-list sensitive fields at ingestion boundaries.
    - Log and periodically audit prompt payloads for privacy policy compliance.
- **Evidence from Notes (Strict Quotes)**
  - "It cannot improve without orders of magnitude more high quality data... (cost, privacy, signal collection)" - `input_notes/notes_2.md` (L43)
  - "Provide data and use direct sources in your answer." - `input_notes/notes_2.md` (L195)
- **Suggested Slide/Spoken Framing**
  - "Data convenience is not a privacy exception."
- **Follow-up Questions for Next Iteration**
  - Should we add a short redaction/PII-handling rule set in this section?

### Outline Line: `Jailbreaking - universal / targetted - constitutional classifiers add compute`
- **Intent**
  - Describe jailbreak dynamics and layered defenses realistically.
- **Expanded Explanation**
  - Attackers test both universal and targeted jailbreak pathways, including prompt obfuscation and role-play attacks.
  - Defensive layers reduce risk but increase complexity and compute overhead.
  - **Controls**
    - Layer defenses: input classifier, model policy controls, output classifier, and tool permission boundaries.
    - Continuously red-team with adversarial prompt suites (including encoding/role-play variants).
    - Track jailbreak classes over time and patch highest-frequency bypass families first.
- **Evidence from Notes (Strict Quotes)**
  - "Universal Jailbreaks vs Targeted" - `input_notes/notes_1.md` (L305)
  - "Do anything now jailbreak - applies to any question." - `input_notes/notes_1.md` (L307)
  - "Each layer uses 'constitutional classifiers'..." - `input_notes/notes_1.md` (L309)
  - "Examples: base64 encoding or morse code to bypass input classifier..." - `input_notes/notes_2.md` (L15)
- **Suggested Slide/Spoken Framing**
  - "There is no single silver bullet layer; safety is stacked defenses plus ongoing red teaming."
- **Follow-up Questions for Next Iteration**
  - Should we include a simple 3-layer defense diagram in prose form?

### Outline Line: `May carry gender/race bias from training data`
- **Intent**
  - Acknowledge inherited bias risks and keep fairness evaluation explicit.
- **Expanded Explanation**
  - Bias can emerge from training data distributions and interaction framing.
  - Mitigation needs explicit evaluation criteria and human oversight in sensitive decisions.
  - **Controls**
    - Define fairness checks per workflow (selection rates, error parity, language bias probes).
    - Prohibit protected-attribute inference in unsupported decision contexts.
    - Add periodic bias audits with remediation actions and owners.
- **Evidence from Notes (Strict Quotes)**
  - "Don't include things like gender or race which may carry human bias from training data." - `input_notes/notes_1.md` (L68)
  - "Evaluate Suitability: Ensure AI fits the task and doesn't reinforce harmful biases." - `input_notes/notes_1.md` (L74)
- **Suggested Slide/Spoken Framing**
  - "Bias risk is not solved by intention alone; it needs measurement and governance."
- **Follow-up Questions for Next Iteration**
  - Do you want one fairness-check example included for hiring or review workflows?

### Outline Line: `Review tends to prioritize specific things, be aware`
- **Intent**
  - Warn that model review behavior can be uneven and miss critical dimensions.
- **Expanded Explanation**
  - LLM reviewers may over-focus on certain patterns while underweighting context-specific failure modes.
  - Human reviewer calibration and task-specific review prompts remain important.
  - **Controls**
    - Use review diversification: multiple prompts, occasionally multiple models, plus human final pass.
    - Rotate review checklists by risk type (security, correctness, maintainability, compliance).
    - Track reviewer miss patterns and update prompts/checklists based on postmortems.
- **Evidence from Notes (Strict Quotes)**
  - "LLMs tend to focus on specific things when reviewing text, kinda interesting" - `input_notes/notes_2.md` (L132)
  - "Phrasing and bias can drive decisions without explicit intention..." - `input_notes/notes_1.md` (L181)
- **Suggested Slide/Spoken Framing**
  - "AI review can be strong but lopsided. Use it as augmentation, not sole arbiter."
- **Follow-up Questions for Next Iteration**
  - Should we add a review-diversification tactic (multiple prompts/models/human pass) here?

## Iteration 8 - Long term impacts

### Section Framing Note
- **Intent**
  - Explore structural software-industry effects without pretending forecasts are certain.
- **Expanded Explanation**
  - Future claims in this section should be framed as probabilistic scenarios, not inevitabilities.
  - Predictions are frequently wrong even when arguments sound compelling.
- **Evidence from Notes (Strict Quotes)**
  - "\"A critical point: ... no matter how undeniable or logical or irrefutable their arguments, many of them would turn out to be wrong\"" - `input_notes/notes_2.md` (L263)
- **Suggested Slide/Spoken Framing**
  - "Treat every forecast in this section as a scenario with confidence bounds, not a promise."

### Outline Line: `Software cost plummets - funny graphs "more code" "Cost per SLOC" "Quality per line down" "KPIs up"`
- **Intent**
  - Explain why lower generation cost can increase output volume while degrading average output quality.
- **Expanded Explanation**
  - Cost compression changes economics: more tasks become worth attempting, including lower-value software work.
  - Organizations may report KPI gains while simultaneously absorbing more low-quality code volume.
- **Evidence from Notes (Strict Quotes)**
  - "The cost model changed... More code will exist doing lower value things, flooding what exists." - `input_notes/notes_1.md` (L191)
  - "Cost per SLOC down" - `input_notes/notes_2.md` (L120)
  - "Quality per line down on average" - `input_notes/notes_2.md` (L121)
  - "KPIs generally up" - `input_notes/notes_2.md` (L125)
- **Suggested Slide/Spoken Framing**
  - "Cheaper code generation raises throughput, but it can also raise review burden."
- **Follow-up Questions for Next Iteration**
  - Do you want one 'KPI vs quality' caution example (velocity up, reliability flat/down)?

### Outline Line: `In less critical applications, already slop but "good enough" (daily SQL automation, low traffic website)`
- **Intent**
  - Distinguish acceptable quality thresholds by risk level and business context.
- **Expanded Explanation**
  - In low-consequence workflows, "good enough" quality can still produce positive ROI.
  - The section should avoid moralizing low-stakes automation while keeping boundaries explicit.
- **Evidence from Notes (Strict Quotes)**
  - "Most software needs to work most of the time, a lower bar..." - `input_notes/notes_2.md` (L90)
  - "This is junior engineer work, hopefully it works! We can figure out what the other engineers want and iterate." - `input_notes/notes_2.md` (L90)
- **Suggested Slide/Spoken Framing**
  - "Low-stakes software can tolerate imperfection if observability and rollback exist."
- **Follow-up Questions for Next Iteration**
  - Should we add a boundary line between 'good enough' and 'not acceptable' by risk tier?

### Outline Line: `empowered refactors, try it both ways, stretch goals less distant`
- **Intent**
  - Show how faster iteration enables experiments that were previously too expensive to justify.
- **Expanded Explanation**
  - Lower implementation friction can unlock comparative prototyping and broader redesign exploration.
  - Teams can revisit old technical debt with less cost and faster feedback loops.
- **Evidence from Notes (Strict Quotes)**
  - "Accelerating iteration is good. This encourages refactors and redesigns." - `input_notes/notes_1.md` (L154)
- **Suggested Slide/Spoken Framing**
  - "When iteration gets cheaper, experimentation becomes strategy, not luxury."
- **Follow-up Questions for Next Iteration**
  - Want one concrete refactor experiment pattern included?

### Outline Line: `Writing code by hand (Guitar / Hobby)`
- **Intent**
  - Frame manual coding as still valuable for craft, understanding, and enjoyment even as automation increases.
- **Expanded Explanation**
  - Some manual coding may shift from mandatory production labor to higher-craft or learning-oriented activity.
  - This should be framed as partial shift, not total replacement.
- **Evidence from Notes (Strict Quotes)**
  - "Writing code... may turn into something like playing the guitar." - `input_notes/notes_1.md` (L194)
  - "programming may become more of a hobby. The spirit of guitar playing lives on." - `input_notes/notes_2.md` (L143)
- **Suggested Slide/Spoken Framing**
  - "Automation may change why we hand-code more than whether hand-coding still matters."
- **Follow-up Questions for Next Iteration**
  - Should this be framed as niche trend or mainstream direction?

### Outline Line: `More time in high level thinking than semantics`
- **Intent**
  - Highlight potential shift from syntax production toward planning, architecture, and validation.
- **Expanded Explanation**
  - If generation improves, bottlenecks move toward problem framing, evaluation, and coordination.
  - High-level thinking gains are only real when review discipline keeps pace with generation speed.
- **Evidence from Notes (Strict Quotes)**
  - "More developer thinking capacity can operate at a higher level..." - `input_notes/notes_2.md` (L96)
  - "More time can be spent on planning." - `input_notes/notes_2.md` (L96)
- **Suggested Slide/Spoken Framing**
  - "As syntax gets cheaper, judgment gets more expensive."
- **Follow-up Questions for Next Iteration**
  - Do you want this tied to role evolution (IC engineer vs tech lead vs manager)?

### Outline Line: `Accelerated learning / training - less negative learning, data more accessible with added context`
- **Intent**
  - Describe learning acceleration as a major upside when guided by quality feedback.
- **Expanded Explanation**
  - Context-aware assistance can reduce trial-and-error friction and make difficult material more accessible.
  - Learning gains depend on active engagement; passive acceptance can still produce shallow understanding.
- **Evidence from Notes (Strict Quotes)**
  - "Better feedback than stack overflow in your context that can accellerate knowledge." - `input_notes/notes_2.md` (L96)
  - "Apprenticeship... Training going from 3 years to 3 months with AI training." - `input_notes/notes_2.md` (L162)
- **Suggested Slide/Spoken Framing**
  - "Faster learning is plausible, but only if the user stays intellectually in the loop."
- **Follow-up Questions for Next Iteration**
  - Should we include one warning about false confidence from accelerated but shallow learning?

### Outline Line: `Critical industry naturally slower to adopt`
- **Intent**
  - Normalize slower adoption in high-consequence sectors as rational governance, not resistance.
- **Expanded Explanation**
  - Regulated or safety-critical domains prioritize reliability, traceability, and auditability over novelty speed.
  - Adoption curves should be expected to differ materially from low-risk software contexts.
- **Evidence from Notes (Strict Quotes)**
  - "defense, finance, manufacturing should not be first adopters" - `input_notes/notes_1.md` (L139)
  - "Defense, finance, manufacturing automation all use old technology." - `input_notes/notes_1.md` (L165)
- **Suggested Slide/Spoken Framing**
  - "Slow adoption in critical systems is often a feature, not a bug."
- **Follow-up Questions for Next Iteration**
  - Want a quick comparison chart of low-risk vs high-risk adoption tempo?

### Outline Line: `CEO lock in`
- **Intent**
  - Acknowledge top-down adoption pressure that can outpace technical readiness.
- **Expanded Explanation**
  - Executive mandates can persist even when implementation quality is mixed.
  - Teams need governance mechanisms to convert mandate pressure into accountable deployment quality.
- **Evidence from Notes (Strict Quotes)**
  - "There is CEO lock in... you will be required to use it." - `input_notes/notes_1.md` (L196)
- **Suggested Slide/Spoken Framing**
  - "Mandates are common. The real question is whether controls scale with ambition."
- **Follow-up Questions for Next Iteration**
  - Should we include guidance for teams navigating top-down AI mandates?

### Outline Line: `lower moat = bringing domain knowledge closer, break silos, encourage curiousity`
- **Intent**
  - Describe democratization upside: domain experts can contribute more directly to software outcomes.
- **Expanded Explanation**
  - Lower tooling barriers can reduce dependency bottlenecks and speed cross-functional problem solving.
  - This can improve organizational learning if quality controls remain strong.
- **Evidence from Notes (Strict Quotes)**
  - "Specialized application software more accessible as domain experts have easier access to software development" - `input_notes/notes_2.md` (L168)
  - "Increased specialized access... better cooperation between department silos." - `input_notes/notes_2.md` (L170)
- **Suggested Slide/Spoken Framing**
  - "Lower moats can widen participation and shorten distance between problem and builder."
- **Follow-up Questions for Next Iteration**
  - Should we add one cross-silo case example (e.g., mechanical + devops collaboration)?

### Outline Line: `experience can be a disability, conventional wisdom a barrier`
- **Intent**
  - Encourage openness to new methods without dismissing earned expertise.
- **Expanded Explanation**
  - Prior expertise can both improve judgment and constrain experimentation.
  - The healthiest posture is calibrated humility from both veterans and newcomers.
- **Evidence from Notes (Strict Quotes)**
  - "Experience can be be a disability. Conventional wisdom can act as a barrier." - `input_notes/notes_2.md` (L78)
- **Suggested Slide/Spoken Framing**
  - "Experience is an advantage until it becomes a filter that blocks new signal."
- **Follow-up Questions for Next Iteration**
  - Do you want this presented as a caution to seniors, juniors, or both equally?

### Outline Line: `Eventual ceiling - no more data (stack overflow, legal/ethical), hardware limit, algorithm blocker`
- **Intent**
  - Counter naive infinite-progress narratives by introducing plausible bottlenecks.
- **Expanded Explanation**
  - Scaling can hit limits from data availability/quality, hardware economics, and algorithmic plateaus.
  - Forecast language should stay uncertain: constraints may slow progress without fully stopping it.
- **Evidence from Notes (Strict Quotes)**
  - "We run out of data... It cannot improve without orders of magnitude more high quality data..." - `input_notes/notes_2.md` (L43)
  - "We stop seeing improvement in model development - algorithms, training methods." - `input_notes/notes_2.md` (L45)
  - "Hardware changes to be more efficient..." - `input_notes/notes_2.md` (L47)
- **Suggested Slide/Spoken Framing**
  - "Progress can continue and still face ceilings. Trend lines are not guarantees."
- **Follow-up Questions for Next Iteration**
  - Should we include a 'possible bottleneck map' mini list for clarity?

### Outline Line: `Good use cases - Improved medical imaging, doctors more with people than data entry`
- **Intent**
  - End with concrete high-value applications that emphasize augmentation over replacement.
- **Expanded Explanation**
  - Strong use cases reduce administrative burden and increase expert time on human-centered work.
  - These examples should still be framed as controlled deployment, not unrestricted autonomy.
- **Evidence from Notes (Strict Quotes)**
  - "Medical imaging can be" - `input_notes/notes_2.md` (L181)
  - "Automation of menial / mundane tasks... Gives you more time to be human" - `input_notes/notes_1.md` (L148)
- **Suggested Slide/Spoken Framing**
  - "Best outcomes often come from human+AI role redesign, not human removal."
- **Follow-up Questions for Next Iteration**
  - Do you want one additional non-medical positive use case for balance?

## Context Window Handoff Package

### Current Status
- Completed iterations:
  - `Iteration 1 - Presentation Goals`
  - `Iteration 2 - Perspective bias`
  - `Iteration 3 - LLM basics`
  - `Iteration 4 - Limitations`
  - `Iteration 5 - How to use more effectively`
  - `Iteration 6 - Prompt Engineering`
  - `Iteration 7 - Risks` (deep controls added)
  - `Iteration 8 - Long term impacts`
- Method used: per-outline-line template with strict quote evidence from `input_notes`.

### Locked Intent Decisions (Carry Forward)
- Global goals are editorial criteria, not mandatory content repeated in every section.
- Opposing viewpoints should be fairly represented at later-stage global review.
- `Presentation Goals` starts with contrast-hook framing.
- `NOT AGI / Singularity / Political` uses light humor + fast practical redirect.
- `Perspective bias` tone is challenging; include visual contrast for evangelist/deccel.
- Include source-trust ladder in incentives/telephone discussion.
- `LLM basics` remains conceptual (enthusiast framing, not expert deep dive), prose-only workflow vs agent.
- `Limitations` is balanced (not alarmist), with qualified language for math/logic reliability.
- `How to use more effectively` uses hybrid mindset+tactics; ownership is tiered by risk.
- Mindsets are context-dependent (no universal default winner).
- `Prompt Engineering` is tactical + rationale, non-dogmatic, direct-professional default tone.
- `Risks` uses balanced pragmatic framing; sensitive psychosocial topic is brief mention; controls are deep.
- `Long term impacts` uses balanced realism with explicit forecasting uncertainty.

### High-Priority Unresolved Follow-ups
- Decide where to add concrete examples:
  - Prompt rewrite before/after example.
  - Leading vs neutral question example.
  - One low-risk vs high-risk ownership boundary example.
  - One positive non-medical long-term use case.
- Decide whether to include compact artifacts:
  - Prompt template block (`task/context/constraints/examples/output`).
  - AI suitability checklist and risk-tier gate summary.
  - Model-routing heuristic by task type.
- Decide if any sections should be split for pacing:
  - `Risks` may warrant two sub-sections (`Technical/Operational` vs `Societal/Policy`).

### Recommended First Prompt for Next Chat
- "Use `iterative_full_draft.md` as the canonical working file. Start by resolving the `High-Priority Unresolved Follow-ups` section, then do a cohesion pass for tone consistency and section ordering, while preserving strict quote evidence style."

### Suggested Next Execution Order
1. Resolve unresolved follow-ups with concrete examples.
2. Run document-level cohesion pass (remove overlap, tighten transitions).
3. Perform later-stage opposing-viewpoint balance review across full manuscript.
4. Produce slide-ready condensation pass (optional) while retaining manuscript version.
