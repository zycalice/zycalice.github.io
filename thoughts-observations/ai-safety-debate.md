# AI Safety Debate
**By Yuchen Zhang**

Recent frontier AI security issues sparked debates among different communities on the topic of AI Safety.

I wanted to write down some thoughts that I observe many discussions could be missing:
1. Two concerns about AI:
   * We are giving *execution access* and/or decision powers to AI a bit too much. Imagine if you enable a coin flip machine to decide and execute nuclear weapon launch, it would be pretty bad.
   But people will not do this because they know that coin flip is obviously flawed. The successes in LLMs makes it *feel* like LLMs are probably correct and safe to do many things.
   LLM training structure is brittle by nature, even if the reward/loss function is set up perfectly. But then the reward function could just be proxies and imperfect in the first place.
   We know this since the beginning of the algorithm, and small problems already exist. But it seems we just keep expanding into new domains and developing stronger capabilities that can create bigger problems. 
   Making models agentic helps the models to execute and get immediate feedbacks on how to improve, but the problem is that we also removed human judgements for executing the intermediate steps. 
   Previously, as pure chatbots, humans could act as a barrier between a piece of generated code and the execution of that code.
   * We could lose the ability to verify AI output. (This is mentioned much more else where, so I will not expand too much on this.)
2. We (or at least I was) are probably underestimating how much capital and power still want to do 1. and give models lots of execution power and decision-making power, even though we *know* they are not reliable.
3. If the ultimate goal is the final impact of making AI safe, it seems to me that it is not a good idea to keep arguments that divide people into camps. Additionally, topics that are not about the actual problem-solving discussions from non-serious people are bad distractions to engage with. 
   * Discussing character attributions on certain communities ignore the actual underlying issue.
   * Score-keeping also wouldn't really help the problems.
