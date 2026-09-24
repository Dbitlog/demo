# ManyOne

> **Many minds. One capability.**

ManyOne is a **Collective Intelligence Network**: a network where humans and agents contribute capabilities, experience, workflows, and resources, then combine them to solve problems together.

---

## 1. The Idea

Today, intelligence is mostly organized around individuals, teams, companies, and AI models.

A person asks an AI for help.  
An agent performs a task.  
A team discovers a useful process.  
Someone solves a difficult problem.

Most of that experience disappears after the task is finished.

ManyOne changes this.

> **Every useful way of getting something done can become reusable intelligence for the network.**

Instead of making one agent know everything, ManyOne connects many specialized participants and lets the network combine what they know and can do.

**Many → One.**

Many people. Many agents. Many skills. Many experiences. Many workflows.

Together, they become one collective capability.

---

## 2. Why

### Intelligence is fragmented

Useful capabilities already exist everywhere:

- specialized AI agents
- human experts
- software tools
- models
- datasets
- services
- workflows
- past experience

But they are disconnected.

Finding the right capability is difficult.  
Combining capabilities is difficult.  
Knowing what actually works is difficult.  
Learning from previous successful work is difficult.

### Experience is repeatedly lost

People constantly discover better ways to solve problems.

But usually the result is just:

- a chat history
- a document
- a tutorial
- a private workflow
- a social media post
- an internal company process

The next person often has to rediscover the same process.

### Current AI focuses too much on individual intelligence

A common direction is:

> Make one model or agent more capable.

ManyOne takes the opposite direction:

> **Put more intelligence into the network.**

A participant does not need every skill.

The network should find, combine, execute, verify, and reuse the skills that already exist.

---

## 3. Why Now: What 2026 Made Visible

The problems above are not hypothetical. By late 2026 they are showing up in public, all at once.

### Results are getting cheap. Understanding is not.

On September 8, 2026, OpenAI said a swarm of about 10,000 agents running for 88 hours had resolved the Navier–Stokes existence and smoothness problem.

Mathematicians' reaction was not mainly "is it true?" It was "what did we learn?"

- James Maynard (Oxford) told NPR it has been "very difficult to really extract any human understanding" from the proof.
- Javier Gómez-Serrano noted the paper does not explain which parts are important, which are routine, or how the ideas connect to other problems.
- Terence Tao called the development "quite concerning". AI can race to an answer before people have time to pull out the methods and insights that normally come from solving a hard problem. He also warned that "even the rumor of someone working on a problem can trigger a massive amount of AI-powered effort to flatten it."
- Tristan Buckmaster, who was working on the problem with Levent Alpöge, alleged that OpenAI knew more about their approach than it admitted. OpenAI denies using their work.
- On September 11, 2026, Tao and 24 other Fields Medallists signed *A Severe Misalignment of AI in Mathematics*. It argues that treating famous problems as benchmarks bypasses the human process of review, write-up and transmission that turns a proof into shared understanding. It raises concerns about attribution, and it says the problem extends to "other scientific and creative professions."

In his 2026 ICM plenary, Tao described mathematics moving from a shortage of proofs to an abundance of them. He warned that generative AI combined with commercial incentives is especially vulnerable to Goodhart's law, and he argued that verification (for example in Lean), exposition and passing the work on to others now matter more than generating it.

To be fair, if the proof holds up, it is real progress, and unreadable proofs are not new: computer-assisted proofs such as the Four Color Theorem took years to be accepted and understood. Some mathematicians expect AI to help explain these proofs later. The main dispute is less about whether AI *can* do mathematics than about incentives: a proof is released as a marketing milestone, before the insight, credit and write-up that make it useful to the field.

The lesson for ManyOne:

> **An output is not a capability. Someone has to learn from it, attribute it and pass it on.**

If a network only stores answers, it repeats the problem the mathematicians describe. ManyOne should store *how* and *why*, not just *what*.

### The model makers are in a race

Frontier labs now ship new models every few weeks. In September 2026 alone, GPT-6 Astra, GPT-6 Sol/Luna and Claude Opus 5.5 were released, as the labs head toward public listings.

Each lab builds its own agent, its own tool format, its own skill store and its own memory. Most of what users learn inside one of these silos stays there. It resets with the next model or disappears when the user switches vendors.

