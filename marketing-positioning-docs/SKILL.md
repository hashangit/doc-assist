---
name: marketing-positioning-docs
description: Create Marketing positioning and messaging documents including Positioning Statement (unique value, target market), Messaging Framework (key messages by audience, tone guidelines), Value Proposition Canvas (pains/gains mapped to features), and Brand Guidelines (visual identity, voice, tone). Use when user asks for "positioning statement", "messaging framework", "value proposition", "brand guidelines", "brand voice", "elevator pitch", or "key messages".
---

# Marketing Positioning Documents

Create positioning and messaging documents that define how your product is perceived in the market.

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
- Use kebab-case for filenames (e.g., `positioning-statement.md`, `messaging-framework.md`)
- Confirm the save location with the user

**If changes needed:**
- Iterate on the content based on feedback
- Show updated version
- Repeat confirmation step

## Document Types

### Positioning Statement

How product is unique, target market, key benefits.

**Structure:**
```markdown
# [Product Name] Positioning Statement

## Core Positioning Statement
For [target customer] who [statement of need/opportunity], [product name] is a [product category] that [key benefit]. Unlike [competitive alternative], our product [primary differentiation].

## Positioning Framework

### For (Target Customer)
- Primary: [Description]
- Secondary: [Description]
- Characteristics: [Key traits]

### Who (Need/Problem)
- Pain point: [What hurts]
- Current solution: [What they use now]
- Frustration: [Why current solutions fail]

### [Product Name] Is (Category)
- Category: [Market category]
- Frame of reference: [How customers should think of us]

### That (Key Benefit)
- Primary benefit: [Main value delivered]
- Supporting benefits:
  1. [Benefit 2]
  2. [Benefit 3]

### Unlike (Competition)
- Direct competitors: [Who]
- Indirect competitors: [Who]
- Status quo: [Doing nothing]

### Our Product (Differentiation)
- Unique capability: [What only we do]
- Evidence: [Proof points]

## Positioning Alternatives

### Option A: [Theme]
For [customer], [product] is [category] that [benefit].

### Option B: [Theme]
For [customer], [product] is [category] that [benefit].

## Tagline Options
1. "[Tagline 1]"
2. "[Tagline 2]"
3. "[Tagline 3]"

## Evidence & Proof Points
| Claim | Evidence | Source |
|-------|----------|--------|
| [Claim 1] | [Data/Quote/Case] | [Where from] |
```

### Messaging Framework

Key messages by audience, tone guidelines, elevator pitches.

**Structure:**
```markdown
# [Product Name] Messaging Framework

## Brand Voice
### Personality Traits
1. [Trait 1]: [How it manifests]
2. [Trait 2]: [How it manifests]
3. [Trait 3]: [How it manifests]

### Tone Spectrum
| We Are | We're Not |
|--------|-----------|
| [Adjective] | [Opposite] |
| [Adjective] | [Opposite] |

### Voice Guidelines
- **Do:** [Examples of on-brand language]
- **Don't:** [Examples of off-brand language]

## Core Messages

### Primary Message
[One sentence that encapsulates the value proposition]

### Supporting Messages
1. **[Message Theme 1]**: [Supporting message]
2. **[Message Theme 2]**: [Supporting message]
3. **[Message Theme 3]**: [Supporting message]

## Messages by Audience

### [Audience 1: e.g., CTOs/Technical Buyers]
**Pain Points:**
- [Pain 1]
- [Pain 2]

**Key Messages:**
1. [Message tailored to this audience]
2. [Message tailored to this audience]

**Objection Handling:**
| Objection | Response |
|-----------|----------|
| "[Objection]" | "[Rebuttal message]" |

### [Audience 2: e.g., CFOs/Economic Buyers]
**Pain Points:**
- [Pain 1]
- [Pain 2]

**Key Messages:**
1. [Message tailored to this audience]
2. [Message tailored to this audience]

## Elevator Pitches

### 30-Second Pitch
[Full pitch script]

### 60-Second Pitch
[Extended pitch script]

### One-Liner
[Single sentence hook]

## Channel-Specific Messaging

### Website Hero
[Headline + subheadline]

### Email Subject Lines
1. "[Subject line 1]"
2. "[Subject line 2]"

### Social Media
- Twitter/X: [280 char message]
- LinkedIn: [Professional message]

## Message Hierarchy
1. **Primary:** [Main message - always lead with this]
2. **Secondary:** [Supporting message - use when space allows]
3. **Tertiary:** [Detailed message - use in long-form content]
```

### Value Proposition Canvas

Customer pains/gains mapped to product features.

