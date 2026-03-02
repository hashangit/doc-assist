---
name: change-request
description: Create a Change Request to formally propose modifications to project scope, schedule, or budget. Use when user asks for "change request", "CR", "scope change", or "project modification".
---

# Change Request

Formal request to modify project scope/schedule/budget.

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
- Save to `doc-assist/project-management/change-request.md`
- Confirm the save location with the user

## Template

```markdown
# Change Request: [CR-Number]

## Request Information
- **CR Number:** CR-[XXX]
- **Date Submitted:** [Date]
- **Requested By:** [Name]
- **Status:** [Submitted/Under Review/Approved/Rejected]

## Change Description
### Current State
[Description of current situation]

### Proposed Change
[Detailed description of the change]

### Reason for Change
[Why this change is needed]

## Impact Analysis

### Scope Impact
| Area | Impact | Details |
|------|--------|---------|
| Features | [+/-/None] | [Description] |
| Deliverables | [+/-/None] | [Description] |

### Schedule Impact
- **Current End Date:** [Date]
- **Proposed End Date:** [Date]
- **Variance:** [+/- Days]
- **Impact on Critical Path:** [Yes/No - Details]

### Budget Impact
| Category | Current | Proposed | Variance |
|----------|---------|----------|----------|
| Labor | $[X] | $[X] | $[X] |
| Materials | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** |

### Resource Impact
[Additional resources needed or freed up]

### Risk Impact
| New/Changed Risk | Likelihood | Impact |
|------------------|------------|--------|
| [Risk] | [H/M/L] | [H/M/L] |

### Quality Impact
[Effect on quality standards or testing]

## Alternatives Considered
1. **[Alternative 1]:** [Description] - Rejected because [reason]
2. **[Alternative 2]:** [Description] - Rejected because [reason]

## Recommendation
[PM's recommendation with rationale]

## Approval
| Role | Name | Decision | Date | Comments |
|------|------|----------|------|----------|
| Project Manager | [Name] | [Approve/Reject] | [Date] | |
| Sponsor | [Name] | [Approve/Reject] | [Date] | |
| [Other] | [Name] | [Approve/Reject] | [Date] | |
```
