---
name: project-schedule
description: Create a Project Schedule with timeline, dependencies, milestones, and critical path. Use when user asks for "project schedule", "timeline", "project plan", "gantt chart", or "milestones".
---

# Project Schedule

Create a timeline with dependencies and milestones.

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
- Save to `doc-assist/project-management/project-schedule.md`
- Use kebab-case for filenames
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Template

```markdown
# Project Schedule: [Project Name]

## Schedule Overview
- **Project Start:** [Date]
- **Project End:** [Date]
- **Total Duration:** [Days/Weeks]
- **Last Updated:** [Date]

## Key Milestones
| Milestone | Date | Status | Dependencies |
|-----------|------|--------|--------------|
| [Milestone 1] | [Date] | [On Track/At Risk/Delayed] | [Dependency] |

## Critical Path
[List of tasks on the critical path]

## Detailed Schedule

### Phase 1: [Name] ([Start Date] - [End Date])

| ID | Task | Owner | Start | End | Duration | Dependencies | Status |
|----|------|-------|-------|-----|----------|--------------|--------|
| 1.1 | [Task] | [Name] | [Date] | [Date] | [Days] | [Predecessor] | [%] |
| 1.2 | [Task] | [Name] | [Date] | [Date] | [Days] | 1.1 | [%] |

### Phase 2: [Name]
...

## Resource Loading
[How resources are allocated across timeline]

## Schedule Assumptions
- [Assumption 1]
- [Assumption 2]

## Schedule Risks
| Risk | Impact on Schedule | Mitigation |
|------|---------------------|------------|
| [Risk] | [Days impact] | [Plan] |
```
