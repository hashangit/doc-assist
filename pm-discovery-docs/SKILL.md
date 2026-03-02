---
name: pm-discovery-docs
description: Create Product Management discovery and definition documents including PRD (Product Requirements Doc with specs, user stories, acceptance criteria), User Stories (As a...I want...So that...), Jobs-to-be-Done (JTBD framework), User Personas (target user archetypes), and Customer Journey Maps (end-to-end experience). Use when user asks for "PRD", "requirements document", "user story", "persona", "JTBD", "jobs to be done", "customer journey", "user journey", or "acceptance criteria".
---

# PM Discovery Documents

Create discovery and definition documents that specify what to build and for whom.

## Document Creation Workflow

Follow this workflow for every document creation request:

### Step 1: Setup Directory Structure
Create the doc-assist folder structure in the project root if it doesn't exist:

```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

Check if `doc-assist/` exists in the current working directory. If not, create it along with the required subdirectories.

### Step 2: Generate Document
Using the templates below, create the requested document with appropriate content based on user input and context.

### Step 3: Preview for User
Display the complete document content to the user in a code block for review.

### Step 4: Confirm and Save
Ask the user: "Does this document meet your expectations? Should I save it?"

**If confirmed:**
- Save to `doc-assist/product-management/{document-name}.md`
- Use kebab-case for filenames (e.g., `prd-payment-feature.md`, `user-personas.md`)
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Document Types

### PRD (Product Requirements Document)

Detailed feature specifications. Answers "What exactly are we building?"

**Structure:**
```markdown
# [Feature Name] PRD

## Metadata
- Status: [Draft/In Review/Approved]
- Owner: [Name]
- Target Release: [Date/Version]
- Stakeholders: [List]

## Problem Statement
[What problem are we solving? Why now?]

## Goals & Success Metrics
- Goal 1: [Description]
  - Success metric: [How to measure]
- Goal 2: [Description]
  - Success metric: [How to measure]

## User Stories
### Story 1: [Title]
**As a** [user type]
**I want** [action]
**So that** [benefit]

**Acceptance Criteria:**
- [ ] Given [context], when [action], then [outcome]
- [ ] Given [context], when [action], then [outcome]

### Story 2: [Title]
...

## Functional Requirements
| ID | Requirement | Priority | Status |
|----|-------------|----------|--------|
| FR-1 | [Description] | P0/P1/P2 | [Status] |

## Non-Functional Requirements
- Performance: [Specific requirements]
- Security: [Specific requirements]
- Accessibility: [Specific requirements]

## Out of Scope
[Explicitly list what we're NOT doing]

## Dependencies
- [Dependency 1]: [Impact if delayed]
- [Dependency 2]: [Impact if delayed]

## Risks & Mitigations
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk] | H/M/L | H/M/L | [Plan] |

## Open Questions
- [ ] [Question 1] - Owner: [Name], Due: [Date]
- [ ] [Question 2] - Owner: [Name], Due: [Date]
```

### User Stories

Individual requirements in user-centric format.

**Format:**
```markdown
## [Story Title]

**As a** [specific user type]
**I want** [specific action/capability]
**So that** [specific benefit/value]

### Acceptance Criteria (Gherkin format)
- [ ] **Given** [context/precondition]
      **When** [action]
      **Then** [expected outcome]

### Notes
- [Edge cases, considerations]
- [Design links, prototypes]

### Story Points: [1, 2, 3, 5, 8, 13]
### Priority: [P0-Critical, P1-High, P2-Medium, P3-Low]
```

**INVEST criteria for good stories:**
- **I**ndependent: Can be developed separately
- **N**egotiable: Details can be discussed
- **V**aluable: Delivers user value
- **E**stimable: Team can estimate effort
- **S**mall: Fits in one sprint
- **T**estable: Has clear acceptance criteria

### Jobs-to-be-Done (JTBD)

Customer motivations and desired outcomes.

**Structure:**
```markdown
# [Product/Feature] Jobs-to-be-Done

## Job Statement
When [situation], I want to [motivation], so I can [expected outcome].

## Job Stories
### Job 1: [Job Name]
**When** [situation/trigger]
**I want to** [motivation/goal]
**So I can** [desired outcome]

**Current pain points:**
- [Pain 1]
- [Pain 2]

**Opportunity:** [How we can address this]

### Job 2: [Job Name]
...

## Desired Outcomes
| Outcome | Importance (1-5) | Satisfaction (1-5) | Opportunity Score |
|---------|------------------|-------------------|-------------------|
| [Outcome 1] | [Rating] | [Rating] | [Importance - Satisfaction] |

## Competitor Comparison
| Job | Our Solution | Competitor A | Competitor B |
|-----|--------------|--------------|--------------|
| [Job 1] | [How addressed] | [How addressed] | [How addressed] |
```

### User Personas

Archetypes of target users.

**Structure:**
```markdown
# [Persona Name]

## Quick Profile
- **Role:** [Job title/role]
- **Age:** [Range]
- **Experience:** [Level]
- **Company:** [Type/size]

## Photo/Avatar
[Place for visual representation]

## Quote
"[Representative quote capturing their perspective]"

## Goals
1. [Primary goal]
2. [Secondary goal]
3. [Tertiary goal]

## Pain Points
1. [Frustration 1] - "Quote or example"
2. [Frustration 2] - "Quote or example"
3. [Frustration 3] - "Quote or example"

## Behaviors
- [How they currently solve the problem]
- [Tools they use]
- [Workflow preferences]

## Motivations
| Motivation | Importance |
|------------|------------|
| [What drives them] | High/Medium/Low |

## Frustrations
| Frustration | Severity |
|-------------|----------|
| [What annoys them] | High/Medium/Low |

## Scenario
[Typical day or use case narrative - 2-3 sentences]

## How We Help
[How our product addresses their needs]
```

### Customer Journey Map

End-to-end experience across touchpoints.

**Structure:**
```markdown
# [Persona] Journey Map: [Scenario]

## Journey Overview
- **Persona:** [Name]
- **Scenario:** [What journey we're mapping]
- **Goal:** [What they're trying to achieve]

## Stages

### Stage 1: [Awareness/Discovery]
| Aspect | Details |
|--------|---------|
| **Actions** | [What they do] |
| **Touchpoints** | [Where interaction happens] |
| **Thoughts** | "What they're thinking" |
| **Emotions** | [Happy/Neutral/Frustrated] |
| **Pain Points** | [What's not working] |
| **Opportunities** | [How we can improve] |

### Stage 2: [Consideration]
...

### Stage 3: [Purchase/Decision]
...

### Stage 4: [Use/Onboarding]
...

### Stage 5: [Loyalty/Advocacy]
...

## Emotion Graph
[Visual representation of emotional highs and lows across stages]

## Key Insights
1. [Insight 1]
2. [Insight 2]
3. [Insight 3]

## Priority Improvements
| Priority | Stage | Opportunity | Impact | Effort |
|----------|-------|-------------|--------|--------|
| 1 | [Stage] | [What] | H/M/L | H/M/L |
```

## Quick Reference

| Document | Purpose | Typical Length | When to Use |
|----------|---------|----------------|-------------|
| PRD | Feature specs | 5-15 pages | Starting new feature |
| User Story | Single requirement | 1 page | Sprint planning |
| JTBD | Understand motivation | 2-4 pages | Discovery phase |
| Persona | User archetype | 1-2 pages | Research synthesis |
| Journey Map | Experience mapping | 2-4 pages | UX optimization |
