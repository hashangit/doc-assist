---
name: docassist
description: Your intelligent guide for creating Product Management, Marketing, and Project Management documents. Use as the primary entry point via /docassist to get help choosing the right document, understanding what document fits your scenario, or navigating the document collection. Triggers on "which document", "what document should I use", "help me choose document", "document for [scenario]", or when unsure which document skill to use.
---

# Doc Assist

Your intelligent guide for choosing and creating the right business document.

## How to Use

**Simply describe what you're trying to do and I'll guide you to the right document.**

Examples of what you can ask:
- "I'm launching a new feature, what documents do I need?"
- "Help me create a project charter"
- "I need to define our product's market position"
- "What's the best document for tracking project risks?"
- "I'm doing user research, how should I document findings?"

## Quick Decision Tree

```
What are you trying to do?

├── Manage a project (planning, execution, delivery)?
│   └──→ Use /project-management-docs
│       ├── Initiation: Charter, Business Case, Stakeholder Register
│       ├── Planning: WBS, Schedule, Budget, Risk Register, RACI, Comm Plan
│       ├── Execution: Status Report, Issue Log, Change Request
│       └── Closure: Lessons Learned, Closure Report
│
├── Define long-term product direction or goals?
│   └──→ Use /pm-strategy-docs
│       ├── Vision (3-5 year direction)
│       ├── Strategy (How to win)
│       ├── Roadmap (Timeline/priorities)
│       └── OKRs (Measurable goals)
│
├── Specify what to build or for whom?
│   └──→ Use /pm-discovery-docs
│       ├── PRD (Feature specifications)
│       ├── User Stories (Requirements)
│       ├── JTBD (Customer motivations)
│       ├── Personas (User archetypes)
│       └── Journey Map (Experience mapping)
│
├── Research market or validate ideas?
│   └──→ Use /pm-research-docs
│       ├── Market Research (Competitive/size/trends)
│       ├── User Research (Interviews/surveys)
│       └── Opportunity Assessment (Business case)
│
├── Define positioning or messaging?
│   └──→ Use /marketing-positioning-docs
│       ├── Positioning Statement (Market position)
│       ├── Messaging Framework (Key messages)
│       ├── Value Prop Canvas (Pains/gains mapping)
│       └── Brand Guidelines (Voice/visual identity)
│
├── Plan content or campaigns?
│   └──→ Use /marketing-content-docs
│       ├── Content Strategy (Pillars/calendar)
│       ├── Campaign Brief (Marketing campaign)
│       ├── Competitor Battlecard (Sales enablement)
│       └── Case Study Brief (Customer story)
│
├── Launch product or enable sales?
│   └──→ Use /marketing-launch-docs
│       ├── GTM Strategy (Launch plan)
│       ├── Launch Checklist (Readiness)
│       ├── Product Datasheet (Feature summary)
│       └── Sales Enablement Kit (Pitch/demo/FAQ)
│
└── Create cross-functional documents?
    └──→ Use /bridge-docs
        ├── Product Brief (Feature summary)
        ├── Release Notes (Shipped value)
        ├── FAQ/Help Center (User education)
        └── Demo Script (Product demos)
```

## By Scenario

### "I'm starting a new project"
| Phase | Document | Command |
|-------|----------|---------|
| Get authorization | Project Charter | `/project-management-docs` |
| Justify investment | Business Case | `/project-management-docs` |
| Map stakeholders | Stakeholder Register | `/project-management-docs` |
| Break down work | WBS | `/project-management-docs` |
| Create timeline | Project Schedule | `/project-management-docs` |
| Identify risks | Risk Register | `/project-management-docs` |
| Clarify roles | RACI Matrix | `/project-management-docs` |

### "I'm running a project"
| Need | Document | Command |
|------|----------|---------|
| Report progress | Status Report | `/project-management-docs` |
| Track problems | Issue Log | `/project-management-docs` |
| Request changes | Change Request | `/project-management-docs` |
| Manage risks | Risk Register | `/project-management-docs` |

### "I'm closing a project"
| Need | Document | Command |
|------|----------|---------|
| Document learnings | Lessons Learned | `/project-management-docs` |
| Final report | Closure Report | `/project-management-docs` |

### "I'm starting a new product/feature"
| Stage | Document | Command |
|-------|----------|---------|
| Validate opportunity | Market Research | `/pm-research-docs` |
| Build business case | Opportunity Assessment | `/pm-research-docs` |
| Align stakeholders | Product Brief | `/bridge-docs` |
| Understand users | User Personas | `/pm-discovery-docs` |
| Define requirements | PRD | `/pm-discovery-docs` |
| Set timeline | Product Roadmap | `/pm-strategy-docs` |

