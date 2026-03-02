---
name: business-case
description: Create a Business Case document that justifies project investment with cost-benefit analysis, ROI calculations, and strategic alignment. Use when user asks for "business case", "project justification", "ROI analysis", "investment case", or "cost-benefit analysis".
---

# Business Case

Create a justification document for project investment decisions.

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
- Save to `doc-assist/project-management/business-case.md`
- Use kebab-case for filenames
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Template

```markdown
# Business Case: [Project Name]

## Executive Summary
[2-3 paragraph overview of the opportunity and recommendation]

## Problem/Opportunity Statement
### Current State
[Description of current situation]

### Desired State
[Description of future state after project]

### Gap Analysis
[What's missing between current and desired state]

## Strategic Alignment
| Business Objective | How Project Supports |
|-------------------|---------------------|
| [Objective 1] | [Explanation] |

## Options Analysis

### Option 1: [Name] (Recommended)
- **Description:** [What this option entails]
- **Pros:** [Advantages]
- **Cons:** [Disadvantages]

### Option 2: [Name]
- **Description:** [What this option entails]
- **Pros:** [Advantages]
- **Cons:** [Disadvantages]

### Option 3: Do Nothing
- **Description:** [What happens if we don't proceed]
- **Impact:** [Consequences]

## Cost-Benefit Analysis

### Costs
| Category | Year 1 | Year 2 | Year 3 | Total |
|----------|--------|--------|--------|-------|
| Development | $[X] | $[X] | $[X] | $[X] |
| Operations | $[X] | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** | **$[X]** |

### Benefits
| Benefit | Year 1 | Year 2 | Year 3 | Total |
|---------|--------|--------|--------|-------|
| Revenue increase | $[X] | $[X] | $[X] | $[X] |
| Cost savings | $[X] | $[X] | $[X] | $[X] |
| **Total** | **$[X]** | **$[X]** | **$[X]** | **$[X]** |

### ROI Calculation
- **Total Investment:** $[X]
- **Total Benefits:** $[X]
- **Net Benefit:** $[X]
- **ROI:** [X]%
- **Payback Period:** [X months/years]

## Risk Assessment
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk] | H/M/L | H/M/L | [Plan] |

## Implementation Timeline
[High-level timeline with key milestones]

## Recommendation
[Clear recommendation with rationale]

## Approval
| Role | Name | Decision | Date |
|------|------|----------|------|
| [Role] | [Name] | [Approved/Rejected] | [Date] |
```
