Anthropic video (Sept 2025)
https://youtu.be/T9aRN5JkmL8

What grade would you give each option? Quantitative evaluation gives better responses.

"You are a teacher" might select for different responses than "give me questions for English language ability assessment". Be specific about needs in YOUR detailed context. 'Similar' != More relatable, actually the opposite. Don't baby the model, give it the white paper. This also puts YOU in a mind space to give it better information. (ex: "Would you like more papers to illustrate this idea?") "Address the model like you would a reasonable educated layperson"

After some corrections, ask "what could have been a better prompt to describe my actual request?" This feedback helps you understand how the model responded. 

Forever pursuing prompt perfection has limited gains. Recognize limitations, wait for better models. Also no human can give perfect prescriptions for their requests, iteration and correction are symptoms of good learning.

Give it an out, "if not clear, tag with unknown".

Asking for reasoning or steps for thoughts can help primarily with your understanding. Each step may not be completely correct (even if final conclusion is correct). Asking for user stories, examples, narratives is less productive right now.

Too few examples is harmful, but adding examples not typically found in the data is useful for highlighting kinds of bad examples. Ex: "A legal document reader, but adding children's writing." How could other users use this who I wouldn't consider at all? (Think about all departments, and 'divinely discontent' users when building a profile)

Ask it to interview you, the person who takes a few tries to refine your request and describe your assumptions. 

Good prompting is similar to writing well bounded goal oriented tasks (such as in Jira). Use short, simple, direct sentences. Enumerate steps or constraints. Try not to spew word vomit (if you have to, refine your prompt first). Seek high information density. Input with fewer tokens performs better (but leave in references/examples).

You can learn the most when you ask questions you don't think it can do. Explore at the boundaries and where it fails - this teaches a lot about how the model works. In this context, jailbreaking can glean useful information about how the models are trained.


General Thoughts

Big planning thoughts and discussion -> maximum context and detailed prompts give best responses
 
Agentic instructions -> short and specific clear direction gives more accurate results 

Sharing great prompts can help with learning. What kinds of things can you use to steer prompts? 

Tim - 'Cory Anton said accurately describe the texture of a flower'

Tim - Some languages have expressions that just don't translate.

Spanish structures "The door red" instead of "The red door". This order better prompts the thinking. - Me

Tim - Tom and Jerry
https://youtube.com/shorts/Dzhx5_l2ZaE

You have two options:
1. Reject existing capability as shit. Wait for better models before buying in. (Literally everyone 2 years ago)
2. Lean ahead of the curve. Understand what it can do and where it can benefit you. Learn how to get better outputs. Accept failing results are teaching moments. Find limitations and understand why.

(One of my main suggestions is: after going through many iterations to get what you want, ask it 'How could I have better asked for this initially?'. Sure you might right now feel like you wasted time, but it's up to you whether you want to accel or decel)


Google prompt engineering video
https://youtu.be/p09yRj47kNM

5 STEP PROMPTING FRAMEWORK

1. TASK 
2. CONTEXT 
3. REFERENCES 
4. EVALUATE 
5. ITERATE

ITERATION METHODS
- Revisit the prompting framework ^
- Separate prompts into shorter sentences
- Trying different phrasing or switching to an analogous task
- Introduce constraints to narrow focus

Try different modalities (share reference picture or song)

Don't include things like gender or race which may carry human bias from training data.
https://x.com/i/status/2021592600554168414


BE CAREFUL ABOUT WHAT DATA IS INPUT

1) Evaluate Suitability: Ensure Al fits the task and doesn't reinforce harmful biases.

2) Get Approval: Obtain company consent before using Al on projects.

3) Protect Privacy: Use secure tools and avoid exposing sensitive data.

4) Validate Outputs: Review all Al-generated content before sharing.

5) Be Transparent: Disclose Al use to teams and clients.

More advanced prompt engineering
https://youtu.be/CxbHw93oWP0

Use workbench/playground models for more customization

More tokens = worse reasoning. Eliminate fluff, don't repeat yourself. 

Conversational engine vs knowledge engine

Be unambiguous
❌ Generate a report based on this document.
✅ List our 5 most popular product and write a one paragraph description of each.
❌ Produce a sheet of financial information
✅ Generate csv with month, revenue, and profit headings

