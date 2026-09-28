# AI Safety Debate
**By Yuchen Zhang**

Recent frontier AI security issues sparked debates among different communities on the topic of AI Safety.

I wanted to write down some thoughts that I observe many discussions could be missing:
1. Two concerns about AI:
   * We are giving *execution access* and/or decision powers to AI a bit too much. LLM training structure is brittle by nature, even if the reward/loss function is set up perfectly. But then the reward function could just be proxies in the first place. We know this since the beginning of the algorithm, and small problems already exist, and we just keep expanding stronger capabilities that can create bigger problems. Making problems agentic help the models to test the world and get immediate feedbacks on how to improve, but the problem is that we also give the models the abilities to execute (a program for example). Previously, as pure chatbots, humans act as a barrier between a piece of generated code and the execution of that code.
   * We could lose the ability to verify AI output. (This is mentioned much more else where so I will not expand too much on this.)
2. We (or at least I was) are probably underestimating how much capital and power want to do 1. even though we know they are not 100% reliable.
3. If the ultimate goal is the final impact of making AI safe, it seems to me that it is not a good idea to keep arguments that divide people. Topics that are not about the actual problem solving discussions could be bad distractions to engage with.

