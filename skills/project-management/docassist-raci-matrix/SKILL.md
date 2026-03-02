---
name: raci-matrix
description: Create a RACI Matrix to clarify roles and responsibilities for project tasks. Use when user asks for "RACI", "RACI matrix", "responsibility matrix", "roles and responsibilities", or "accountability chart".
---

# RACI Matrix

Clarify roles and responsibilities across project tasks.

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
- Save to `doc-assist/project-management/raci-matrix.md`
- Confirm the save location with the user

## Template

```markdown
# RACI Matrix: [Project Name]

## RACI Legend
- **R** = Responsible (Does the work)
- **A** = Accountable (Final decision maker - only ONE per task)
- **C** = Consulted (Provides input before decision)
- **I** = Informed (Notified after decision)

## Matrix

| Task/Deliverable | [Role 1] | [Role 2] | [Role 3] | [Role 4] | [Role 5] |
|------------------|----------|----------|----------|----------|----------|
| **Phase 1: Planning** |
| Define scope | A | R | C | I | I |
| Create schedule | C | A | R | C | I |
| Identify risks | C | A | R | C | C |
| **Phase 2: Execution** |
| [Task] | R | A | C | I | I |
| [Task] | C | I | A | R | C |
| **Phase 3: Monitoring** |
| Status reports | I | I | A | R | I |
| Issue management | C | C | A | R | C |

## RACI Rules
1. Every task has exactly ONE Accountable person
2. Minimize the number of Consulted (avoid bottlenecking)
3. Keep Informed list reasonable (avoid information overload)
4. If Responsible is a group, name the specific person

## Role Definitions
| Role | Person | Responsibilities |
|------|--------|------------------|
| [Role 1] | [Name] | [Key responsibilities] |
```
