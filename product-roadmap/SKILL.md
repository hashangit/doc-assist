---
name: product-roadmap
description: Create a Product Roadmap showing timeline of features and releases with priorities. Use when user asks for "product roadmap", "roadmap", "release plan", or "feature timeline".
---

# Product Roadmap

Show the timeline of features and releases (6-12 month horizon).

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
**Save to:** `doc-assist/product-management/product-roadmap.md`

## Template

```markdown
# Product Roadmap: [Product Name]

## Roadmap Overview
- **Time Horizon:** [Date Range]
- **Last Updated:** [Date]
- **Owner:** [Name]

## Strategic Themes
| Theme | Objective | Key Results |
|-------|-----------|-------------|
| [Theme 1] | [What] | [KR1, KR2] |

## Now (Current Quarter)
**Theme:** [Theme name]

| Initiative | Status | Owner | Target Date |
|------------|--------|-------|-------------|
| [Initiative 1] | 🟢 In Progress | [Name] | [Date] |

## Next (Next Quarter)
**Theme:** [Theme name]

| Initiative | Status | Owner | Target Date |
|------------|--------|-------|-------------|
| [Initiative 1] | 📋 Planned | [Name] | [Date] |

## Later (Future Quarters)
### Q[X]: [Theme]
- [Initiative 1]
- [Initiative 2]

### Q[Y]: [Theme]
- [Initiative 1]

## Release Timeline
| Release | Date | Key Features | Status |
|---------|------|--------------|--------|
| v[X.Y] | [Date] | [Features] | [Status] |

## Dependencies
| Initiative | Depends On | Impact if Delayed |
|------------|------------|-------------------|
| [Initiative] | [Dependency] | [Impact] |

## Risks
| Risk | Impact | Mitigation | Owner |
|------|--------|------------|-------|
| [Risk] | [H/M/L] | [Plan] | [Name] |

## Change Log
| Date | Change | Reason | Updated By |
|------|--------|--------|------------|
| [Date] | [What] | [Why] | [Name] |
```
