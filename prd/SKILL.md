---
name: prd
description: Create a Product Requirements Document (PRD) with detailed feature specifications, user stories, and acceptance criteria. Use when user asks for "PRD", "product requirements document", "feature spec", or "requirements document".
---

# Product Requirements Document (PRD)

Define what to build with detailed specifications.

## Document Creation Workflow

### Step 1: Setup Directory Structure
Create the doc-assist folder structure in the project root if it doesn't exist:
```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

### Step 2: Generate Document
### Step 3: Preview for User
### Step 4: Confirm and Save
**Save to:** `doc-assist/product-management/prd-[feature-name].md`

## Template

```markdown
# PRD: [Feature/Product Name]

## Document Info
- **Status:** [Draft/In Review/Approved]
- **Author:** [Name]
- **Created:** [Date]
- **Last Updated:** [Date]

## Problem Statement
[What problem are we solving? Why does it matter?]

## Goals & Non-Goals
### Goals
1. [Goal 1]
2. [Goal 2]

### Non-Goals
1. [What we're explicitly not doing]
2. [What's out of scope]

## User Stories

### Epic: [Epic Name]
**As a** [user type]
**I want** [action]
**So that** [benefit]

#### Story 1: [Story Name]
**As a** [user type]
**I want** [action]
**So that** [benefit]

**Acceptance Criteria:**
- [ ] Given [context], when [action], then [outcome]
- [ ] Given [context], when [action], then [outcome]

**Priority:** [P0/P1/P2]
**Story Points:** [Estimate]

## Functional Requirements
| ID | Requirement | Priority | Status |
|----|-------------|----------|--------|
| FR-001 | [Requirement] | Must/Should/Nice | [Status] |

## Non-Functional Requirements
| ID | Requirement | Metric | Target |
|----|-------------|--------|--------|
| NFR-001 | Performance | Response Time | < 200ms |
| NFR-002 | Availability | Uptime | 99.9% |

## Technical Considerations
[Architecture, dependencies, constraints]

## UI/UX Requirements
[Wireframes, mockups, interaction patterns]

## Success Metrics
| Metric | Current | Target | Timeline |
|--------|---------|--------|----------|
| [Metric] | [Value] | [Value] | [When] |

## Timeline
| Phase | Dates | Deliverables |
|-------|-------|--------------|
| Design | [Dates] | [Deliverable] |
| Build | [Dates] | [Deliverable] |
| Launch | [Dates] | [Deliverable] |

## Risks
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk] | H/M/L | H/M/L | [Plan] |

## Open Questions
| Question | Owner | Due Date | Status |
|----------|-------|----------|--------|
| [Question] | [Name] | [Date] | [Open/Resolved] |

## Approval
| Role | Name | Status | Date |
|------|------|--------|------|
| Product | [Name] | [Approved/Pending] | [Date] |
| Engineering | [Name] | [Approved/Pending] | [Date] |
| Design | [Name] | [Approved/Pending] | [Date] |
```
