---
name: marketing-content-docs
description: Create Marketing content and campaign documents including Content Strategy (pillars, channels, editorial calendar), Campaign Brief (goals, audience, budget, timeline), Competitor Battlecard (feature comparisons, objection handling), and Case Study Brief (customer success story structure). Use when user asks for "content strategy", "editorial calendar", "campaign brief", "battlecard", "competitor battlecard", "case study", "customer story", or "content plan".
---

# Marketing Content Documents

Create content and campaign documents that drive marketing execution.

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
- Save to `doc-assist/marketing/{document-name}.md`
- Use kebab-case for filenames (e.g., `content-strategy.md`, `campaign-brief-q1.md`)
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Document Types

### Content Strategy

Content pillars, channels, editorial calendar.

**Structure:**
```markdown
# [Brand/Product] Content Strategy

## Content Mission
[What content we create, for whom, and why - one sentence]

## Content Pillars
### Pillar 1: [Name]
- **Theme:** [What it covers]
- **Audience:** [Who it's for]
- **Goal:** [What it achieves]
- **Formats:** [Blog, video, podcast, etc.]
- **Frequency:** [How often]

### Pillar 2: [Name]
...

## Target Audience

### Primary Audience
- **Persona:** [Name]
- **Content needs:** [What they're looking for]
- **Preferred channels:** [Where they consume content]
- **Content triggers:** [When they engage]

### Secondary Audience
...

## Channel Strategy

| Channel | Purpose | Content Type | Frequency | KPIs |
|---------|---------|--------------|-----------|------|
| Blog | [Goal] | [Types] | [Cadence] | [Metrics] |
| LinkedIn | [Goal] | [Types] | [Cadence] | [Metrics] |
| Email | [Goal] | [Types] | [Cadence] | [Metrics] |
| YouTube | [Goal] | [Types] | [Cadence] | [Metrics] |

## Content Formats

### Long-Form Content
- Blog posts: [Length, frequency]
- Whitepapers: [Frequency, purpose]
- Case studies: [Frequency, purpose]

### Short-Form Content
- Social posts: [Platform-specific guidelines]
- Email: [Newsletter structure]
- Videos: [Length, style]

## Editorial Calendar

### Monthly Themes
| Month | Theme | Focus | Key Dates |
|-------|-------|-------|-----------|
| [Month] | [Theme] | [Focus area] | [Events/launches] |

### Weekly Content Plan
| Day | Channel | Content Type | Topic | Owner |
|-----|---------|--------------|-------|-------|
| Monday | [Channel] | [Type] | [Topic] | [Name] |

## Content Workflows

### Ideation to Publication
1. **Ideation:** [Process for generating ideas]
2. **Approval:** [Who approves, timeline]
3. **Creation:** [Who creates, timeline]
4. **Review:** [Review process]
5. **Publish:** [Publishing process]
6. **Promote:** [Distribution strategy]

## Content Governance

### Brand Voice
[Link to messaging framework - key points]

### Quality Checklist
- [ ] Aligned with content pillar
- [ ] Targets defined audience
- [ ] Follows brand voice
- [ ] Includes CTA
- [ ] SEO optimized (if applicable)

## Measurement

### Content KPIs
| Metric | Target | Measurement Tool |
|--------|--------|------------------|
| [Metric 1] | [Target] | [Tool] |

### Monthly Review
- Top performing content: [Analysis]
- Underperforming content: [Analysis]
- Recommendations: [Next steps]
```

### Campaign Brief

Goals, target audience, channels, budget, timeline.