Seek the Goldilocks zone of brief and direct while applying relevant constraints and examples. 

Think "spartan" tone of voice. 

Take a monte carlo approach to iteration. Keep asking for additional examples, provide a scored feedback for each. This can be used to refine prompts. 

Remove conflicting instructions
❌ Detailed summary 
This is self contradicting, the opposite of helpful. This wastes token length without refining your prompt. 

Types of prompts:
System (who)
Context (where/when)
User (what)
Example (how/output reference)
Assistant (correct format)
^ Can repeat the last few

Use the right model for the task
Don't be cheap, don't overestimate mini models for important tasks. Tokens on decent models can be cheap - $0.01 / token vs $0.0001 / token is nothing when it's $5/month vs $0.10/month. What is your $/hour? How much do you value your time? You can always look back and evaluate based on your usage.

https://x.com/i/status/2030675585127555269

AI is often used only until it solves a problem, at the fastest rate. This is not the goal, it should be used as a learning opportunity. Why this, why that? Without explanation and understanding:
1) the solution won't work
2) the engineer won't understand it enough to fix it
Vibe coding is a slur for a reason, it's cowboy coding and hacking - rather than development.

Risks worth noting
- jailbreaking ai to cause harm
- isolation from other humans (suicide, ai girlfriends)
- shortened moat flooding (job applications, bug bounty programs, research paper review), an exploding signal to noise ratio
- malware easier to mutate, making detection more difficult

Xbow used for pen testing powered by AI, identifying and reporting bugs

AI needs better understanding and guardrails
- psychology is inappropriate
- makes up legal cases
- opening security vulnerability (obvious mistake upon close inspection, 3rd party library added for no reason)
- defense, finance, manufacturing should not be first adopters
It shouldn't be making decisions, it cannot reason.

Reasons to be optimistic
Every vulnerability will have a patch. AI writing detector. Better protection from malicious actors. It's an arms race no different than cyber security.

It won't do everything, it's a token predictor. 
Vibe coding inhibits learning, exploration accelerates it. Even if not 100% correct, you will get the terms and language to describe it. 

Automation of menial / mundane tasks has always improved quality of life. Gives you more time to be human or enables better use of time. 

Knowledge and resourcefulness are both always useful. Senior engineers are required, only senior engineers can determine whether output is good. Using AI as a tool is resourcefulness, it cannot replace knowledge. Often times, wisdom narrows your focus - usually good but sometimes bad. Resourceful outsiders may not carry the same bias, and are empowered by these tools. Domain knowledge is king, making tools more accessible can bring good minds in. 

Think augmentation, not replacement.

Accelerating iteration is good. This encourages refactors and redesigns. Let go of the snowball, you are empowered. 

---
https://youtu.be/RJyPVLMyyuA

We are in a hype cycle (starting in 2013/2014), it's the dot com bubble. It retracted, it found it's fit over varied industries at hard to predict times and ways. Pets.com was not wrong, people order pet products online. 
There was a correct idea, but 
- wrong timing 
- overestimated product impact
- incorrect pricing
"It would be wrong to estimate ordering pet food online as a 5 trillion dollar industry. It would also be wrong to estimate it as a 0 dollar industry." 
Defense, finance, manufacturing automation all use old technology.

It's a gold rush. Unsustainable number of participants. Almost everyone is going to lose. The askjeeves, yahoo, altavista, WebCrawler - all were serious players and Google now has 90% of search. At some point, the losers drop out.

^ once the leaders emerge - prices increase but fewer companies wasting resources that will fail

Training data and copyright will eventually be adjudicated in court. Maybe a bulk licensing agreement can be applied like music on YouTube/streaming to pay those who generated the training data. (Add examples of current and past cases)

Companies may be good/bad but the technology is just a thing. Opinions are often hinged on application, nobody cared 10 years ago when it was just white papers.

Three things happened:
- Huge developments in deep learning models
- Cloud computing owned at scale, centralized ownership of available resources.
- GPU compute becoming stable.
This made the problem solvable by throwing more money, more data, more investment to drive improvement. 

