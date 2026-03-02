---
name: pm-research-docs
description: Create Product Management research and validation documents including Market Research (competitive analysis, market size, trends), User Research Report (interview findings, survey results, usability insights), and Opportunity Assessment (business case for features/products). Use when user asks for "market research", "competitive analysis", "user research report", "survey analysis", "usability report", "opportunity assessment", "business case", or "market analysis".
---

# PM Research Documents

Create research and validation documents that inform product decisions with data.

## Document Types

### Market Research

Competitive analysis, market size, and trends.

**Structure:**
```markdown
# [Market/Product] Research Report

## Executive Summary
- Market size: $[X]B (growing [X]% YoY)
- Key finding 1: [Insight]
- Key finding 2: [Insight]
- Recommendation: [Action]

## Market Overview
### Market Size
- TAM (Total Addressable Market): $[X]B
- SAM (Serviceable Addressable Market): $[X]B
- SOM (Serviceable Obtainable Market): $[X]M

### Market Trends
| Trend | Impact | Timeframe | Our Position |
|-------|--------|-----------|--------------|
| [Trend 1] | [High/Med/Low] | [When] | [Leading/Following] |

### Customer Segments
1. **[Segment 1]** ([X]% of market)
   - Characteristics: [Key traits]
   - Needs: [Primary needs]
   - Current solutions: [What they use]

## Competitive Analysis
### Competitor Matrix
| Dimension | Us | [Competitor A] | [Competitor B] | [Competitor C] |
|-----------|-----|----------------|----------------|----------------|
| Pricing | [Model] | [Model] | [Model] | [Model] |
| Target Market | [Who] | [Who] | [Who] | [Who] |
| Key Feature 1 | [Yes/No] | [Yes/No] | [Yes/No] | [Yes/No] |
| Key Feature 2 | [Yes/No] | [Yes/No] | [Yes/No] | [Yes/No] |
| Strengths | [Ours] | [Theirs] | [Theirs] | [Theirs] |
| Weaknesses | [Ours] | [Theirs] | [Theirs] | [Theirs] |

### Feature Comparison
| Feature | Us | Comp A | Comp B | Comp C |
|---------|-----|--------|--------|--------|
| [Feature 1] | [Details] | [Details] | [Details] | [Details] |

### SWOT Analysis (per competitor)
**[Competitor A]**
- Strengths: [What they do well]
- Weaknesses: [Where they struggle]
- Opportunities: [Market gaps they could exploit]
- Threats: [What could hurt them]

## Market Gaps
| Gap | Size | Competition | Opportunity Score |
|-----|------|-------------|-------------------|
| [Gap 1] | [Small/Med/Large] | [Low/Med/High] | [1-10] |

## Recommendations
1. [Recommendation 1] - Priority: High
2. [Recommendation 2] - Priority: Medium
3. [Recommendation 3] - Priority: Low

## Sources
- [Source 1]
- [Source 2]
```

### User Research Report

Interview findings, survey results, usability insights.

**Structure:**
```markdown
# [Research Topic] Report

## Research Overview
- **Objective:** [What we wanted to learn]
- **Method:** [Interviews/Survey/Usability Test/Diary Study]
- **Participants:** [N] users, [segments]
- **Duration:** [Dates]
- **Researcher:** [Name]

## Executive Summary
### Key Findings
1. [Finding 1]
2. [Finding 2]
3. [Finding 3]

### Recommendations
1. [Recommendation 1]
2. [Recommendation 2]

## Participant Profile
| ID | Segment | Role | Experience | Key Characteristic |
|----|---------|------|------------|---------------------|
| P1 | [Segment] | [Role] | [Years] | [Trait] |

## Detailed Findings

### Theme 1: [Theme Name]
**Summary:** [1-2 sentence overview]

**Evidence:**
> "Quote from participant" - P1

> "Another quote" - P3

**Observations:**
- [What we observed]
- [What we observed]

**Implications:**
- [What this means for the product]

### Theme 2: [Theme Name]
...

## Quantitative Data (if survey)
### Question 1: [Question text]
| Response | Count | Percentage |
|----------|-------|------------|
| [Option A] | [N] | [%] |
| [Option B] | [N] | [%] |

**Insight:** [What this tells us]

## Usability Findings (if applicable)
| Task | Success Rate | Avg Time | Errors | Severity |
|------|--------------|----------|--------|----------|
| [Task 1] | [%] | [min] | [N] | [High/Med/Low] |

## Pain Points Ranked
| Pain Point | Frequency | Severity | Action |
|------------|-----------|----------|--------|
| [Pain 1] | [N mentions] | [H/M/L] | [Recommended action] |

## Action Items
| # | Action | Owner | Priority | Status |
|---|--------|-------|----------|--------|
| 1 | [Action] | [Name] | [P1/P2/P3] | [Status] |

## Appendix
- [Links to recordings, transcripts, raw data]
```

### Opportunity Assessment

Business case for pursuing a feature/product.

**Structure:**
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
- Technical feasibility | [High/Med/Low] | [Explanation] |
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

## Quick Reference

| Document | Purpose | Research Type | Typical Length |
|----------|---------|---------------|----------------|
| Market Research | Understand landscape | Secondary research | 10-20 pages |
| User Research Report | Share user insights | Primary research | 5-15 pages |
| Opportunity Assessment | Make investment case | Mixed | 3-5 pages |
