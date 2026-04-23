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
  - Should the humorous framing be visual-heavy (meme style) or verbal-only?

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
  - Should this include a simple source-trust ranking (headline -> influencer -> manager summary -> engineer/primary source)?

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
