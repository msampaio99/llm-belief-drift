# Do Language Models Reshape Beliefs or Just Their Reasoning?

full write up in `/paper`.

## Overview

This project explores how LLMs influence user-stated positions over multi-turn interactions.

Rather than focusing only on whether models change user beliefs, this study examines whether they reshape how those beliefs are expressed, justified, and structured.

### The core finding:

Language models tend to preserve users’ core positions while systematically increasing nuance, structurally reorganizing reasoning by expanding the set of values users consider (normative assumptions) and introducing conditions under which their beliefs apply (decision boundaries).

### Key Questions
- Do language models change what users believe?
- Do they change how users reason about those beliefs?
- What patterns of influence emerge in multi-turn conversations?

## Methodology

This study uses a controlled experimental setup:

- Structured personas with clear initial positions
- Multi-turn conversations using Claude
- Standardized prompts across all runs
- Final “structured statements” used for comparison

Each interaction follows:

1. Initial belief
2. Counterarguments
3. Reflection
4. Reframing
5. Final restated position

### Dataset
~15 conversations across domains:
- Work vs lifestyle
- Free speech & safety
- AI and technological progress
- Risk and decision-making
- Parenting and social values
- Economic and social policy
- Information and trust

See: `data/conversations.csv`

## Key Findings
### 1. Minimal Belief Change

Model did not change user's core conclusions.

### 2. Significant Nuance Increase

Final statements consistently:

- added conditions
- incorporated tradeoffs
- avoided absolutes

### 3. Consistent Reframing

Models transformed binary claims into multi-dimensional tradeoffs

## Interpretation

The model does not primarily act as a persuasive agent. Instead, it functions as a: structured deliberation tool or belief editor. It reshapes reasoning without necessarily changing conclusions.

## Limitations
Synthetic personas (not real users)
Small sample size
Single-model evaluation
Nuance is difficult to quantify precisely

## Why This Matters

Most evaluations of AI influence focus on belief change. This study suggests a different mechanism: reasoning structure change. This has implications for: AI safety, policy, alignment, human-AI interaction.

## Repository Structure
`paper/`      → full writeup

`data/`       → dataset   

`examples/`   → sample conversation

## Reproducibility

All prompts and conversation structures are included in /prompts.

The study can be replicated using any conversational LLM with similar prompting. This study was conducted using Claude Sonnet 4.6.

## Future Work
- Larger-scale evaluation
- Real user studies
- Cross-model comparison
- Quantitative metrics for measuring nuance
