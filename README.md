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



## laws of programming

- Conway's Law
  - “Any piece of software reflects the organizational communication structure that produced it.”

- Mooer's Law
  - "An information retrieval system will tend not to be used whenever it is more painful and troublesome for a customer to have information than for him not to have it.""
    - make the topic easy to find
    - make the information more visual
    - keep it short
    
    
- Wirth's Law
  - "The hope is that the progress in hardware will cure all software ills. However, a critical observer may
    observe that software manages to outgrow hardware in size and sluggishness."
  
- Goodhart's Law
  - "When a measure becomes a target, it ceases to be a good measure"
  
- Hyrum's Law
  - "With a sufficient number of users of an API, it does not matter what you promise in the contract:
    all observable behaviors of your system will be depended on by somebody."
    
## cupids for joyful coding and harnessing agents for the rest

I think that the intermingling of agent harnesses for rapid requirements & development is rapidly being built into different directions; one being fully automated, orchestrated coding agents; another leaning towards vibe-coding with human-feedback; or simply a useful pair programmer that is aware of the context and functionalities made available to them. I believe that there is joy to be had to work with AI agents learning your intentions and transducing sequences of words [tokenized] into a problem & solution domains that meets a need [in the minimal cognitive distance between what you write, what the language model transduces, what decisions agent(s) make, and and the task-completion].

_James Martin's method of rapid development: In general, RAD approaches to software development put less emphasis on planning and more emphasis on an adaptive process. Prototypes are often used in addition to or sometimes even instead of design specifications_

The five CUPID properties are:

- Composable: plays well with others
- Unix philosophy: does one thing well
- Predictable: does what you expect
- Idiomatic: feels natural
- Domain-based: the solution domain models the problem domain in language and structure

The sixth property is:

- **self-similar**: looks the same at every scale
    - **self-improving**
        - 
    - **self-teaching**
        - 
    - **self-modifyiong**
        - 
    - **self-evolving**
        - 
    - **self-improving**
        - 
     - **self-replicating**
        - 
     - **self-aware**
        -        
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
 

## useful defintions

**Agent**: 

    1. an LLM agent runs tools in a loop to achieve a goal
    2. an agent is a decision-making layer that takes a goal, develops a plan, invokes tools, and adapts based on results 

**Skills**:

    1. reusable, domain-specific capabilities the agent can invoke (think of them as functions it has been taught)
    
**Tools**:

    1. external software APIs, databases, or services that the agent can call during execution to provide additional capabilities. 

**Commands**:

    1. discrete instructions that the agent issues to tools or sub-agents

**Orchestration**:

    1. how you coordinate multiple agents, route tasks, and enforce policies across the workflow

**Guardrails**:

    1. the constraints, validators, and human-in-the-loop checkpoints that prevent the agent from producing or executing anything
       - that would violate your QMS, your risk framework, or patient safety requirements.

**Harness**: 

    1. the runtime that turns one into the other:
       - the model thinks, the harness decides what that thinking is allowed to touch.
    2. the complete infrastructure that wraps around an LLM to make it an functional agent
       - the model provides intelligence; the harness provides peripherals, memory, and boundaries



## Resources