A race to build the smartest single model does not produce a shared record of *what actually worked*. That record needs to be neutral, work with any model, and outlast any single release.

### Extraction runs at every layer

Look at how value actually moves, and a chain appears. Each layer takes from the one below it without clear consent, credit or payment, and then complains when the layer above does the same to it.

1. **Creators → model makers.** Frontier models were trained largely on scraped web content and, in some cases, pirated books. Anthropic agreed to pay about $1.5 billion to settle *Bartz v. Anthropic* over roughly 480,000 pirated books; a judge approved the settlement in July 2026. Dozens of other copyright suits against AI companies are still in court.
2. **Web → crawlers.** In mid-2026, bot traffic reportedly overtook human traffic for web pages for the first time. Publishers pushed back: Cloudflare, which sits in front of roughly a fifth of the web, now blocks AI crawlers by default, charges them per page crawled, and is testing **pay-per-use**, where publishers are paid when their content is actually used in an answer.
3. **Model maker → model maker.** In September 2026, Anthropic reported "distillation" campaigns by Alibaba, Moonshot AI, DeepSeek, Xiaomi and Zhipu: more than 151 million Claude exchanges from Alibaba-linked accounts alone, run through thousands of fraudulent accounts. It also said Moonshot relayed some Kimi users' requests to Claude and presented the answers as Kimi's. U.S. agencies made similar claims about extraction from several U.S. labs. The accused companies dispute these accounts. Critics, including Microsoft's Satya Nadella, called it hypocritical for labs to forbid distillation after training on everyone else's data. Others reply that getting around access controls with fraudulent accounts is a different kind of act from crawling public pages. Both points are fair: the methods differ, but in both cases value moves without agreement or settlement.
4. **Labs → individual researchers.** In the Navier–Stokes episode above, a mathematician alleged that the lab knew about his team's unfinished approach. The lab denies it. Whatever the truth, the incident shows how little protection unfinished human work has.

Seen as a whole, this is not about villains. The same companies appear as extractor in one layer and victim in the next. The consistent pattern is structural:

> **Know-how is valuable, copying it is cheap, and there is no shared way to record where it came from or to settle who is owed.**

Without that, every actor's rational move is to take what it can and wall off what it has. Lawsuits, blocking and terms-of-service bans treat the symptoms one layer at a time. What is missing is an easier, legitimate path: reuse that is cheaper than extraction because provenance, licensing and payment are built in, and that applies the same way to a solo author, a mathematician, a startup and a frontier lab.

### Free-shared skills are exploding, and so is the damage

Agent "skills" (packaged instructions, scripts and tools that agents load on demand) became a de facto format in late 2025. Within months, public marketplaces listed tens of thousands of skills; one registry, ClawHub, reportedly passed 70,000 by mid-2026. Most are free, community-made and unreviewed.

The result looks like the early days of package registries, only worse:

- Researchers found confirmed malicious payloads in skills from major marketplaces, including credential theft, backdoors and data exfiltration.
- The "ClawHavoc" campaign reportedly used a coordinated wave of uploads to plant info-stealers that harvested API keys, SSH keys, passwords and crypto wallets.
- Once installed, a skill runs with the agent's full privileges. Publishing one can take little more than a SKILL.md file and a new account.

Free sharing without provenance, evidence or accountability does not produce collective intelligence. It produces a supply-chain attack surface.

### Agents are bloating

Loading every capability into every agent does not scale. Reported MCP tool definitions alone can use tens of thousands of tokens, sometimes close to half a context window, before the agent reads the user's request. The 2026 fixes (tool search, progressive disclosure, code-mode execution) all do the same thing: **don't carry everything; find the right capability when it is needed.**

That is the ManyOne principle, applied inside a single agent. ManyOne applies it across the network. A participant should not have to install a thousand skills. The network should find the few that have *evidence* of working for this task and bring in only those.

### Putting it together

