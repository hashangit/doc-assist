---
name: opportunity-assessment
description: Create an Opportunity Assessment business case for pursuing a feature or product. Use when user asks for "opportunity assessment", "business case", "opportunity sizing", or "feature business case".
---

# Opportunity Assessment

Build the business case for a feature or product.

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
**Save to:** `doc-assist/product-management/opportunity-assessment.md`

## Template

```markdown
# Opportunity Assessment: [Feature/Product Name]

## Overview
- **Opportunity:** [One-line description]
- **Owner:** [Name]
- **Date:** [Date]
- **Status:** [Exploring/Validating/Approved/Rejected]

## Problem Statement
[What problem does this solve? Why is it worth solving?]

## Opportunity Sizing
### Market Opportunity
- Addressable users: [N]
- Willingness to pay: $[X]/month
- Annual revenue potential: $[X]M

### Internal Impact
- Affected users: [N] ([X]% of user base)
- Projected adoption: [X]% in [timeframe]
- Revenue impact: $[X]M ARR

## Strategic Fit
| Criterion | Assessment | Notes |
|-----------|------------|-------|
| Aligns with vision | [Yes/Partially/No] | [Explanation] |
| Competitive necessity | [Yes/No] | [Explanation] |
| Technical feasibility | [High/Med/Low] | [Explanation] |
| Resource availability | [Yes/Partially/No] | [Explanation] |

## Success Metrics
| Metric | Current | Target | Timeframe |
|--------|---------|--------|-----------|
| [Metric 1] | [Value] | [Value] | [When] |
| [Metric 2] | [Value] | [Value] | [When] |

## Investment Required
| Category | Estimate | Notes |
|----------|----------|-------|
| Engineering | [X weeks] | [Team size] |
| Design | [X weeks] | [Scope] |
| Marketing | $[X] | [Campaign type] |
| Total | [X weeks] | |

## Risk Assessment
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk 1] | H/M/L | H/M/L | [Plan] |

## Alternatives Considered
1. **[Alternative 1]:** [Description] - Rejected because [reason]
2. **[Alternative 2]:** [Description] - Rejected because [reason]

## Recommendation
**[Proceed / Do Not Proceed / Investigate Further]**

**Rationale:** [Why this recommendation]

## Next Steps
- [ ] [Action 1] - Owner: [Name], Due: [Date]
- [ ] [Action 2] - Owner: [Name], Due: [Date]

## Approval
| Role | Name | Decision | Date |
|------|------|----------|------|
| [Role] | [Name] | [Approved/Rejected] | [Date] |
```