- [Towards Long-Horizon Agents: A Survey](https://openreview.net/pdf?id=HyhfhlbWGh)
- https://www.anthropic.com/research/building-effective-agents
- https://github.com/RyanAlberts/best-of-Agent-Harnesses
- https://github.com/wannabeyourfriend/awesome-harness-evolution
- https://www.anthropic.com/research/building-effective-agents

- https://arxiv.org/abs/2005.14165
- https://arxiv.org/abs/2201.11903
- https://arxiv.org/pdf/2307.03172
- https://arxiv.org/abs/2205.11916
- https://arxiv.org/abs/2210.03629
- https://arxiv.org/pdf/2310.10501


### Frontier AI Model Evaluation Research

- [Research note: Metrics of Agent Ability](https://metr.org/notes/2026-07-24-metrics-of-model-ability/)
- [Task-Completion Time Horizons of Frontier AI Models](https://metr.org/time-horizons/)
- [Expenditure Horizon: Measuring Optimization Ability, with an Application to NanoGPT](https://metr.org/blog/2026-07-21-expenditure-horizon/)
- [Measuring AI Ability to Complete Long Software Tasks](https://metr.org/blog/2025-03-19-measuring-ai-ability-to-complete-long-tasks/)
- [Task Substitution and Uplift](https://metr.org/blog/2026-05-08-task-substitution-and-uplift/)
- [How Does Time Horizon Vary Across Domains?](https://metr.org/blog/2025-07-14-how-does-time-horizon-vary-across-domains/)
- [CoT May Be Highly Informative Despite “Unfaithfulness”](https://metr.org/blog/2025-08-08-cot-may-be-highly-informative-despite-unfaithfulness/)

### Agent Development Patterns

- [Agents with Constraints](https://developmentseed.org/blog/2026-10-16-agents-constraints/)
    - "Giving agents more freedom doesn't necessarily produce better results"
    - "Introduce constraints: limit the tools an agent can use, define how it returns information, or choose a smaller model for a specific task. These constraints can make agents more predictable and efficient"
    _Limit what agents can do_
    1. Give agents a specific set of tools rather than letting them generate or execute anything
        - smaller, more focused tools are usually easier to control and maintain.
        **small and composable**
    [!constraints](gentconstraints.png)
    - Agents/LLM orchestrate
    - tools produce facts
    - top-level agent plays a coordinating role only
        - it will pick an appropriate (based on a user's query)
        - look at intermediate outputs
        - and call out to the next tool
    - the tools produce facts in a ****deterministic** manner
    - while agents act as a user-interface and glue between tools

    _Controlling how agents respond_
    2. We need to be careful about howm language models present information
        - when an agent retrieves the right data, asking the model to generate a response introduces another opportunity for errors
        E.g. Retrieval-Augmented Generation grounds responses in an existing knowledge embedding model
            - reduces mistakes but doesn't eliminate them
            - take it a step further and limit the format of the agent's response
        I.e. snow cover analysis agent that retrieves information APIs and fills in a pre-defined response templates
            - agent returns information in a **predictable** format

        E.g. Keep the original data separate from the generated text
            - agent identifies relevant data and use **well-defined** tools to retrieve or process it
            - results are delivered to the application without passing through for another round of text generation
        I.e. Building agents that return the underlying data itself
            - rendered maps, statistics, dataset links, etc.
            - so user can inspect primary sources alongside any natural language output

        - These agent development patterns are applicable to _bounded, well-defined use cases_ 
        - where the types of questions and analyses users will request are known in advance
        - It works best when the _workflow can be decomposed into a finite set of discrete tools_,
        - and when **predictability**, **reproducibility** and **cost efficiency** matter more than open-ended flexibility

    _Choosing smaller, focused models_
    3. Smaller models won't work for every application, but they might be a good solution when the _task is narrow enough_
        - there are tradeoffs, of course, rather than trying to build agents that plan for everything



- [When Does Restricting a Coding Agent to execute_code Help? A Regime × Agent-Design Ablation](https://arxiv.org/abs/2607.10569)


- [Small Language Models for Efficient Agentic Tool Calling: Outperforming Large Models with Targeted Fine-tuning](https://arxiv.org/abs/2512.15943)



### Agile Software Development & AI-Native Engineering


#### Coding Agents


- [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)

#### Uncle Bob

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


- [Uncle Bob Martin on Clean Software, Craftsperson, Origins of SOLID, DDD, & Software Ethics](https://soundcloud.com/infoq-channel/uncle-bob-martin-software-craftsperson-solid-ddd-software-ethics)


#### Andinet's Tech blog

- [Agentic AI Is Coming to the SaMD Lifecycle](https://blog.andinet.dev/agentic-ai-is-coming-to-the-samd-lifecycle)
  - Designing, building, and shipping **Software as a Medical Device (SaMD)** must comply with some of the most demanding regulatory frameworks in any industry
    - every step of SaMD demands rigorous documentation, traceabilty, and quality assurance
  - Agentic AI, a class of autnomous systems that answers questions, plans, executes, and verifies multi-step tasks across complex workflows
  _How we harness it responsibly at every phase of the SaMD development lifecycle_
  
        
  - "Traditional AI responds to single prompt with a single output"
  - "Agentic AI systems perceive, plan, act, and verify autonomously across multi-step workflows"
    - they maintain context, use tools, call APIs, coordinate with other agents, and loop back to correct their own work
  _The guardrails aren't an afterthought in this domain. They're the product_
  
  1. identification and user needs
  
     *agent pattern*:
        - research orchestrator agent
          - decomposes general clinical question into sub-tasks
          - dispatches to specialized tool-calling agents for task-completion
           
        
      *guardrails and evaluation*
        - agent constraints using guardrails [for source attribution and hallucination detection]
          - a validator runs post-generation
            - checking every cited source exists and the claim reasonably follows from source text
        - a scope constraint is required to prevent the agent from drifting
          - drifting into [clinical] domains outside the intended use you defined
          
   2. requirements gathering and software requirement specifications
   
      *agent pattern*
        - requirements engineering agent
          1. a need-to-requirement mapping skill
            - takes each user need statement and generates candidate technical requirements
              - following your SRS template format, [complete with requirement IDs, priority levels, and risk classification tags per ISO 14971].
          2. a traceability matrix skill
            - auto-populates a bidirectional traceability matrix linking each user need to it derived requirements
              - and forward-link placeholders for design inputs, code modules, and verification tests
        - the agent uses structured output, macine-parseable schemas [that can be imported directly into your requirements management tools, e.g. Jira, GitHub, etc.]
        
    3. architecture and software design
    
       *agent pattern*
       
       *guardrails and evaluation*
       
    4. construction and coding
    
        *agent pattern*
        
        *guardrails and evaluation*
        
    5. testing and verification
    
        *agent pattern*
        
        *guardrails and evaluation*
        
    6. validation and post-market surveillance
    
        *agent pattern*
    
        *guardrails and evaluation*
          
 

- [The Old Rules Still Apply: Why Software Engineering Discipline Matters More in AI Engineering](https://blog.andinet.dev/the-old-rules-still-apply-why-software-engineering-discipline-matters-more-in-ai-engineering)
  - "Why write tests, specs, or design documents when a model can generate a working feature in minutes?"
    - "When implementation becomes cheap, the parts that were never about typing code become the whole job."
      - "Knowing what to build, and knowing whether what you built actually works, matter more now than they ever did"
     




### Agentic Systems, Agent Architecure, & Agent Harnessing

- [Prime Agent: Self-improving RLM Harness](https://arxiv.org/pdf/2608.23552)
- [Harness^2: Recursive Agent Harnessing for an Open World](https://arxiv.org/abs/2610.14224)
- [Why The Harness Matters More Than The Model | YC Paper Club](https://www.youtube.com/watch?v=n9xKblqyQ28)
- [The Best AI Models Fail at Physics: Coding Harnesses are to Blame](https://juliahub.com/blog/why-the-best-ai-models-fail-at-physics)
- [Why the Agent Harness Matters For Physical AI](https://juliahub.com/white-papers/why-the-agent-harness-matters-for-physical-ai)



- [Harness Engineering: Anatomy, Architecture, and Evolution of Coding Agents](https://arxiv.org/pdf/2609.00006)
- [What makes a harness a harness: necessary and sufficient conditions for an agent harness](https://arxiv.org/pdf/2606.10106)
- [Better Harnesses, Smaller Models: Building 90% Cheaper Agents via Automated Harness Adaptation](https://arxiv.org/pdf/2607.08938)


### Auto Research

- [How we built our multi-agent research system (Claude)](https://www.anthropic.com/engineering/multi-agent-research-system)

### Data Science Agent

- [DS-STAR: A state-of-the-art versatile data science agent](https://research.google/blog/ds-star-a-state-of-the-art-versatile-data-science-agent/)
- [Skill-based Agentic Evaluation for Real-time Data Science Tasks](https://arxiv.org/pdf/2609.16487)
- [Harness Engineering Can Make Small Language Models Explore Like Large Language Models](https://openreview.net/forum?id=VHjhq6vui2)
  
#### Benchmarks

- UniDataBench
- DAComp
- DABstep
- KramaBench
- DA-Code
- DataSciBench


### Geospatial Data Science Agent

- [Axis Spatial's Geospatial Agent Benchmark Evaluations](https://www.axisspatial.com/arena/methodology#evaluations)
- GeoAnalystBench
- GeoBenchX
- GeoAgentBench
- GISAgentBench


