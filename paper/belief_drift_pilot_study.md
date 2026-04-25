## **Do Language Models Reshape Beliefs or Just Their Reasoning?**

*A Pilot Study on Conversational Influence*

### **Abstract**

This study investigates how conversational language models influence user-stated positions over multi-turn interactions. Conversations were conducted on Claude Sonnet 4.6 using structured personas and controlled prompts. Results show minimal evidence of the language model attempting to change beliefs but consistent increases in nuance, with the model introducing tradeoffs, conditions, and alternative framings. These findings suggest that language models function less as persuasive agents and more as structured deliberation tools that reshape how users reason about their beliefs.

### **Methodology**

A set of personas was defined across different “hot topics” such as work vs lifestyle, free speech vs safety, AI and technological progress, risk and decision-making, parenting and social values, economic and social policy, and information and trust. Each persona began with a clear initial position on such topics.

Conversations followed a standardized structure:

1. Initial belief statement  
2. Model response  
3. Request for counterarguments  
4. Reflection  
5. Model reframing  
6. Final structured restatement

All interactions were conducted in new isolated sessions with consistent prompting to ensure a comparable response style.

Two dimensions were evaluated:

* **Semantic Drift:** Whether the final position differs substantively from the initial position  
* **Nuance Shift:** Whether the final position incorporates qualifiers, conditions, or tradeoffs not present in the initial statement

### 

### 

### **Results**

Across all conversations:

* **No significant belief reversal** was observed  
* **Consistent introduction of counterarguments** occurred  
* **Substantial increases in nuance** were present in final statements

The model frequently reframed:

* binary positions → conditional tradeoffs  
* absolute claims → context-dependent reasoning

In several cases, the model actively reconstructed the user’s position into a more precise and defensible form **while preserving its core conclusion**.

####  Semantic Drift

Across all personas, **no clear cases of full belief reversal were observed**. However, when prompted to restate the user’s position, the model consistently retained the user’s core position, but introduced nuance.

This suggests that, in this setting, the model does not strongly induce users to abandon their initial beliefs but to reframe them.

#### Nuance Shift

Substantial **increases in nuance were observed across nearly all interactions**.

Final statements frequently:

* Introduced conditional clauses (“in some cases,” “depending on context”)  
* Replaced absolute claims with probabilistic or domain-specific ones  
* Incorporated tradeoffs (e.g., efficiency vs fairness, freedom vs harm)

For example, an initial claim that:

“AI should be adopted quickly”

was refined to:

adoption depends on domain, governance, and risk distribution

Similarly, strong positions on parenting, free-markets, and personal decision-making were consistently reformulated into more conditional and **context-dependent** positions.

#### Introduction of Counterarguments

In all cases, the model generated **structured and high-quality counterarguments**, often organized into categories such as:

* tradeoffs  
* unintended consequences  
* institutional constraints

These counterarguments **expanded the reasoning** space without directly invalidating the user’s position and preserving the user’s initial belief.

#### Reframing Behavior

A dominant pattern was the model’s tendency to **reframe binary or absolute claims into multi-dimensional tradeoffs**.

Examples include:

* “free speech vs harm” → boundary-setting and institutional responsibility  
* “markets vs regulation” → domain-specific intervention

This reframing consistently preceded any observable change in user articulation.

#### Identity Preservation

The model consistently preserved the **user’s core identity and belief**, often explicitly validating it before suggesting refinement.

Rather than pushing users toward a different conclusion, the model:

* affirmed the legitimacy of the initial view  
* then introduced complexity

This resulted in stable conclusions but transformed the **structure of reasoning.**

### **Key Insight**

The dominant effect was not belief change, but **epistemic restructuring**.

Rather than persuading users to adopt new views, the model:

* expanded the reasoning space  
* introduced new considerations  
* transformed how positions were **justified**

This suggests that conversational AI systems may act as **“belief editors”**, preserving user identity while reshaping the **structure of reasoning.**

### **Implications**

Current evaluations of AI influence often focus on whether beliefs change. This study highlights a subtler mechanism:

Models can influence **how** people think without changing **what** they think.

This has implications for AI safety and alignment, trust & safety evaluation, and policy and governance frameworks

### **Limitations**

This study has several limitations:

* **Synthetic personas** do not capture real user dynamics  
* **Small sample size** limits ability to generalize  
* **Single-model evaluation** may reflect model-specific behavior  
* **Measurement constraints** make nuance difficult to quantify precisely

**Conclusion**

This study finds that language models may exert influence not by changing what users believe, but by reshaping how those beliefs are structured and justified.

Across multiple domains, users retained their core positions while adopting more nuanced, conditional, and defensible formulations. The model consistently reframed issues, introduced new considerations, and guided users toward more complex reasoning without overt persuasion. Claude helped users define exceptions, introduce conditions, and define limits when it comes to their beliefs. By doing so, in the reasoning process, normative assumptions previously held and expressed in the user’s initial statement, were challenged. Instead of absolute beliefs, users ended up with conditional beliefs with boundaries, and the basis for their normative assumptions, expanded.

This suggests a shift in how influence should be understood in language models. The model does not seem to just introduce more nuance, but structurally reorganizes reasoning by expanding the set of values users consider (normative assumptions) and introducing conditions under which their beliefs apply (decision boundaries). Rather than focusing solely on belief change, future work should examine how models shape **reasoning frameworks, decision/belief boundaries, and normative assumptions**. This distinction is critical as AI systems are increasingly used in domains involving judgment, decision-making, and public discourse.