**Structure:**
```markdown
# [Campaign Name] Brief

## Campaign Overview
- **Campaign Name:** [Name]
- **Campaign Type:** [Launch/Awareness/Lead Gen/Retention]
- **Owner:** [Name]
- **Status:** [Draft/Approved/In Progress/Complete]

## Business Context
### Background
[Why are we running this campaign? Context and business need]

### Objectives
1. **Primary Objective:** [Specific, measurable goal]
2. **Secondary Objectives:**
   - [Objective 2]
   - [Objective 3]

### Success Metrics
| Metric | Baseline | Target | Measurement Method |
|--------|----------|--------|-------------------|
| [Metric 1] | [Current] | [Goal] | [How measured] |

## Target Audience

### Primary Audience
- **Segment:** [Who]
- **Size:** [How many]
- **Characteristics:** [Key traits]
- **Current behavior:** [What they do now]
- **Desired behavior:** [What we want them to do]

### Secondary Audience
[Same structure as primary]

## Key Messages

### Primary Message
[Main message for this campaign]

### Supporting Messages
1. [Message 1]
2. [Message 2]

### Call to Action
[What we want audience to do]

## Channels & Tactics

| Channel | Tactic | Budget | Expected Reach | KPI |
|---------|--------|--------|----------------|-----|
| [Channel 1] | [Tactic] | $[X] | [Number] | [Metric] |

## Creative Direction

### Campaign Theme
[Overall creative concept]

### Visual Direction
- Style: [Description]
- Colors: [Palette]
- Imagery: [Guidelines]

### Copy Guidelines
- Tone: [For this campaign]
- Key phrases: [Terms to use]
- Terms to avoid: [What not to say]

## Budget

| Category | Amount | % of Total |
|----------|--------|------------|
| Media | $[X] | [%] |
| Creative | $[X] | [%] |
| Production | $[X] | [%] |
| Tools/Tech | $[X] | [%] |
| **Total** | **$[X]** | **100%** |

## Timeline

| Phase | Dates | Activities | Owner |
|-------|-------|------------|-------|
| Planning | [Dates] | [Activities] | [Name] |
| Creative Dev | [Dates] | [Activities] | [Name] |
| Launch | [Dates] | [Activities] | [Name] |
| Active | [Dates] | [Activities] | [Name] |
| Analysis | [Dates] | [Activities] | [Name] |

## Dependencies & Risks

| Dependency/Risk | Impact | Mitigation | Owner |
|-----------------|--------|------------|-------|
| [Item] | [High/Med/Low] | [Plan] | [Name] |

## Approval
| Role | Name | Status | Date |
|------|------|--------|------|
| [Role] | [Name] | [Approved/Pending] | [Date] |
```

### Competitor Battlecard

Feature comparisons, objection handling, win/loss analysis.

**Structure:**
```markdown
# Competitor Battlecard: [Competitor Name]

## Quick Facts
- **Company:** [Name]
- **Founded:** [Year]
- **Headquarters:** [Location]
- **Employees:** [Number]
- **Funding:** [$ Amount]
- **Market Position:** [Leader/Challenger/Niche]

## Overview
### Their Positioning
[How they position themselves - one paragraph]

### Target Market
- Primary: [Who they target]
- Secondary: [Other segments]

### Pricing
| Tier | Price | Features |
|------|-------|----------|
| [Tier] | $[X]/mo | [Key features] |

## Competitive Comparison

### Feature Comparison
| Feature | Us | [Competitor] | Advantage |
|---------|-----|--------------|-----------|
| [Feature 1] | [Yes + details] | [Yes/No/Partial] | [Us/Them/Neutral] |
| [Feature 2] | [Yes + details] | [Yes/No/Partial] | [Us/Them/Neutral] |

### Where We Win
1. **[Advantage 1]:** [Why we're better]
   - Proof point: [Evidence]
   - Talk track: "[What to say]"

2. **[Advantage 2]:** [Why we're better]
   - Proof point: [Evidence]
   - Talk track: "[What to say]"

### Where We Lose
1. **[Their Advantage]:** [Why they win]
   - Counter strategy: "[What to say]"
   - Pivot to: "[Our strength to emphasize]"

### Neutral Areas
[Where we're comparable]

## Objection Handling

| Objection | Response | Supporting Evidence |
|-----------|----------|---------------------|
| "They're cheaper" | "[Response script]" | [Data point] |
| "They have [feature]" | "[Response script]" | [Alternative] |
| "They're bigger/more established" | "[Response script]" | [Proof point] |

## Win/Loss Analysis

### Why We Win Against Them
- [Reason 1]: [% of wins]
- [Reason 2]: [% of wins]

### Why We Lose to Them
- [Reason 1]: [% of losses]
- [Reason 2]: [% of losses]

### Recent Wins
| Customer | Industry | Why They Chose Us |
|----------|----------|-------------------|
| [Name] | [Industry] | [Reason] |

## Talk Tracks

### Opening
"When comparing us to [Competitor], the key difference is..."

### Differentiation
"Unlike [Competitor], we..."

### Closing
"If [specific need] is important to you, our solution is better because..."

## Resources
- Product comparison sheet: [Link]
- Case studies vs. this competitor: [Links]
- Competitive intelligence updates: [Link]

## Last Updated
[Date] - [What changed]
```

