---
name: user-stories
description: Create User Stories with acceptance criteria for agile development. Use when user asks for "user stories", "user story", "agile requirements", or "story writing".
---

# User Stories

Create user stories for agile development.

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
**Save to:** `doc-assist/product-management/user-stories.md`

## Template

```markdown
# User Stories: [Feature/Epic Name]

## Epic Overview
**As a** [user type]
**I want** [high-level goal]
**So that** [business/user value]

---

## Story 1: [Story Title]

**As a** [type of user]
**I want** [action]
**So that** [benefit/value]

### Acceptance Criteria
- [ ] Given [context], when [action], then [outcome]
- [ ] Given [context], when [action], then [outcome]
- [ ] Given [context], when [action], then [outcome]

### Details
- **Priority:** [P0/P1/P2/P3]
- **Story Points:** [1, 2, 3, 5, 8, 13]
- **Epic:** [Epic Name]
- **Sprint:** [Sprint Number]

### Notes
[Additional context, edge cases, dependencies]

---

## Story 2: [Story Title]

**As a** [type of user]
**I want** [action]
**So that** [benefit/value]

### Acceptance Criteria
- [ ] Given [context], when [action], then [outcome]
- [ ] Given [context], when [action], then [outcome]

### Details
- **Priority:** [P0/P1/P2/P3]
- **Story Points:** [Estimate]

---

## Definition of Done
- [ ] Code complete
- [ ] Unit tests pass
- [ ] Code reviewed
- [ ] QA tested
- [ ] Documentation updated
- [ ] Deployed to staging

## Story Map
| Release 1 | Release 2 | Release 3 |
|-----------|-----------|-----------|
| [Story] | [Story] | [Story] |
```
