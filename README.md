

# Agent Readiness Review

## Prototype

**[Try the interactive prototype](https://www.figma.com/design/e9jvwp7I1vDMMlxweMQUaI/Agent-Documentation-Validator?node-id=0-1&t=5XZCLQMmauJkrCWz-1)**

This project demonstrates a lightweight workflow for evaluating and improving documentation so it can be reliably used by AI agents — not just humans.

## What this is
An example **agent-readiness review flow** that:
- Identifies where documentation breaks down for automated agents
- Rewrites instructions into clear, executable steps
- Validates the result with a simple, transparent scoring model
- Outputs a final status with concrete next actions

**Example scenario:** Validating a subscription cancellation workflow for autonomous agent execution.

---

## Why this approach matters
Most documentation is written for humans and relies on:
- Screenshots
- Implicit navigation
- Assumed context
- Ambiguous language

These patterns cause agents to fail, loop, or require human intervention.

Agent-ready documentation:
- Reduces task failure rates and support escalations
- Enables reliable automation at scale
- Treats documentation as executable infrastructure, not just reference material
- Makes content reusable across both humans and AI systems

This reframes documentation as part of the system itself, not a passive artifact.

---

## Design decisions
- **Problem → solution comparison** — Issues and fixes are shown clearly, not implied
- **Severity signaling** — Blockers, warnings, and ready states are visually distinct
- **Progressive disclosure** — Summary → detailed issues → fixes → final status
- **Transparent scoring** — Improvements are measurable and explainable (42 → 89 / 100)

---

## Complete Flow


<p align="center">
  <img src="images/agent-documentation-validator-flow.png" width="45%" alt="Agent Documentation Validator end-to-end flow" />
</p>

<p align="center">
  <em>End-to-end validation workflow from input to final status.</em>
</p>



## Key Screens

### Detailed Issue Analysis


<p align="center">
  <img src="images/03%20-%20Detailed%20Issues.png"
       width="40%"
       alt="Detailed issues and recommendations screen" />
</p>
<p align="center">
  <em>Problems identified on the left, actionable fixes on the right.</em>
</p>





### Validation Complete


<p align="center">
  <img src="images/05%20-%20Final%20Status.png"
       width="40%"
       alt="Final validation status screen" />
</p>
<p align="center">
  <em>Final status with measurable improvement and next steps.</em>
</p>



---

## What this project shows
- A practical framework for reviewing documentation for agent readiness
- How small structural changes improve agent reliability
- How validation results can be communicated clearly and transparently
- What a realistic “completion state” looks like in internal tooling

This is a **conceptual reference**, not a production UI — intended for teams designing agent workflows, internal tools, or AI-assisted systems.