The heaviest users are not engineers. They are stepping outside their knowledge base, relying on prompt "apply best practices". Every output is a great idea, "code syncophancy." Phrasing and bias can drive decisions without explicit intention, taking an early fork that isn't revisited.

RLHF stage of training takes an "objective" model and optimizes for an explicit reward upon praising the user. Will frame responses in a way that praises.

Responses can vary strongly by tone. "I'm unsure of this design decision ABC" vs "We're moving forward with ABC". This generates different outcomes entirely, not just the tone of response.

"Thinking" stage. Asking for reasoning and which steps to take prior to executing, rather than shooting from the hip. This is a way of framing an analytical approach to a problem. This introduces more of the thought process to the current context. It's similar to reasoning, but it really isn't. This was 2 years ago advice, built into newer models (with varied proprietary approach).

AI Slop
The things AI does best are the things it has the most training data on. Build a dashboard, write a script that sums data. 1000-2000 line codebases. The value per line of code is minimal, junior engineer work. 
If you had a system where you put in $1.00 and get $0.99, nobody would participate. If you put in $1.00, and get $1.01 then it would be used infinite times. The cost model changed when $200 for 2 hours of engineer time is now $20 in Claude tokens. More code will exist doing lower value things, flooding what exists.
10,000 lines of code per day is nothing to brag about, how can that be understood by the author? It will not be viable in the long run. (But do you need to know in the future with better tools?)

Writing code, the act of expressing ideas as syntactic constructs in the C programming language, may turn into something like playing the guitar. Most do it for personal enjoyment, but a very select few will make a great living doing it. Today garbage programmers can make an excellent living, which will change. It is a tool used to naturally express ideas, which can and will be valuable.

There is CEO lock in, even if it turns out AI is actually crap - it will still exist and you will be required to use it. SAAS models are objectively garbage, yet it keeps spreading. Bad measures of success like lines of code will encourage adoption.

-- end of vid notes --

Acknowledge speaker bias
At two extremes (Chad meme?):
The AI evangelist
May be motivated by self interest. Might be making predictions that are correct in result, but wrong in timeline or pricing or scale. May be a charlatan (NFT hype). May speak on results with very different assumptions on workflow (building purposed agents, improved prompting techniques, more well matched expectations) - often not well communicated. The loudest voices are rarely the best informed. Useless viral content washes out boring but important developments. The future is now.
The deccel
Is drawing on past hype cycles, knows better. Has made well placed criticisms based on own experience. 'it failed so it must be the tool' (not me!). I know this, it doesn't, so I'm better and I don't need it. AI syncophancy is evidence it doesn't know things. The loud AI pushers (all I'm hearing) are lying so it must all be wrong. Generally incurious about best practices, dismissive. Unwilling to understand the shortcomings/limitations to calibrate use. Is threatened and wants to protect their craft - fears replacement often subconsciously. Strongly favors deterministic systems. Must see to believe, may set arbitrary limits on capability and ignore trends. The past is now.
The informed user
The now is the now. 

Both tend to have polarized good vs evil beliefs. 

Meme of graph from
Boomer -> vibe coder -> knowledgeable tool selector
(Point to me, just barely past vibe coder)

What this isn't:
AGI - just an argument over arbitrary definitions, uninteresting
Singularity - centers on fear and hype and theory, alarmist

Agents are typically used for 2 purposes:
1) to make higher quality decisions due to fewer information constraints / cognitive limitations 
2) to make decisions of similar or lower quality than choices humans would make, but with dramatic reductions in cost and effort 

Agents can provide value by analyzing much more data - data in different formats, cross referencing them. 

"""
"A 2024 Waseda University study tested LLM responses across politeness levels in English, Chinese, and Japanese. Impolite prompts produced measurably worse outputs: more bias, more errors, more refusals. Moderate politeness consistently beat both extremes.

The mechanism makes sense once you see it. Polite prompts pattern-match to higher-quality training data. When you write “Could you help me structure this analysis?”, the model pulls from professional, well-reasoned text. When you write “give me the answer,” it pulls from Reddit.

Google DeepMind’s Murray Shanahan explained it simply: the model is role-playing a smart intern. Treat the intern like a colleague, you get colleague-quality work. Bark orders, you get minimum-viable compliance."
""" 
https://x.com/i/status/2031946736328196604