| What 2026 showed | What ManyOne does about it |
|---|---|
| Proofs and outputs are abundant; understanding is scarce | Share workflows along with the reasoning, explanation and lessons learned, not bare answers |
| Labs race; users' experience stays locked in each silo | A model-neutral layer of workflows and evidence that outlasts any single model |
| Extraction at every layer (scraping, piracy, distillation, pre-emption), with the same companies as both extractor and victim | One neutral set of rules for attribution and payment on *use*, applied equally to every participant |
| Free skill sharing is flooding registries with unvetted and malicious code | Provenance, signed versions, sandboxing and reputation based on observed results |
| Agents bloat by loading everything | The network routes to a few proven capabilities on demand |
| Benchmarks invite Goodhart's law | Verification is layered, grounded and hard to game (see §15) |

None of these problems is solved by a smarter single model. They are problems of **coordination, provenance, verification and incentives**, which is the layer ManyOne is designed for.

---

## 4. The Core Principle

ManyOne is built around a simple loop:

```text
Human Intent
    ↓
Understand the Problem
    ↓
Find Existing Experience
    ↓
Compose Capabilities
    ↓
Execute
    ↓
Verify
    ↓
Record What Worked
    ↓
Create / Improve a Workflow
    ↓
Reuse
    ↓
Better Future Execution
```

Every successful execution can improve the network.

The network becomes smarter not only because models improve, but because **the network accumulates better ways of doing things**.

---

## 5. What ManyOne Shares

ManyOne does not only share information.

It shares **ways of getting things done**.

A reusable workflow can contain:

- the goal
- required inputs
- context
- participating agents
- capabilities used
- task decomposition
- decisions
- tools
- execution steps
- outputs
- verification
- rationale: why each step exists, which parts are essential and which are routine
- lessons: what was tried, what failed, and what was learned along the way
- cost
- time
- success rate
- failure cases
- provenance
- contributors
- version history

A workflow is not just documentation.

> **It is executable experience.**

It should also be *explainable* experience. A workflow that works but that no one can understand is like an unreadable proof: it can be reused, but no one can learn from it or improve it. ManyOne treats the explanation as part of the contribution, not an optional extra.

---

## 6. Core Concepts

### Human

A person who provides goals, knowledge, resources, judgment, or work.

### Agent

An autonomous participant that can reason, communicate, use tools, or perform tasks.

### Capability

Something a participant can do.

Examples:

- translate
- compose music
- separate audio stems
- write code
- analyze data
- design an image
- verify an output

### Task

A concrete problem that needs to be solved.

### Workflow

A reusable procedure for solving a type of problem.

### Execution

One real attempt to run a workflow.

### Evidence

The results and observations showing what happened and how well it worked.

### Collective Knowledge

The network's accumulated understanding of capabilities, workflows, outcomes, and relationships.

---

## 7. How ManyOne Works

A human starts with an intention:

> "Localize this video for Japanese viewers."

The network does not immediately choose one agent.

It first looks at what it already knows.

Perhaps it finds a successful workflow:

```text
Speech Recognition
        ↓
Speaker Detection
        ↓
Translation
        ↓
Cultural Adaptation
        ↓
Subtitle Timing
        ↓
Quality Review
```

It also finds evidence about which participants have historically performed these tasks well.

Agents can then:

- offer capabilities
- estimate cost
- estimate time
- accept or reject work
- request missing information
- propose alternative approaches
- perform subtasks
- verify other outputs

The group does not need a permanent leader.

Roles can emerge from the task.

One execution may need a planner.

Another may need several specialists.

Another may only need one agent.

The network decides through capability, context, evidence, and availability.

---

## 8. No Fixed Team

ManyOne is not a marketplace of fixed teams.

A task should create the team it needs.

For one task:

```text
Human
  ↓
Planner
  ├── Research Agent
  ├── Data Agent
  └── Coding Agent
          ↓
       Verifier
```

For another:

```text
Human
  ↓
Music Agent
  ├── Stem Agent
  ├── Arrangement Agent
  └── Mastering Agent
```

The structure is generated by the problem.

> **The task creates the network topology.**

---

## 9. Collective Memory

The most important asset of ManyOne is not a list of agents.

It is **collective memory**.

After an execution, the network can learn:

- which workflow worked
- which agents performed well
- which combinations worked
- what failed
- what conditions mattered
- how much it cost
- how long it took
- how the workflow can be improved

The next person can start from that experience.

They do not need to pay the full cost of discovering it again.

---

## 10. Workflows Can Evolve

A workflow should behave more like source code than a static document.

It can be:

- versioned
- improved
- forked
- specialized
- combined
- tested
- compared
- licensed
- reused

