# Novelty Detection and Learning Specification
This specification describes the mechanisms by which Llaminated system and its agents observe and learn from novelty.

The concept is that novelty is a state where the system has no comprehensive model of response for a new observation. The agents must sort this state, determine its reliability, and store a reinforced lesson.

## Principles

- Novelty Detection: when the system cannot predict next-step behaviour from current state, it marks an observation as "novel".
- Agent Deliberation: multiple agents report their observations, negotiate descriptions, and write lessons to a common ledger.
- Reinforcement: agents arranged in pairs remind one another when one loses focus or memory.
- Attention: the novelty layer raises weight of activation and resources for the absent field.
- Learning: reflective analysis and lesson recording results in reinforcement of correlations.