**Structure:**
```markdown
# [Product Name] Value Proposition Canvas

## Customer Profile

### Customer Jobs
**Functional Jobs:**
- [Job 1]: [Description]
- [Job 2]: [Description]

**Social Jobs:**
- [How they want to be perceived]

**Emotional Jobs:**
- [How they want to feel]

### Pains
| Pain | Severity | Frequency |
|------|----------|-----------|
| [Pain 1] | [High/Med/Low] | [Daily/Weekly/Monthly] |
| [Pain 2] | [High/Med/Low] | [Daily/Weekly/Monthly] |

**Pain Points Detail:**
- [Detailed description of major pain]

### Gains
| Gain | Importance | Current Satisfaction |
|------|------------|---------------------|
| [Gain 1] | [High/Med/Low] | [Satisfied/Neutral/Unsatisfied] |

**Desired Outcomes:**
- [Outcome 1]: [What success looks like]

## Value Map

### Products & Services
| Offering | Type | Importance to Customer |
|----------|------|----------------------|
| [Feature 1] | Core/Support/Nice-to-have | [High/Med/Low] |

### Pain Relievers
| Our Solution | Pain Addressed | How It Helps |
|--------------|----------------|--------------|
| [Feature/Service] | [Which pain] | [Description] |

### Gain Creators
| Our Solution | Gain Addressed | How It Delivers |
|--------------|----------------|-----------------|
| [Feature/Service] | [Which gain] | [Description] |

## Fit Analysis

### Problem-Solution Fit
| Customer Need | Our Solution | Fit Score (1-5) |
|---------------|--------------|-----------------|
| [Need 1] | [Solution] | [Score] |

### Competitive Comparison
| Gain/Pain | Us | Competitor A | Competitor B |
|-----------|-----|--------------|--------------|
| [Pain 1] | [How addressed] | [How addressed] | [How addressed] |

## Value Proposition Statement
[Product] helps [customer] [achieve gain/avoid pain] by [unique approach].

## Priority Opportunities
| Opportunity | Impact | Effort | Priority |
|-------------|--------|--------|----------|
| [Opportunity 1] | H/M/L | H/M/L | 1-5 |
```

### Brand Guidelines

Visual identity, voice, tone, do's and don'ts.

**Structure:**
```markdown
# [Brand Name] Brand Guidelines

## Brand Overview

### Mission
[What we do and why]

### Vision
[Where we're headed]

### Values
1. **[Value 1]**: [What it means, how it guides behavior]
2. **[Value 2]**: [What it means, how it guides behavior]
3. **[Value 3]**: [What it means, how it guides behavior]

## Brand Voice

### Voice Attributes
| Attribute | Description | Example |
|-----------|-------------|---------|
| [Attribute 1] | [Definition] | "[Example sentence]" |

### Tone by Context
| Context | Tone | Example |
|---------|------|---------|
| Marketing | [Tone] | "[Example]" |
| Support | [Tone] | "[Example]" |
| Error Messages | [Tone] | "[Example]" |

### Writing Guidelines
**Do:**
- [Guideline 1]
- [Guideline 2]

**Don't:**
- [Guideline 1]
- [Guideline 2]

## Visual Identity

### Logo
- Primary logo: [Usage guidelines]
- Minimum size: [Specification]
- Clear space: [Specification]
- Variations: [When to use each]

### Color Palette
| Color | Hex | Usage |
|-------|-----|-------|
| Primary | #[HEX] | [Where to use] |
| Secondary | #[HEX] | [Where to use] |
| Accent | #[HEX] | [Where to use] |
| Background | #[HEX] | [Where to use] |

### Typography
| Use | Font | Weight | Size |
|-----|------|--------|------|
| Headings | [Font] | [Weight] | [Size range] |
| Body | [Font] | [Weight] | [Size range] |

### Imagery
- Photography style: [Description]
- Illustration style: [Description]
- Icon style: [Description]

## Application Examples

### Email Signature
[Template]

### Social Media
- Profile image: [Guidelines]
- Cover image: [Guidelines]
- Post templates: [Guidelines]

### Document Templates
- Presentation: [Guidelines]
- Proposal: [Guidelines]

## Do's and Don'ts

### Logo Usage
| Do | Don't |
|----|-------|
| [Correct usage] | [Incorrect usage] |

### Color Usage
| Do | Don't |
|----|-------|
| [Correct usage] | [Incorrect usage] |

### Copy Examples
| Do | Don't |
|----|-------|
| "[Good copy]" | "[Bad copy]" |
```

## Quick Reference

| Document | Purpose | Audience | Update Frequency |
|----------|---------|----------|------------------|
| Positioning Statement | Define market position | Internal/Partners | Annually or with major pivots |
| Messaging Framework | Guide all communications | Marketing/Sales | Quarterly |
| Value Prop Canvas | Map value to customer needs | Product/Marketing | Per feature/release |
| Brand Guidelines | Maintain brand consistency | All teams | Annually |