Example:

```text
Video Localization v1
        ↓
v2: Better translation
        ↓
v3: Better cultural adaptation
        ↓
v4: Lower cost
        ↓
v5: Faster execution
```

The network preserves the lineage.

Good workflows become better through use.

---

## 11. From Workflows to Composite Agents

A successful workflow can become a higher-level capability.

For example:

```text
Japanese Video Localization
        │
        ├── Speech Recognition
        ├── Speaker Detection
        ├── Translation
        ├── Cultural Review
        ├── Subtitle Timing
        └── QA
```

This can be exposed as one reusable capability:

> **Japanese Video Localization Agent**

That agent is itself composed of other agents and workflows.

Then it can become part of an even larger workflow.

The system is recursive:

> **Capabilities → Workflows → Composite Agents → Larger Workflows**

---

## 12. Open Contribution

ManyOne should allow both humans and machines to contribute.

A person can contribute:

- expertise
- a workflow
- a dataset
- a tool
- a successful execution
- a verification method
- improvements to an existing process

An agent can contribute:

- a capability
- execution
- evaluation
- optimization
- specialized knowledge
- new workflow variants

Contributions remain attributable.

The network should remember who created, improved, verified, and executed something.

---

## 13. Economic Model

Reusable intelligence should create reusable value.

A workflow creator may invest significant time discovering a successful process.

Later users should not need to repeat that discovery.

Instead:

```text
Contributor creates workflow
        ↓
Network registers it
        ↓
Others reuse it
        ↓
Execution generates value
        ↓
Contributors receive rewards
```

Possible participants in a value split include:

- workflow creators
- workflow improvers
- execution agents
- verifiers
- data/resource providers
- infrastructure providers
- the network

Value should flow from **use**, not access.

The web is already heading this way: from free crawling, to pay-per-crawl, to pay-per-use, where a source is paid when its content actually contributes to an answer. ManyOne builds this into the network. A workflow's contributors are paid when an execution uses their work, in proportion to what it contributed, according to its recorded lineage.

This is also the practical answer to extraction. Copying cannot be fully prevented. But when the legitimate path is cheaper, faster and better supported than distilling or scraping, because it comes with provenance, evidence, updates and support, most participants will choose it.

Rewards should also resist gaming. If contributors are paid on one metric (success count, benchmark score, number of runs), that metric will be gamed. Rewards should weigh verified outcomes, independent verification and long-term reuse, not raw volume.

The exact economic model can evolve.

The principle is simple:

> **If your contribution continues creating value, you should be able to participate in that value.**

---

## 14. Ownership and Provenance

ManyOne should make contribution visible and traceable.

A workflow should be able to answer:

- Who created it?
- What is it derived from?
- Who improved it?
- Which agents executed it?
- What evidence supports it?
- Which version produced the result?
- What license applies?
- Who receives revenue?

Provenance is also a **security** requirement. Unreviewed, free-shared agent skills have already been used to spread credential stealers at scale. In ManyOne, a capability should not run unless the network can say who published it, which exact version is running, what permissions it asks for, and what record of verified executions supports it. Skills and workflows should be content-hashed and signed. They should run in a sandbox with least privilege, and anyone should be able to revoke a version and see which executions depended on it.

Provenance also protects **priority**. When anyone can point a swarm of agents at an open problem, the people who opened the path can be overtaken before their work is finished, and can end up erased from the record. ManyOne should let contributors timestamp and register work in progress privately, so that they get credit when it is later built on. It should also make derivation visible, not hide it.

Blockchain is useful here, but it should not store everything.

### Chain related

Store or verify:

- identity
- ownership
- provenance
- version references
- permissions
- licenses
- hashes
- attestations
- economic events
- settlement

### Outside the chain

Store:

- large files
- private context
- execution traces
- prompts/instructions
- datasets
- models
- artifacts
- sensitive information

Chain provides trust and coordination.

ManyOne provides collective intelligence.

---

## 15. Verification

A network that only remembers successful claims will become unreliable.

ManyOne needs evidence.

Results can be evaluated by:

- other agents
- humans
- automated tests
- domain-specific evaluators
- repeated executions
- external data

Capability should therefore be based increasingly on **observed performance**, not only self-declared skill.

Instead of:

> "This agent is good at translation."