### "I'm preparing for launch"
| Timing | Document | Command |
|--------|----------|---------|
| 3-6 months before | GTM Strategy | `/marketing-launch-docs` |
| 3-6 months before | Positioning Statement | `/marketing-positioning-docs` |
| 2-3 months before | Messaging Framework | `/marketing-positioning-docs` |
| 1-2 months before | Sales Enablement Kit | `/marketing-launch-docs` |
| 2-4 weeks before | Launch Checklist | `/marketing-launch-docs` |
| Launch day | Release Notes | `/bridge-docs` |

## By Role

| Role | Go-To Commands |
|------|---------------|
| **Project Manager** | `/project-management-docs` |
| **Product Manager** | `/pm-strategy-docs`, `/pm-discovery-docs`, `/bridge-docs` |
| **Product Marketing** | `/marketing-positioning-docs`, `/marketing-launch-docs` |
| **Content Marketer** | `/marketing-content-docs` |
| **Sales Enablement** | `/marketing-launch-docs`, `/marketing-content-docs` |
| **UX Researcher** | `/pm-discovery-docs`, `/pm-research-docs` |

## Document Reference

### Project Management (`/project-management-docs`)

| Phase | Documents |
|-------|-----------|
| **Initiation** | Charter, Business Case, Stakeholder Register |
| **Planning** | WBS, Schedule, Budget, Risk Register, RACI, Communication Plan |
| **Execution** | Status Report, Issue Log, Change Request |
| **Closure** | Lessons Learned, Closure Report |

### Product Management

| Skill | Documents | When to Use |
|-------|-----------|-------------|
| `/pm-strategy-docs` | Vision, Strategy, Roadmap, OKRs | Strategic planning |
| `/pm-discovery-docs` | PRD, User Stories, JTBD, Personas, Journey Map | Defining what to build |
| `/pm-research-docs` | Market Research, User Research, Opportunity Assessment | Research & validation |

### Marketing

| Skill | Documents | When to Use |
|-------|-----------|-------------|
| `/marketing-positioning-docs` | Positioning, Messaging, Value Prop, Brand | Defining market position |
| `/marketing-content-docs` | Content Strategy, Campaign Brief, Battlecard, Case Study | Content & campaigns |
| `/marketing-launch-docs` | GTM Strategy, Launch Checklist, Datasheet, Sales Kit | Launch execution |

### Cross-Functional (`/bridge-docs`)

| Documents | PM Use | Marketing Use |
|-----------|--------|---------------|
| Product Brief | Stakeholder alignment | Messaging foundation |
| Release Notes | Shipped value | Feature marketing |
| FAQ/Help Center | User education | SEO content |
| Demo Script | Stakeholder demos | Sales demos |

## Document Creation Workflow

When creating documents, all skills in this collection follow a consistent workflow:

### Step 1: Setup Directory Structure
Each skill automatically creates a `doc-assist/` folder in the project root if it doesn't exist:

```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

### Step 2: Generate Document
Using the appropriate template, the skill creates the requested document with content based on your input.

### Step 3: Preview for User
The complete document content is displayed in a code block for your review.

### Step 4: Confirm and Save
You'll be asked: "Does this document meet your expectations? Should I save it?"

**If confirmed:**
- Document is saved to the appropriate category folder (e.g., `doc-assist/project-management/project-charter.md`)
- Filenames use kebab-case (e.g., `product-brief.md`, `release-notes-v1.2.md`)
- Save location is confirmed with you

**If changes needed:**
- The skill iterates on the content based on your feedback
- Updated version is shown
- Confirmation step repeats

### Save Locations by Category

| Category | Save Folder | Example |
|----------|-------------|---------|
| Project Management | `doc-assist/project-management/` | `project-charter.md` |
| Product Strategy | `doc-assist/product-management/` | `product-roadmap.md` |
| Product Discovery | `doc-assist/product-management/` | `prd.md` |
| Product Research | `doc-assist/product-management/` | `market-research.md` |
| Marketing Positioning | `doc-assist/marketing/` | `positioning-statement.md` |
| Marketing Content | `doc-assist/marketing/` | `campaign-brief.md` |
| Marketing Launch | `doc-assist/marketing/` | `gtm-strategy.md` |
| Bridge Documents | `doc-assist/bridge/` | `product-brief.md` |

## Quick Help

**Just tell me what you're working on and I'll recommend the right document:**

- "I need to write a [specific document]"
- "I'm [doing something], what document should I use?"
- "Help me with [business scenario]"
- "What's the difference between [doc A] and [doc B]?"