### Case Study Brief

Customer success story structure, interview questions.

**Structure:**
```markdown
# Case Study Brief: [Customer Name]

## Project Overview
- **Customer:** [Company Name]
- **Industry:** [Industry]
- **Size:** [Employees/Revenue]
- **Product Used:** [What they bought]
- **Case Study Owner:** [Your Name]
- **Target Publish Date:** [Date]

## Customer Background

### Company Overview
[2-3 sentences about the customer]

### The Team
- **Main Contact:** [Name, Title]
- **Decision Maker:** [Name, Title]
- **User:** [Name, Title] (if different)

## The Story Arc

### Before (The Challenge)
**Business Problem:**
[What problem were they trying to solve?]

**Pain Points:**
- [Pain 1]
- [Pain 2]
- [Pain 3]

**Previous Solution:**
[What were they using before? Why wasn't it working?]

**Impact of Problem:**
[Quantifiable impact - time lost, revenue impact, etc.]

### During (The Solution)
**Why They Chose Us:**
[What made them choose our solution?]

**Implementation:**
[How did the rollout go? Timeline?]

**Features Used:**
- [Feature 1]: [How they use it]
- [Feature 2]: [How they use it]

### After (The Results)
**Quantitative Results:**
| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| [Metric 1] | [Value] | [Value] | [% or Xx] |

**Qualitative Results:**
- [Benefit 1]
- [Benefit 2]

**ROI:**
[Payback period, cost savings, revenue impact]

**Quote:**
> "[Powerful quote about results]" - [Name, Title]

## Interview Plan

### Participants to Interview
1. [Name, Title] - [What they can speak to]
2. [Name, Title] - [What they can speak to]

### Interview Questions
**About the Challenge:**
1. What was happening in your business that made you look for a solution?
2. What were you using before? What wasn't working?
3. How was this problem impacting your team/business?

**About the Selection:**
4. What other solutions did you consider?
5. Why did you choose [our product]?
6. What was the deciding factor?

**About the Results:**
7. How has [our product] changed how your team works?
8. What results have you seen? Can you quantify them?
9. What's been the biggest impact on your business?

**About the Experience:**
10. How was the implementation process?
11. How has the support been?
12. What would you tell others considering [our product]?

## Assets Needed
- [ ] Customer logo (approved for use)
- [ ] Customer photo/headshot
- [ ] Screenshots (if applicable)
- [ ] Data visualization of results
- [ ] Video testimonial (if possible)

## Approvals Required
- [ ] Customer quote approval
- [ ] Customer logo usage approval
- [ ] Internal review
- [ ] Legal review (if needed)

## Distribution Plan
- [ ] Website: [Location]
- [ ] Sales enablement: [Where to share]
- [ ] Social media: [Platform, date]
- [ ] Email: [Campaign]
```

## Quick Reference

| Document | Purpose | Audience | Typical Length |
|----------|---------|----------|----------------|
| Content Strategy | Guide content creation | Marketing team | 5-10 pages |
| Campaign Brief | Plan marketing campaign | Cross-functional | 3-5 pages |
| Competitor Battlecard | Enable sales | Sales team | 2-3 pages |
| Case Study Brief | Plan customer story | Marketing/CS | 2-3 pages |