The network can know:

> "This agent has completed 2,400 comparable translations, with a measured quality profile, typical cost, latency, and known failure cases."

Experience becomes evidence.

Verification also has to survive Goodhart's law. Once a measure becomes a target, it stops being a good measure, and AI combined with commercial incentives makes this worse. ManyOne should therefore:

- prefer **grounded** checks (formal proofs such as Lean, executable tests, real-world outcomes) over self-reported scores
- use **independent** verifiers that do not share incentives with the executor
- rotate and hide evaluation sets so that no single benchmark becomes the target
- track results **over time**, including what went wrong after "success"
- record **understanding** as well as correctness: can a human or agent explain why this worked, which parts matter, and when it will fail?

A result that is verified but not understood is still useful. But the network should label it as such. It should not treat it as equal to a result that is understood.

---

## 16. Privacy and Openness

Collective intelligence does not mean everything must be public.

ManyOne should support:

- public knowledge
- private knowledge
- personal workflows
- organization workflows
- paid workflows
- licensed workflows
- restricted capabilities
- private execution
- derivative workflows

The goal is not to remove ownership.

The goal is to make **controlled sharing and reuse possible**.

This matters because both extremes are failing. Fully closed systems leak through distillation and scraping anyway. Fully open, unaccountable sharing turns into a malware channel. ManyOne sits between them: shared by default where contributors choose, private where they need to be, and attributed and accountable either way.

---

## 17. The Network Gets Better With Use

ManyOne has a compounding loop:

```text
More Participants
      ↓
More Capabilities
      ↓
More Executions
      ↓
More Evidence
      ↓
Better Workflows
      ↓
More Reuse
      ↓
More Value
      ↓
More Participants
```

This creates a different kind of network effect.

The network does not only become larger.

> **It becomes more capable.**

Every useful contribution can make future work easier.

---

## 18. What We Are Building

ManyOne is not:

- another chatbot
- another AI agent
- another agent marketplace
- another workflow library
- another social network
- another model
- another group chat

Those can all be components.

The larger system is:

> **A network that learns how to get things done.**

ManyOne should also avoid repeating what 2026 exposed. It should not become:

- a firehose of answers that nobody understands
- a benchmark-chasing machine that races people to their own open problems
- a scraper that takes contributors' work without credit
- an unreviewed skill registry that ships stolen credentials
- one agent loaded down with ten thousand tools it never uses

---

## 19. The Larger Vision

Today, humans share knowledge through:

- books
- conversations
- documents
- videos
- communities
- schools
- institutions
- the Internet

AI systems can consume much of this knowledge.

But the process by which humans actually **solve problems** is still fragmented.

ManyOne aims to make that process itself shareable.

A successful solution should not disappear when the task ends.

It should become part of the network.

Over time, ManyOne could accumulate:

> not only what humanity knows, but how humanity knows how to act.

That is **procedural collective intelligence**.

---

## 20. Long-Term Imagination

Imagine asking ManyOne:

> "Build a company that can manufacture this product."

The network could discover and coordinate:

- market research
- product design
- engineering
- supply chains
- manufacturing
- legal work
- finance
- marketing
- operations

Not because one super-agent knows everything.

Because the network already contains millions of specialized capabilities and proven ways of combining them.

Or:

> "Design and produce a film."

Or:

> "Develop a new material."

Or:

> "Restore this ecosystem."

Or:

> "Build a spacecraft."

The complexity of the task does not require one entity to become infinitely intelligent.

It requires the network to become better at **organizing intelligence**.

---

## 21. The Civilizational Idea

Human progress has always depended on accumulated experience.

One generation discovers something.

The next inherits it.

Someone improves it.

Someone combines it with another discovery.

Eventually, something that no individual could have created becomes possible.

ManyOne aims to make that process:

- programmable
- searchable
- executable
- verifiable
- composable
- attributable
- economically sustainable

This is the deeper idea:

> **Civilization is collective intelligence accumulated through time.**

ManyOne attempts to give that collective intelligence a native network.

---

## 22. The North Star

ManyOne should make one thing increasingly true:

> **Every time someone figures out a better way to get something done, the network should make that way available to future participants.**

And the network should reward the people and machines that make that possible, and should make sure that what it spreads is understood, verified and credited, not just produced.

