# PM & Marketing Document Skills Collection

A collection of Claude Code skills for creating Product Management and Marketing documents.

## Skills Overview

### Product Management Skills

| Skill | Documents | Description |
|-------|-----------|-------------|
| **pm-strategy-docs** | Vision, Strategy, Roadmap, OKRs | Strategic planning documents |
| **pm-discovery-docs** | PRD, User Stories, JTBD, Personas, Journey Maps | Discovery and definition documents |
| **pm-research-docs** | Market Research, User Research, Opportunity Assessment | Research and validation documents |

### Marketing Skills

| Skill | Documents | Description |
|-------|-----------|-------------|
| **marketing-positioning-docs** | Positioning Statement, Messaging Framework, Value Prop Canvas, Brand Guidelines | Positioning and messaging documents |
| **marketing-content-docs** | Content Strategy, Campaign Brief, Competitor Battlecard, Case Study Brief | Content and campaign documents |
| **marketing-launch-docs** | GTM Strategy, Launch Checklist, Product Datasheet, Sales Enablement Kit | Launch and go-to-market documents |

### Bridge Documents

| Skill | Documents | Description |
|-------|-----------|-------------|
| **bridge-docs** | Product Brief, Release Notes, FAQ/Help Center, Demo Script | Documents that serve both PM and Marketing |

### Meta-Skill

| Skill | Description |
|-------|-------------|
| **document-selector** | Guide for choosing the right document type for your needs |

## Installation

Copy the skill directories to your Claude Code skills folder:

```bash
cp -r pm-strategy-docs pm-discovery-docs pm-research-docs marketing-positioning-docs marketing-content-docs marketing-launch-docs bridge-docs document-selector ~/.claude/skills/
```

Or use the package script to create .skill files for distribution.

## Usage

Each skill is automatically triggered based on your request. For example:

- "Create a PRD for a new feature" → `pm-discovery-docs`
- "Help me write a positioning statement" → `marketing-positioning-docs`
- "I need a GTM strategy" → `marketing-launch-docs`
- "What document should I use for..." → `document-selector`

## Document Quick Reference

### By Stage

| Stage | Documents |
|-------|-----------|
| **Strategy** | Vision, Strategy, OKRs |
| **Discovery** | Personas, JTBD, Journey Maps, User Research |
| **Definition** | PRD, User Stories, Product Brief |
| **Launch** | GTM Strategy, Positioning, Messaging, Datasheet |
| **Enablement** | Battlecards, Demo Script, Sales Kit |
| **Communication** | Release Notes, FAQ, Case Studies |

### By Role

| Role | Most Used Documents |
|------|---------------------|
| **Product Manager** | PRD, Roadmap, User Stories, OKRs |
| **PMM** | Positioning, Messaging, GTM Strategy, Datasheet |
| **Content Marketer** | Content Strategy, Campaign Brief, Case Study |
| **Sales Enablement** | Battlecards, Demo Script, Sales Kit |
| **UX Researcher** | Personas, Journey Maps, Research Reports |

## License

MIT