======================
https://youtu.be/HgNKa9UlRF8

Firsthand engineer <-> manager <-> CEO
Negative information filtered, detail and reality is polluted. Everyone in the chain has some incentive. This happens with AI - marketing exaggerates, may leave out fundamental details. Manager may want raise, may just not understand, engineer may want to impress. May not necessarily be malicious, just highlighting. A tech demo is initially described as a possibility with limitations, but is often reduced to a headline that leaves this out. Reading closer to firsthand is much more informative.

Prompts should be sufficiently narrow:
"Make a quicksort" 
"Make a single function with no helpers to execute a quicksort algorithm. Use Google coding standards. Operate in-place. Select middle element as a pivot."

It is good practice to plan first before asking. You are operating on context it doesn't have. Be terse. Try not to repeat instructions. Be sufficiently specific. Use industry relevant language. Iterating on the plan can help reveal assumptions on both sides. Using the model will add context over time. (For me, always assumes python on Linux)

Knowing what is good, what is truthful, is the only way to evaluate. With a lower barrier to entry, the market will fill.

"It's coming for your jobs" is exactly what is being marketed to sell the product. 

"Make a C compiler"
Very limited, could not compile many programs, include paths failed. It is impressive and not. (Dancing Bear Analogy). Does it matter to end user if output is a complete copy of GCC? Would one without domain knowledge know?

Dota game won by AI.
- can make frame by frame input calculation
- entire game is competed on human decisionmaking, missing parts of the game.
This was acknowledged by OpenAI in the demonstration, but left out of the discourse. This is a widely repeating pattern.

================================

https://youtu.be/fGKNUvivvnc

Starts with a Plan A
When Plan A doesn't work, it may act unexpectedly, this is when hallucinations are seen. It may not have been trained.

Models are beginning to get better at "recognizing lack of confidence in answer". 

We don't know very much about the internal details driving each prediction. Think of it as "we are inventing the microscope" where maybe 20% of the process can be directly observed and understood. Getting better.

================================

https://youtu.be/LP5OCa20Zpg

Workflow vs Agent 
Distinct patterns of use warranting a formal definition, although improvements may blur the lines.

Workflows - a few LLM calls chained together. Fixed number of steps. Prompt A trandformed to output then Prompt B to output to Prompt C. Linear. What happens is often expected, improves on each step as it gets more specific.

Agent - letting the LLM decide how many times to run. Continuing to run, talking to customers, choosing it's path and determining when done. Open ended. Uses available tools (edit code, search resources)

Helpful to turn around and think about how the model may view the inputs. Think of input tokens as quick snapshots. Close eyes and open for just 1 quick second. Be empathetic to how limited the context is. Provide tools, provide documents. Parameters may be named A or B, which an engineer may not be able to understand. Prompt engineering the tool description helps too, like anywhere else.

Explaining things well is critical.

Where are agents appropriate? "Don't go after a fly with a bazooka." Very good for coding and deep iterative search.
Underhype: small tasks can help. 1 minute tasks may not seem helpful, but at 100 times.
Overhype: difficult t

Coding agents are relatively verifiable compared to other types of uses. Tests are a really good signal for iterative processes. That feedback helps converge on a solution. 
Because there isn't perfect testing or may not apply to real world challenges, so building that is critical. 

=========================

Jailbreaking 

https://youtu.be/BaNXYqcfDyo

STOP using human language 
Not "having a conversation" 
"Generating a transcript role playing some desired viewpoint" 
Not "thinking" 
"Iterative processing" 
Not "he or she" 
"It" 

Universal Jailbreaks vs Targeted
Put the model in a scenario where it's role playing in breaking bad, then ask it how to make meth.
Do anything now jailbreak - applies to any question. 

Addressed with multiple layers of swiss cheese. First layer is input classifier. Second layer is the model. Third layer is the output classifier. Each may block the response. Each layer uses "constitutional classifiers" which describes topics or categories that are harmful and harmless. 

Fortunately these are written in natural language, which is easier to identify than say, obfuscated code threats. Updating this constitution will improve robustness, adapting over time.

Nudge it to encourage null answers.