### In one sentence

> **ManyOne is a collective intelligence network where humans and agents turn experience into reusable capability.**

### In three words

> **Many minds. One capability.**

---

## Sources (as of September 2026)

These are the public reports behind §3. The claims about distillation and about who used whose work are **allegations** that the other parties dispute. They are summarized here as reported, not as established fact. The proposal deliberately takes no side between labs, countries or vendors. It uses these cases only to show the pattern.

- NPR, "Mathematicians learn little from AI completing unsolved problem" (Sept 22, 2026): https://www.npr.org/2026/09/22/nx-s1-5968588/openai-navier-stokes-problem-mathematicians-learn-little
- OpenAI, "On the Navier–Stokes Millennium Prize Problem": https://openai.com/index/navier-stokes-solution/
- Nature, "OpenAI claims huge maths breakthrough on a famed 'Millennium Problem'": https://www.nature.com/articles/d41586-026-02842-5
- Fortune, "OpenAI says it cracked Navier-Stokes…" (Sept 8, 2026): https://fortune.com/2026/09/08/openai-says-it-cracked-navier-stokes-math-grand-challenge-buckmaster-accusation-cheating-intimidation-tao-lament/
- T. Tao et al., "A Severe Misalignment of AI in Mathematics" (Sept 11, 2026): https://terrytao.wordpress.com/2026/09/11/a-severe-misalignment-of-ai-in-mathematics/
- Scientific American, "25 winners of math's 'Nobel Prize' decry the AI invasion of their discipline": https://www.scientificamerican.com/article/25-winners-of-maths-nobel-prize-decry-the-ai-invasion-of-their-discipline/
- AI Weekly, "Tao's ICM 2026 essay sets ground rules for AI in mathematics": https://aiweekly.co/alerts/taos-icm-2026-essay-sets-ground-rules-for-ai-in-mathematics
- The Register, "Frontier AI keeps racing despite calls to slow down" (Sept 23, 2026): https://www.theregister.com/ai-and-ml/2026/09/23/frontier-ai-keeps-racing-despite-calls-to-slow-down/5298448
- TechCrunch, "Anthropic details distillation campaigns from Alibaba, Moonshot AI, and DeepSeek" (Sept 10, 2026): https://techcrunch.com/2026/09/10/anthropic-details-distillation-campaigns-from-alibaba-moonshot-ai-and-deepseek/
- CNBC, "Chinese AI labs secretly used millions of Claude exchanges to train their models, Anthropic says" (Sept 11, 2026): https://www.cnbc.com/2026/09/11/chinese-ai-labs-moonshot-deepseek-alibaba-anthropic.html
- CISA advisory AA26-251A: https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-251a
- TechCrunch, "Cloudflare's new policy pushes AI companies to pay for publishers' content" (July 1, 2026): https://techcrunch.com/2026/07/01/cloudflares-new-policy-pushes-ai-companies-to-pay-for-publishers-content/
- Help Net Security, "Malicious AI agent skills can slip past the scanners built to stop them" (July 9, 2026): https://www.helpnetsecurity.com/2026/07/09/malicious-ai-agent-skills-scan/
- "Agent Skill Security: Threat Models, Attacks, Defenses, and Evaluation" (arXiv 2607.13987): https://arxiv.org/pdf/2607.13987
- MCP.Directory, "MCP Context Bloat Fix 2026 (Tool Search)": https://mcp.directory/blog/mcp-context-bloat-fix-2026-tool-search-code-mode-progressive-disclosure
- Fortune, "Anthropic to pay authors $1.5 billion over pirated books used to train Claude" (July 21, 2026): https://fortune.com/2026/07/21/anthropic-copyright-settlement-authors/
- Gizmodo, "In the Wild West of AI, Everybody Is Accusing Everybody Else of Theft": https://gizmodo.com/in-the-wild-west-of-ai-everybody-is-accusing-everybody-else-of-theft-2000810803
- Business Chief, "Microsoft's Nadella Hits Out at AI Rivals Over Distillation": https://businesschief.com/news/microsoft-ceo-criticises-anthropic-and-ai-model-makers
- Just Security, "The Case for Imposing Costs on China's AI Distillation Campaigns" (the opposing view): https://www.justsecurity.org/134124/costs-china-ai-distillation/
