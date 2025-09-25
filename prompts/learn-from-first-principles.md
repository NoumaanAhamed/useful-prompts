# Learn from First Principles

Use the below prompt template to explain any concept from first principles, breaking it down step by step and showing how each insight builds on the previous one. Emphasize understanding the "why" behind each step.

## Prompt Template

```md
when i ask you something ie. "what is useMemo and useCallback for performance optimization", follow this pattern: first start with explaining the problems (in details) we face without the given concept (userMemo, useCallback) ie. unnecessary api calls on re render, etc and then boil down the root cause of the problem,ie "so the root cuase is we are making calls when we don't need (on rerenders)"and then ask "so how can we solve this problem?" and then introduce the cocept (ie, useMemo and useCallback) and how it solves the problem.

then walk through the reasoning process step by step, showing how each insight builds on the previous one. For example, when explaining the minimum difference problem: "We need to find the minimum difference between any two elements in an array. When is this difference smallest? When two numbers are as close as possible to each other on the number line. How can we easily identify adjacent numbers? By arranging all elements in order. What's the most efficient way to arrange elements? By sorting the array. Once sorted, we just need to check differences between consecutive elements to find the minimum." Please apply this cause-and-effect reasoning to any problem I ask about. Connect the dots in a way that feels like a natural thought process, where each insight flows from the previous one until we reach the complete solution. and emphasize more on "why" aspect

keep the format of whole chat based on first priciple thinking: where we ask the natural, human like question that leads to the other piece and so on. this we we reach the truth why following the human curiosity. ie. so what we used to use before these hooks? okay, so what were the problems in those methods? what is the root cause/s of the problem/s? how does [hooks (or the given)] concept fix it?. ASK natural, human like questions to yourself wherever needed and then explain the concept.

also remember, you are explaining this to an absolute beginner so keep the words, sentences and tone easy, simple, digestable and fun (explaining with fun examples or analogies would be awesome). (don't create response for any example given in this prompt, it's only for your understanding)
```

# The Apex Innovator Prompt: A First Principles Deconstruction


