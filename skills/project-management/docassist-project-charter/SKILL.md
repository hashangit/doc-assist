---
name: project-charter
description: Create a Project Charter document that formally authorizes a project, defines objectives, scope, stakeholders, and success criteria. Use when user asks for "project charter", "charter document", "project authorization", "initiate project", or "formal project document".
---

# Project Charter

Create a formal authorization document that defines the project and its boundaries.

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
Using the template below, create the document with appropriate content based on user input and context.

### Step 3: Preview for User
Display the complete document content to the user in a code block for review.

### Step 4: Confirm and Save
Ask the user: "Does this document meet your expectations? Should I save it?"

**If confirmed:**
- Save to `doc-assist/project-management/project-charter.md`
- Use kebab-case for filenames
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Template

```markdown
# Project Charter: [Project Name]

## Project Information
- **Project Name:** [Name]
- **Project ID:** [Identifier]
- **Sponsor:** [Name]
- **Project Manager:** [Name]
- **Date:** [Date]

## Business Justification
[Why this project is needed - link to strategic objectives]

## Project Objectives
1. [Specific, measurable objective 1]
2. [Specific, measurable objective 2]
3. [Specific, measurable objective 3]

## Scope

### In Scope
- [Deliverable 1]
- [Deliverable 2]
- [Deliverable 3]

### Out of Scope
- [Explicitly excluded item 1]
- [Explicitly excluded item 2]

## Key Deliverables
| Deliverable | Description | Due Date |
|-------------|-------------|----------|
| [Deliverable 1] | [Description] | [Date] |

## High-Level Timeline
| Phase | Duration | Key Milestones |
|-------|----------|----------------|
| [Phase 1] | [Duration] | [Milestone] |

## Budget Summary
- **Total Budget:** $[Amount]
- **Contingency:** $[Amount] ([X]%)

## Key Stakeholders
| Name | Role | Responsibility |
|------|------|----------------|
| [Name] | [Role] | [RACI designation] |

## Risks & Assumptions

### High-Level Risks
| Risk | Impact | Mitigation |
|------|--------|------------|
| [Risk 1] | [H/M/L] | [Strategy] |

### Assumptions
- [Assumption 1]
- [Assumption 2]

## Constraints
- [Constraint 1: Time, budget, resource, or technical]
- [Constraint 2]

## Success Criteria
[How will we know the project succeeded?]

## Approval
| Role | Name | Signature | Date |
|------|------|-----------|------|
| Sponsor | [Name] | | |
| Project Manager | [Name] | | |
```
