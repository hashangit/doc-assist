---
name: pm-strategy-docs
description: Create Product Management strategy and planning documents including Product Vision (long-term direction, 3-5 year outlook), Product Strategy (market segments, competitive differentiation), Product Roadmap (timeline, quarterly themes, priorities), and OKRs/KPIs (measurable goals, success metrics). Use when user asks for "product vision", "strategy document", "roadmap", "OKRs", "KPIs", "goals framework", "strategic planning", "quarterly planning", or "success metrics".
---

# PM Strategy Documents

Create strategic product documents that define long-term direction and measurable goals.

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
- Use kebab-case for filenames (e.g., `product-vision.md`, `okrs-q1-2024.md`)
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Document Types

### Product Vision

Long-term aspirational direction (3-5 years). Answers "Where are we going?"

**Structure:**
```markdown
# [Product Name] Vision

## North Star
[One sentence describing the ultimate goal]

## World We're Building
[2-3 paragraphs describing the future state when we succeed]

## For [Target Users]
[Who we serve and how their lives improve]

## We Believe
[3-5 core beliefs that guide decisions]

## Success Looks Like
[Concrete outcomes in 3-5 years]
```

**Key elements:**
- Inspirational but grounded
- Customer-centric language
- Differentiated from competitors
- Guides decision-making

### Product Strategy

How to achieve the vision. Answers "How do we win?"

**Structure:**
```markdown
# [Product Name] Strategy

## Strategic Intent
[Clear statement of competitive position]

## Target Market
- Primary segment: [description, size]
- Secondary segment: [description, size]
- Jobs-to-be-Done: [key jobs]

## Competitive Differentiation
| Dimension | Us | Competitor A | Competitor B |
|-----------|-----|--------------|--------------|
| [Factor 1] | [Advantage] | [State] | [State] |

## Strategic Pillars
1. [Pillar 1]: [Description]
2. [Pillar 2]: [Description]
3. [Pillar 3]: [Description]

## Key Initiatives
- [Initiative 1]: [Expected impact]
- [Initiative 2]: [Expected impact]

## Success Metrics
- [Metric 1]: [Target]
- [Metric 2]: [Target]
```

### Product Roadmap

Timeline of features and releases. Answers "When are we building what?"

**Structure:**
```markdown
# [Product Name] Roadmap

## Strategic Themes
- Q1: [Theme] - [Why this matters]
- Q2: [Theme] - [Why this matters]
- Q3: [Theme] - [Why this matters]
- Q4: [Theme] - [Why this matters]

## Now (0-3 months)
| Item | Status | Owner | Impact |
|------|--------|-------|--------|
| [Feature 1] | [Status] | [Name] | [High/Med/Low] |

## Next (3-6 months)
| Item | Dependencies | Risk |
|------|--------------|------|
| [Feature 2] | [Dependency] | [Risk level] |

## Later (6-12 months)
- [Feature 3] - [Rationale for deferral]

## Key Milestones
- [Date]: [Milestone] - [Significance]
```

**Roadmap types by audience:**
- **Executive**: Strategic themes, major milestones, business outcomes
- **Engineering**: Detailed features, dependencies, technical requirements
- **Sales/Customer**: Benefits-focused, no internal details, flexible dates

### OKRs (Objectives and Key Results)

Measurable goals framework. Answers "How do we measure success?"

**Structure:**
```markdown
# [Team/Product] OKRs - [Quarter/Year]

## Objective 1: [Inspirational, qualitative goal]
**Key Results:**
1. KR1: [Specific metric] from [baseline] to [target] by [date]
2. KR2: [Specific metric] from [baseline] to [target] by [date]
3. KR3: [Specific metric] from [baseline] to [target] by [date]

**Initiatives:**
- [Initiative supporting KR1]
- [Initiative supporting KR2]

## Objective 2: [Inspirational, qualitative goal]
...
```

**OKR best practices:**
- Objectives: Qualitative, inspirational, 3-5 per quarter
- Key Results: Quantitative, measurable, 2-5 per objective
- 70% achievement = success (set ambitious goals)
- Review weekly, grade at quarter end

**Common metric types:**
- Growth: Users, revenue, market share
- Engagement: DAU/MAU, time spent, actions
- Quality: NPS, CSAT, bug rates
- Efficiency: CAC, LTV, conversion rates

## Quick Reference

| Document | Time Horizon | Audience | Update Frequency |
|----------|-------------|----------|-----------------|
| Vision | 3-5 years | All stakeholders | Annually |
| Strategy | 1-2 years | Leadership, teams | Quarterly |
| Roadmap | 6-12 months | Teams, stakeholders | Monthly |
| OKRs | Quarterly | Teams, individuals | Weekly |
