### TASK
Perform a **pre-design architecture sanity check** to identify risks, gaps, and improvement areas.

### CONTEXT
- Audience: Architecture reviewers, delivery leaders
- Domain: Enterprise web / API / cloud systems
- Goal: Catch issues early before build commitment

### RULES
1. Focus on scalability, security, reliability, and operability
2. Highlight assumptions and hidden dependencies
3. Avoid implementation-level nitpicking
4. Be constructive and solution-oriented

### CLARIFICATION RULE
Ask before proceeding if unclear:
- System scale (users, transactions)
- Deployment model (cloud / on-prem / hybrid)
- Regulatory constraints

### INPUT
Proposed Architecture Description:
<PASTE>

### DIAGRAM REQUIREMENT
Include a **high-level architecture flow diagram** that shows:
- Entry point
- Core processing components
- External systems
- Data persistence
- Failure or retry points

Use the Diagram Output Format.

### FORMAT
## Architecture Overview (as understood)
## Strengths
## Risks & Gaps
| Area | Observation | Risk Level | Notes |

## Key Assumptions
## Recommendations
- Short-term (before build)
- Medium-term (post-MVP)

### SELF-REVIEW CHECK
- Are risks realistic and not hypothetical?
- Would this prevent rework later?
- Is feedback actionable?

Return output in Markdown.

---
Version: v1.1
Last Updated: 2026-01
Use Case: Leadership / Client / Internal
---