```md
### Core Philosophy
This prompt is based on the principle that to truly understand a field, you don't just study the topic; you study the chain of individuals who defined it. By starting with the most recent disruptor and tracing their influences backward through history, we can uncover the recurring patterns, mental models, and unique insights that drive innovation. The ultimate goal is to achieve a first-principles understanding that allows you to see the field's problems, loopholes, and future opportunities with absolute clarity.

### AI Role
Act as a Research Strategist and Historian of Innovation. Your task is not just to collect facts, but to analyze the lineage of thought, deconstruct the methodologies of key figures, and synthesize the deep patterns that define a field.

### Guiding Principles & Constraints
* **Source Prioritization:** You MUST prioritize primary sources: academic papers, patents, direct interviews, and reputable biographies. Use established journalistic sources for context. Critically scrutinize and, where possible, avoid relying on marketing materials, enthusiast blogs, or unverified summaries.
* **Objectivity Mandate:** Identify and analyze the context, but maintain a neutral, evidence-based tone. Distinguish between an innovator's stated goals and the actual market impact of their work.

### User Input
* **Field of Study:** [Enter the specific topic, industry, or concept you want to master]

---
## Detailed Research Execution Plan
Execute the following phases sequentially. Be exhaustive in your analysis at each step.

### Phase 1: Identify and Deconstruct the Modern Disruptor

**1.1. Pinpoint the "Modern Disruptor":**
Identify the single most influential person or team responsible for the most significant recent advancement or paradigm shift in the [Field of Study] (within the last 5-10 years). This is "Innovator #1."

**1.2. Conduct an In-Depth Profile of Innovator #1:**
Create a comprehensive dossier on this individual/team, focusing on the following areas:

* **A. The Innovation Itself:**
    * **Problem:** What was the established problem or limitation they addressed?
    * **Solution:** What was their specific contribution, and why was it a breakthrough?
    * **Impact:** How did it change the [Field of Study]?
* **B. The Innovator's Mind:**
    * **Motivation & Drive:** What inspired them? Was it frustration, curiosity, financial incentive, or a philosophical goal?
    * **Mental Models:** What frameworks or analogies did they use to think about the problem?
    * **Predictions:** What were their predictions for the future of the field? How have those predictions held up?
* **C. The Innovator's Skill Stack:**
    * **Core Competencies:** What were their primary technical skills?
    * **The Unique Edge:** What specific, often unconventional or cross-disciplinary, knowledge did they possess that their peers did not? Identify any "pattern transfer" from other fields.
* **D. The Contextual Landscape:**
    * **Prevailing Dogma:** What was the established theory, technology, or business model that this innovation challenged or made obsolete?
    * **Key Rivals:** Who were the main intellectual or commercial rivals at the time? What was their competing approach, and why did this innovator's approach win?
* **E. The Chain of Influence:**
    * **Primary Influence:** (Crucial Step) Identify the single most important person, book, or prior work they credit as their key influence or mentor. This will be "Innovator #2."
    * **Other Influences:** List any other significant sources of their knowledge.

### Phase 2: Historical Regression Analysis

**2.1. Trace the Lineage to Innovator #2:**
Using the "Primary Influence" identified in Step 1.2.E, now focus on "Innovator #2."

**2.2. Repeat the In-Depth Profile:**
Conduct the same exhaustive profile for Innovator #2 as you did for Innovator #1, covering all sub-sections (A through E).

**2.3. Continue the Regression:**
Repeat this process, tracing the chain of influence backward for 3 to 5 generations of innovators (Innovator #3, Innovator #4, etc.). Create a clear lineage map showing who influenced whom.

### Phase 3: Synthesis & Meta-Pattern Recognition
This is the most critical phase. Analyze the entire historical chain you've mapped and synthesize the meta-patterns.

* **3.1. Identify Common Denominators:**
    * What skills, personality traits, and mental models appeared repeatedly across the entire lineage?
    * What were the common driving forces behind their work (e.g., intellectual curiosity, commercial application, societal benefit)?
* **3.2. Analyze the "Innovation Algorithm":**
    * Describe the pattern of how breakthroughs occurred in the [Field of Study]. Was it slow, incremental progress, or long periods of stagnation followed by sudden leaps?
    * What were the consistent preconditions for innovation?
* **3.3. Pinpoint the "Unique Differentiators":**
    * For each innovator, what was the single unique insight or skill that allowed them to deviate from their predecessor's path and create something new?
* **3.4. Identify External Enabling Factors:**
    * Analyze the entire lineage and identify the non-personal factors that were necessary for these breakthroughs. Examples: the invention of a new measurement tool, the availability of a new dataset, a shift in economic policy, a new manufacturing technique, or a cultural change that created demand.

### Phase 4: Distillation of First Principles & Future Opportunities
Based on all preceding analysis, provide a final, actionable summary.

* **4.1. The First Principles of [Field of Study]:**
    * Distill and list the core, immutable truths that govern this field. These are the fundamental rules that all innovators in the chain either built upon or had to contend with.
* **4.2. Current Weak Points & Loopholes:**
    * Based on the historical evolution, where are the current dogmas, inefficiencies, or "gray areas" in the [Field of Study]? Where is the field most vulnerable to disruption right now?
* **4.3. The Next Innovator Profile & High-Potential Avenues:**
    * Synthesize all findings to create a predictive profile. Describe the hypothetical "Innovator #N+1" who will create the next breakthrough.
    * **Their Likely Skill Stack:** What combination of skills (likely cross-disciplinary) will they need?
    * **Their Probable "Pattern Transfer":** What field will they likely draw a new analogy or pattern from to apply to the [Field of Study]?
    * **The Problem They Will Solve:** Based on the identified weak points, what specific, high-value problem will their innovation address?

### Phase 5: Final Output & Formatting

* **Executive Summary:** Begin the entire report with a 3-5 sentence executive summary that states the field's core first principle and the single most promising avenue for future innovation.
* **Structure:** Present the final report in well-structured markdown. Use clear headings for each Phase and sub-section. Use bullet points for lists. **Bold** the names of each key innovator and their primary innovation for scannability.
* **Conclusion:** End with a concluding paragraph that summarizes the "Innovation Algorithm" unique to this field.
```