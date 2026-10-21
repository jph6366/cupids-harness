# cupids-harness

https://cupid.dev/
```
I believe that there are properties or characteristics of software that make it a joy to work with. The more your code has these qualities, the more joyful it is to work with; but everything is a tradeoff so you should always consider your context.
There are likely many of these properties, overlapping and interrelating, and there are many ways to describe them. I have chosen five that underpin much of what I care about in code. There is a diminishing return; five are enough to make a handy acronym, and few enough to remember.
```
https://dannorth.net/blog/cupid-for-joyful-coding
```
What started as lighthearted iconoclasm, poking at the bear of SOLID, has developed into something more concrete and tangible. If I do not think the SOLID principles are useful these days, then what would I replace them with? Can any set of principles hold for all software? What do we even mean by principles?

I believe that there are properties or characteristics of software that make it a joy to work with. The more your code has these qualities, the more joyful it is to work with; but everything is a trade-off so you should always consider your context.

There are likely many of these properties, overlapping and interrelating, and there are many ways to describe them. I have chosen five that underpin much of what I care about in code. There is a diminishing return; five are enough to make a handy acronym, and few enough to remember.

I will expand on each property in future articles so that this one does not get any longer, so please forgive me for not being more comprehensive.
```

https://www.youtube.com/watch?v=zcLPGC-tvgk&t=464s
```
Got my first agent [early grok agent]...
Well maybe this thing can help me with this project...
I was cleaning up after it all the time...
It's interesting because it's fast, but its frustrating because it makes me slow...
Because it's fast it can do things I cannot...
These things are fast and they don't care how boring the work is...
Overall that is my goal, if these things are fast [and they are] and if I can constrain them to do a good job, then I'm not going impose my slowness upon them...



Agents may be fast and relatively smart, but they are as subject as humans are to messy code, maybe there is a difference in threshold but the threshold is still there. Code can get messy enough that the agents can't deal with it anymore...

**automated checks v.s. steering**
- Uncle bob's early prompts was describing TDD and CLEAN CODE driven for inserting automated checks instead of steering the agent
  "The agents and the models treat the rules and guidelines like Pirates of Caribbean sense"
- There is a phenomenon called "lost in the middle", as the context builds up in the model the stuff at the beginning and end has more prominence than the stuff in the middle
  "Eventually the tests will slow the down the agents to the point that they are much slower than humans... but as long as you can keep the margin of productivity higher than a human, you're still ahead of the game"
  "Now I'm in the midst of trying to get multiple agents talking to each other and handing off to each other, so one guy does one thing and the next one reviews it and the next one tests it, and the next one hardens it... the communication overhead is crazy, yet it's still faster by a large token than a human"

"Lets try the AGILE approach, let them do a story or two, maybe I'll get manually involved, and you know sort a few things out, then a few more stories... We may never skip the manual organizing step at the end... I don't know if it's possible"
- Building the wrong thing is something that you can still do...
- Spec-driven development
"the cost of change has plummeted to as close to zero as I think we're ever going to get [and well that's a prediction I'll probably lose but still] the cost of change has gone so far down that why would you do this upfront planning because that's expensive, just fiddle, fiddle, fiddle until it looks right."
```



## cupids for joyful coding and harnessing agents for the rest

I think that the intermingling of agent harnesses for agile software development is rapidly being built into different directions; one being fully automated, orchestrated coding agents; another leaning towards vibe-coding with human-feedback; or simply a useful pair programmer that is aware of the context and functionalities made available to them. I believe that there is joy to be had to work with AI agents learning your intentions and transducing sequences of words [tokenized] into a problem & solution domains that meets a need [in the minimal cognitive distance between what you write, what the agent(s) do, what the language model generates, and what the code does].

The five CUPID properties are:

- Composable: plays well with others
- Unix philosophy: does one thing well
- Predictable: does what you expect
- Idiomatic: feels natural
- Domain-based: the solution domain models the problem domain in language and structure

The sixth property is:

- **Self-similar**: looks the same at every scale
    
  - **affinity** (from the Latin, affinis, "connected with") 
    - 
  - **identity** (from the Latin, identitas, "sameness")
    - 



  - **measure** (from the Latin, mēnsūra, "a measure")
    - 

  - generally address only scores on a single task for only an agent or for an agent and human expenditure and capability
    - applications to collections of tasks (**benchmark scores**) can be **domain-based** and varying in complexity
      - that is where at any magnification there is a smaller learning task that is similar to the whole collection of tasks learned.      
    - **task-completion time horizon** is the task duration (measured by human expert completion time) at which an agent is predicted to succeed with a given level of reliability
 


## Resources
- https://www.anthropic.com/research/building-effective-agents
- https://github.com/RyanAlberts/best-of-Agent-Harnesses
- https://github.com/wannabeyourfriend/awesome-harness-evolution


https://www.anthropic.com/research/building-effective-agents

### Measuring AI Agents
- [Research note: Metrics of Agent Ability](https://metr.org/notes/2026-07-24-metrics-of-model-ability/)
- [Task-Completion Time Horizons of Frontier AI Models](https://metr.org/time-horizons/)
- [Expenditure Horizon: Measuring Optimization Ability, with an Application to NanoGPT](https://metr.org/blog/2026-07-21-expenditure-horizon/)


### Benchmarks

### Agile Software Development

- [Uncle Bob Martin on Clean Software, Craftsperson, Origins of SOLID, DDD, & Software Ethics](https://soundcloud.com/infoq-channel/uncle-bob-martin-software-craftsperson-solid-ddd-software-ethics)
- [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)

### Harness Engineering

- [Why The Harness Matters More Than The Model | YC Paper Club](https://www.youtube.com/watch?v=n9xKblqyQ28)
- [Prime Agent: Self-improving RLM Harness](https://arxiv.org/pdf/2608.23552)

### Auto Research

- [How we built our multi-agent research system (Claude)](https://www.anthropic.com/engineering/multi-agent-research-system)

### Data Science Agent

- [DS-STAR: A state-of-the-art versatile data science agent](https://research.google/blog/ds-star-a-state-of-the-art-versatile-data-science-agent/)
