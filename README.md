# Doc Assist

> Your intelligent guide for creating Product Management and Marketing documents with Claude Code.

A collection of Claude Code skills that help you create professional PM and Marketing documents with structured templates, best practices, and expert guidance.

## Quick Start

### Primary Command

```
/docassist
```

This is your main entry point. Use it when you need help choosing the right document or understanding what document fits your situation.

### Examples

```
/docassist I'm launching a new feature, what documents do I need?
/docassist Help me create a PRD for a mobile app
/docassist I need to define our market positioning
/docassist What's the best document for quarterly planning?
```

## Installation

### Option 1: Copy to Claude Code Skills Directory

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/doc-assist.git

# Copy all skills to your Claude Code skills directory
cp -r doc-assist/* ~/.claude/skills/
```

### Option 2: Use as a Claude Code Plugin

Add to your `~/.claude/settings.json`:

```json
{
  "skills": {
    "paths": ["/path/to/doc-assist"]
  }
}
```

## Available Commands

### Meta Command

| Command | Purpose |
|---------|---------|
| `/docassist` | Main entry point - get help choosing the right document |

### Product Management Commands

| Command | Documents | When to Use |
|---------|-----------|-------------|
| `/pm-strategy-docs` | Vision, Strategy, Roadmap, OKRs | Strategic planning, goal setting |
| `/pm-discovery-docs` | PRD, User Stories, JTBD, Personas, Journey Map | Defining what to build |
| `/pm-research-docs` | Market Research, User Research, Opportunity Assessment | Research & validation |

### Marketing Commands

| Command | Documents | When to Use |
|---------|-----------|-------------|
| `/marketing-positioning-docs` | Positioning, Messaging, Value Prop, Brand Guidelines | Defining market position |
| `/marketing-content-docs` | Content Strategy, Campaign Brief, Battlecard, Case Study | Content & campaigns |
| `/marketing-launch-docs` | GTM Strategy, Launch Checklist, Datasheet, Sales Kit | Launch execution |

### Cross-Functional Commands

| Command | Documents | When to Use |
|---------|-----------|-------------|
| `/bridge-docs` | Product Brief, Release Notes, FAQ, Demo Script | Documents for both PM & Marketing |

## Document Reference

### Product Management Documents

#### Strategy & Planning (`/pm-strategy-docs`)

| Document | Purpose | Time Horizon |
|----------|---------|--------------|
| **Product Vision** | Long-term direction, market positioning | 3-5 years |
| **Product Strategy** | How to achieve vision, competitive differentiation | 1-2 years |
| **Product Roadmap** | Timeline of features/releases, priorities | 6-12 months |
| **OKRs** | Measurable goals and success metrics | Quarterly |

#### Discovery & Definition (`/pm-discovery-docs`)

| Document | Purpose |
|----------|---------|
| **PRD** | Detailed feature specs, user stories, acceptance criteria |
| **User Stories** | Individual requirements in "As a... I want... So that..." format |
| **JTBD** | Customer motivations and desired outcomes |
| **User Personas** | Archetypes of target users with goals, pain points |
| **Customer Journey Map** | End-to-end experience across touchpoints |

#### Research & Validation (`/pm-research-docs`)

| Document | Purpose |
|----------|---------|
| **Market Research** | Competitive analysis, market size, trends |
| **User Research Report** | Interview findings, survey results, usability insights |
| **Opportunity Assessment** | Business case for pursuing a feature/product |

### Marketing Documents

#### Positioning & Messaging (`/marketing-positioning-docs`)

| Document | Purpose |
|----------|---------|
| **Positioning Statement** | How product is unique, target market, key benefits |
| **Messaging Framework** | Key messages by audience, tone guidelines |
| **Value Proposition Canvas** | Customer pains/gains mapped to product features |
| **Brand Guidelines** | Visual identity, voice, tone |

#### Content & Campaigns (`/marketing-content-docs`)

| Document | Purpose |
|----------|---------|
| **Content Strategy** | Content pillars, channels, editorial calendar |
| **Campaign Brief** | Goals, audience, channels, budget, timeline |
| **Competitor Battlecard** | Feature comparisons, objection handling |
| **Case Study Brief** | Customer success story structure |

#### Launch & GTM (`/marketing-launch-docs`)

| Document | Purpose |
|----------|---------|
| **GTM Strategy** | Launch plan, pricing, channels, sales enablement |
| **Launch Checklist** | Cross-functional readiness checklist |
| **Product Datasheet** | Feature summary, specs, use cases (1-pager) |
| **Sales Enablement Kit** | Pitch decks, objection handling, demo scripts |

### Bridge Documents (`/bridge-docs`)

Documents that serve both Product Management and Marketing:

| Document | PM Use | Marketing Use |
|----------|--------|---------------|
| **Product Brief** | Feature summary for stakeholders | Messaging foundation |
| **Release Notes** | Communicate shipped value | Market new features |
| **FAQ/Help Center** | User education | SEO content |
| **Demo Script** | Stakeholder alignment | Sales/marketing demos |

## Common Workflows

### New Feature Launch

```
1. /bridge-docs → Product Brief (align stakeholders)
2. /pm-discovery-docs → PRD (define requirements)
3. /marketing-positioning-docs → Positioning Statement
4. /marketing-launch-docs → GTM Strategy
5. /marketing-launch-docs → Launch Checklist
6. /bridge-docs → Release Notes
```

### Market Entry

```
1. /pm-research-docs → Market Research
2. /pm-research-docs → Opportunity Assessment
3. /pm-strategy-docs → Product Vision
4. /pm-strategy-docs → Product Strategy
5. /marketing-positioning-docs → Positioning Statement
```

### Sales Enablement

```
1. /marketing-launch-docs → Product Datasheet
2. /marketing-content-docs → Competitor Battlecard
3. /bridge-docs → Demo Script
4. /marketing-launch-docs → Sales Enablement Kit
```

### User-Centered Design

```
1. /pm-discovery-docs → User Personas
2. /pm-discovery-docs → JTBD
3. /pm-discovery-docs → Customer Journey Map
4. /pm-discovery-docs → PRD (with User Stories)
```

## Usage Examples

### Getting Started

```
You: /docassist I'm a new PM, what documents should I know about?

Claude: Welcome! Here are the essential documents every PM should know...
[Provides guided overview]
```

### Choosing a Document

```
You: /docassist I need to convince leadership to invest in a new feature

Claude: For building a business case, you'll want an Opportunity Assessment.
Let me help you create one...
[Guides through /pm-research-docs]
```

### Creating a Specific Document

```
You: /pm-discovery-docs Help me write a PRD for a mobile payment feature

Claude: I'll help you create a comprehensive PRD. Let me start with the
structure and guide you through each section...
[Provides template and guidance]
```

### Understanding Document Differences

```
You: /docassist What's the difference between Product Vision and Product Strategy?

Claude: Great question!
- Product Vision: WHERE you're going (3-5 year aspiration)
- Product Strategy: HOW you'll get there (competitive approach)
[Detailed explanation]
```

## By Role

### Product Manager

**Most Used:**
- `/pm-discovery-docs` - PRD, User Stories
- `/pm-strategy-docs` - Roadmap, OKRs
- `/bridge-docs` - Product Brief, Release Notes

### Product Marketing Manager

**Most Used:**
- `/marketing-positioning-docs` - Positioning, Messaging
- `/marketing-launch-docs` - GTM Strategy, Datasheet
- `/marketing-content-docs` - Case Study Brief

### Content Marketer

**Most Used:**
- `/marketing-content-docs` - Content Strategy, Campaign Brief
- `/marketing-positioning-docs` - Brand Guidelines

### Sales Enablement

**Most Used:**
- `/marketing-launch-docs` - Sales Enablement Kit, Datasheet
- `/marketing-content-docs` - Competitor Battlecard
- `/bridge-docs` - Demo Script

### UX Researcher

**Most Used:**
- `/pm-discovery-docs` - Personas, Journey Maps
- `/pm-research-docs` - User Research Report

## Tips

1. **Start with `/docassist`** when you're unsure which document you need
2. **Be specific** about your situation for better recommendations
3. **Chain documents** - many workflows use multiple documents in sequence
4. **Customize templates** - adapt structures to your organization's needs

## File Structure

```
doc-assist/
├── README.md                    # This guide
├── docassist/                   # Meta-skill (main entry point)
│   └── SKILL.md
├── pm-strategy-docs/           # Vision, Strategy, Roadmap, OKRs
│   └── SKILL.md
├── pm-discovery-docs/          # PRD, User Stories, JTBD, Personas
│   └── SKILL.md
├── pm-research-docs/           # Market Research, User Research
│   └── SKILL.md
├── marketing-positioning-docs/ # Positioning, Messaging, Brand
│   └── SKILL.md
├── marketing-content-docs/     # Content Strategy, Campaigns
│   └── SKILL.md
├── marketing-launch-docs/      # GTM, Launch, Sales Enablement
│   └── SKILL.md
└── bridge-docs/                # Product Brief, Release Notes, FAQ
    └── SKILL.md
```

## Contributing

Contributions are welcome! To add or improve documents:

1. Fork the repository
2. Make your changes to the relevant SKILL.md
3. Submit a pull request

## License

MIT
