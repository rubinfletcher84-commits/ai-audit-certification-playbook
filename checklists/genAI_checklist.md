# Generative AI Control Checklist

Use this checklist for LLM-based assistants, chatbots, copilots, retrieval-augmented generation systems, agent workflows, and third-party foundation model integrations.

## Objective
Verify that generative AI systems are controlled in a way that reduces unsafe behavior, leakage, over-automation, and misuse.

## Control checks
- [ ] Prompt and system-instruction changes are version controlled
- [ ] Critical prompts or orchestrations require approval before production use
- [ ] Rollback exists for prompt or orchestration changes
- [ ] Retrieval sources are trusted and appropriately scoped
- [ ] Citation or grounding behavior is defined where required
- [ ] Tool, plugin, or agent permissions follow least privilege
- [ ] Destructive or high-risk actions require additional approval
- [ ] Input and output protections exist for prompt injection, sensitive data, and unsafe content
- [ ] Human review is required for high-impact generative AI use cases
- [ ] Model provider terms, retention behavior, and legal implications are documented

## Sample evidence
- Prompt library
- Change tickets
- Evaluation reports
- RAG configuration
- Corpus access rules
- Agent policy documentation
- API permission scopes
- Adversarial test results
- Vendor documentation
- Model cards

## Red flags
- Prompts are changed directly in production with no version history
- Agents can take actions without approval boundaries
- Sensitive data can be entered into tools without restriction
- No one knows what the model provider retains or uses
- High-impact outputs are trusted without human review