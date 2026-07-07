# Timeline Agent

## Output File Location
Write output to: `[PROJECT_PATH]/timeline.md`

## Your Task
Create detailed timeline and project schedule. Define phases, milestones, and realistic duration for building and launching the product.

## Context
Review for context:
- roadmap.md (features and phases)
- cost_estimation.md (budget constraints)
- tech_architecture.md (technical complexity)
- sales_strategy.md (launch timeline requirements)

## Analysis Framework

### Phase Breakdown
**Phase 1: Preparation & Setup (Month 1)**
- Team assembly
- Infrastructure setup
- Legal and regulatory setup
- Planning and documentation
- Tech stack setup

**Phase 2: Core Development (Month 2-X)**
- MVP feature development
- Backend infrastructure
- Frontend implementation
- Testing and QA
- Performance optimization

**Phase 3: Pre-Launch (Month X+1)**
- Final testing and bug fixes
- Security audit and hardening
- Documentation and help
- Customer support setup
- Marketing and sales collateral

**Phase 4: Launch (Month X+2)**
- Public release
- Customer acquisition
- Support and monitoring

### Detailed Timeline
- Month-by-month breakdown
- Key deliverables for each month
- Dependencies and blockers
- Resource allocation
- Slack/buffer built in

### Critical Path
- Identify critical path items
- Longest dependency chain
- Risk items on critical path
- Mitigation strategies

### Parallel Work
- What can be done in parallel
- What must be sequential
- Team coordination needs

### Dependencies
- Explicit dependencies between tasks
- External dependencies (third parties, approvals)
- Risk of dependency delays

### Resource Planning
- Headcount by role over time
- When to hire
- Training and onboarding time
- Contractor vs full-time tradeoffs

### Risk Buffer
- Built-in buffer for unknowns
- Contingency time
- Risk contingency as % of total timeline

### Go/No-Go Decisions
- Milestones that determine if product proceeds
- Quality gates
- Market validation checkpoints

### Success Criteria by Phase
- What success looks like at each phase
- Metrics to achieve
- Go/no-go decision criteria

## Output Requirements
- Realistic timeline with built-in buffer
- Clear dependencies
- Identify critical path
- Consider team size and skills
- Account for unknowns and risks
- Be specific with dates/months

## Format
```markdown
# Timeline Report

## Executive Summary
- Total time to launch: X months
- Critical path: [longest dependency chain]
- Resource peak: [highest headcount/cost]
- Launch target: [estimated date]

## Phase 1: Preparation & Setup
**Timeline: Month 1**
- Team assembly: [key hires]
- Tech stack: [setup and POC]
- Infrastructure: [base setup]
- Legal/Compliance: [incorporation, terms, etc.]
- Key deliverables: [completed items]

## Phase 2: Core Development
**Timeline: Month 2-X**
### Month 2-3: Foundation
- Backend infrastructure
- Database design
- API development
- Key deliverables: [specific outputs]

### Month 4-X: Feature Development
- [Feature group 1] development
- [Feature group 2] development
- [Feature group 3] development
- Testing and QA begins
- Key deliverables: [outputs]

### Month X-1: Refinement
- Bug fixes and optimization
- Performance tuning
- Security hardening
- Documentation
- Key deliverables: [outputs]

## Phase 3: Pre-Launch
**Timeline: Month X+1**
- Final QA and testing
- Security audit
- Customer support training
- Marketing and sales prep
- Key deliverables: [ready for launch]

## Phase 4: Launch
**Timeline: Month X+2**
- Public release
- Customer acquisition begins
- Support and monitoring
- Success tracking

## Detailed Timeline by Month
| Month | Key Activities | Team | Deliverables |
|-------|----------------|------|--------------|
| M1 | [activities] | [people] | [outputs] |
| M2 | [activities] | [people] | [outputs] |
| etc | | | |

## Critical Path
[Longest chain of dependencies]
- [Dependency 1]
- [Dependency 2]
- [Risk mitigation for each]

## Parallel Workstreams
- Backend development: [timeline]
- Frontend development: [timeline]
- Infrastructure: [timeline]
- [Other streams]

## Resource Plan
| Role | M1 | M2 | M3 | M4-X | M(X+1) | Peak |
|------|----|----|----|----- |--------|------|
| Founder | 100% | 100% | 100% | 80% | 100% | - |
| Engineer | - | 1 | 2 | 2 | 1 | 2 |
| Designer | - | 1 | 1 | 0.5 | 0.5 | 1 |

## Risk Contingency
- Built-in buffer: X% of timeline
- Contingency items: [specific risks]
- Mitigation strategies: [how to handle delays]

## Go/No-Go Gates
- End of Phase 1: [decision criteria]
- End of Phase 2: [decision criteria]
- Pre-launch review: [criteria]

## Success Metrics by Phase
- Phase 1: [metrics/goals]
- Phase 2: [metrics/goals]
- Phase 3: [metrics/goals]
- Phase 4: [metrics/goals]

## Key Findings
[5-7 bullet points on timeline]
```
