---
name: docassist
description: Your intelligent guide for creating Product Management and Marketing documents. Use as the primary entry point via /docassist to get help choosing the right document, understanding what document fits your scenario, or navigating the document collection. Triggers on "which document", "what document should I use", "help me choose document", "document for [scenario]", or when unsure which document skill to use.
---

# Doc Assist

Your intelligent guide for choosing and creating the right PM or Marketing document.

## How to Use

**Simply describe what you're trying to do and I'll guide you to the right document.**

Examples of what you can ask:
- "I'm launching a new feature, what documents do I need?"
- "Help me create a PRD"
- "I need to define our product's market position"
- "What's the best document for quarterly planning?"
- "I'm doing user research, how should I document findings?"

## Quick Decision Tree

```
What are you trying to do?

├── Define long-term direction or goals?
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

### "I'm doing user/customer research"
| Need | Document | Command |
|------|----------|---------|
| Create user archetypes | User Personas | `/pm-discovery-docs` |
| Map user experience | Customer Journey Map | `/pm-discovery-docs` |
| Understand motivation | JTBD | `/pm-discovery-docs` |
| Document findings | User Research Report | `/pm-research-docs` |
| Tell success story | Case Study Brief | `/marketing-content-docs` |

### "I'm doing strategic planning"
| Need | Document | Command |
|------|----------|---------|
| Set direction | Product Vision | `/pm-strategy-docs` |
| Plan approach | Product Strategy | `/pm-strategy-docs` |
| Set timeline | Product Roadmap | `/pm-strategy-docs` |
| Set goals | OKRs | `/pm-strategy-docs` |

### "I'm enabling sales"
| Need | Document | Command |
|------|----------|---------|
| Product overview | Product Datasheet | `/marketing-launch-docs` |
| Beat competitors | Competitor Battlecard | `/marketing-content-docs` |
| Guide demos | Demo Script | `/bridge-docs` |
| Full enablement | Sales Enablement Kit | `/marketing-launch-docs` |

## By Role

| Role | Go-To Commands |
|------|---------------|
| **Product Manager** | `/pm-strategy-docs`, `/pm-discovery-docs`, `/bridge-docs` |
| **Product Marketing** | `/marketing-positioning-docs`, `/marketing-launch-docs` |
| **Content Marketer** | `/marketing-content-docs` |
| **Sales Enablement** | `/marketing-launch-docs`, `/marketing-content-docs` |
| **UX Researcher** | `/pm-discovery-docs`, `/pm-research-docs` |

## Document Reference

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

### Cross-Functional

| Skill | Documents | When to Use |
|-------|-----------|-------------|
| `/bridge-docs` | Product Brief, Release Notes, FAQ, Demo Script | Documents for both PM & Marketing |

## Quick Help

**Just tell me what you're working on and I'll recommend the right document:**

- "I need to write a [specific document]"
- "I'm [doing something], what document should I use?"
- "Help me with [business scenario]"
- "What's the difference between [doc A] and [doc B]?"
