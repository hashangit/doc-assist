# Doc Assist

> Your intelligent guide for creating Product Management, Marketing, and Project Management documents with Claude Code.

A collection of Claude Code skills that help you create professional documents with structured templates, best practices, and expert guidance.

## Quick Start

### Primary Command

```
/docassist
```

This is your main entry point. Use it when you need help choosing the right document or understanding what document fits your situation.

### Examples

```
/docassist I'm starting a new project, what documents do I need?
/docassist Help me create a project charter
/docassist I need to write a status report
/docassist What's the difference between a PRD and a Product Brief?
```

## Installation

### Option 1: Copy to Claude Code Skills Directory

```bash
# Clone the repository
git clone https://github.com/hashangit/doc-assist.git

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

### Project Management Commands

| Command | Documents | When to Use |
|---------|-----------|-------------|
| `/project-management-docs` | Charter, Business Case, WBS, Schedule, Risk Register, RACI, Status Report, Issue Log, Change Request, Lessons Learned, Closure Report | Managing projects from initiation to closure |

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

### Project Management Documents (`/project-management-docs`)

#### Initiation Phase

| Document | Purpose |
|----------|---------|
| **Project Charter** | Formal authorization, objectives, scope, stakeholders |
| **Business Case** | Justification for the project, ROI analysis |
| **Stakeholder Register** | Who's involved, roles, influence, communication needs |

#### Planning Phase

| Document | Purpose |
|----------|---------|
| **Work Breakdown Structure (WBS)** | Hierarchical decomposition of work |
| **Project Schedule** | Timeline, dependencies, milestones |
| **Budget** | Cost estimates, contingencies |
| **Risk Register** | Risks, likelihood, impact, mitigation |
| **RACI Matrix** | Who is Responsible, Accountable, Consulted, Informed |
| **Communication Plan** | Who needs what info, when, how |

#### Execution & Control Phase

| Document | Purpose |
|----------|---------|
| **Status Report** | Regular progress updates |
| **Issue Log** | Problems, ownership, resolution status |
| **Change Request** | Formal requests to modify scope/schedule/budget |

#### Closure Phase

| Document | Purpose |
|----------|---------|
| **Lessons Learned** | What went well, what didn't, recommendations |
| **Project Closure Report** | Final status, deliverables, handoff |

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

## Document Creation Workflow

When you use any skill in this collection to create a document, it follows a consistent workflow:

### Step 1: Setup Directory Structure

Each skill automatically creates a `doc-assist/` folder in your project root if it doesn't exist:

```
doc-assist/
├── project-management/
├── product-management/
├── marketing/
└── bridge/
```

### Step 2: Generate Document

Using the appropriate template, the skill creates the requested document with content based on your input and context.

### Step 3: Preview for User

The complete document content is displayed in a code block for your review before saving.

### Step 4: Confirm and Save

You'll be asked: **"Does this document meet your expectations? Should I save it?"**

**If confirmed:**
- Document is saved to the appropriate category folder
- Filenames use kebab-case (e.g., `product-brief.md`, `release-notes-v1.2.md`)
- Save location is confirmed with you

**If changes needed:**
- The skill iterates on the content based on your feedback
- Updated version is shown for review
- Confirmation step repeats until you're satisfied

### Save Locations by Document Category

| Category | Save Folder | Example Documents |
|----------|-------------|-------------------|
| Project Management | `doc-assist/project-management/` | `project-charter.md`, `status-report.md` |
| Product Strategy | `doc-assist/product-management/` | `product-vision.md`, `product-roadmap.md` |
| Product Discovery | `doc-assist/product-management/` | `prd.md`, `user-personas.md` |
| Product Research | `doc-assist/product-management/` | `market-research.md`, `user-research-report.md` |
| Marketing Positioning | `doc-assist/marketing/` | `positioning-statement.md`, `messaging-framework.md` |
| Marketing Content | `doc-assist/marketing/` | `content-strategy.md`, `campaign-brief.md` |
| Marketing Launch | `doc-assist/marketing/` | `gtm-strategy.md`, `launch-checklist.md` |
| Bridge Documents | `doc-assist/bridge/` | `product-brief.md`, `release-notes.md` |

### Example Session

```
You: /project-management-docs Create a project charter for a website redesign

Claude: I'll help you create a comprehensive Project Charter. Let me set up the
directory structure and generate the document...

[Creates doc-assist/project-management/ folder if needed]

[Displays complete Project Charter in a code block]

Does this document meet your expectations? Should I save it?

You: Yes, save it

Claude: Saved to `doc-assist/project-management/project-charter.md`
```

## Common Workflows

### Starting a New Project

```
1. /project-management-docs → Project Charter (get authorization)
2. /project-management-docs → Business Case (justify investment)
3. /project-management-docs → Stakeholder Register (map people)
4. /project-management-docs → WBS (break down work)
5. /project-management-docs → Project Schedule (create timeline)
6. /project-management-docs → Risk Register (identify risks)
7. /project-management-docs → RACI Matrix (clarify roles)
```

### Running a Project

```
Weekly:
- /project-management-docs → Status Report
- /project-management-docs → Issue Log (update)

As Needed:
- /project-management-docs → Change Request
- /project-management-docs → Risk Register (update)
```

### Closing a Project

```
1. /project-management-docs → Lessons Learned
2. /project-management-docs → Closure Report
```

### New Feature Launch

```
1. /bridge-docs → Product Brief (align stakeholders)
2. /pm-discovery-docs → PRD (define requirements)
3. /marketing-positioning-docs → Positioning Statement
4. /marketing-launch-docs → GTM Strategy
5. /marketing-launch-docs → Launch Checklist
6. /bridge-docs → Release Notes
```

### Sales Enablement

```
1. /marketing-launch-docs → Product Datasheet
2. /marketing-content-docs → Competitor Battlecard
3. /bridge-docs → Demo Script
4. /marketing-launch-docs → Sales Enablement Kit
```

## By Role

### Project Manager

**Most Used:**
- `/project-management-docs` - All project documents

**Daily/Weekly:**
- Status Report, Issue Log, Risk Register updates

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

## Usage Examples

### Getting Started

```
You: /docassist I'm a new project manager, what documents should I know about?

Claude: Welcome! Here are the essential documents every PM should know...
[Provides guided overview of project management documents]
```

### Choosing a Document

```
You: /docassist I need to track project risks

Claude: For tracking risks, you'll want a Risk Register.
Let me help you create one...
[Guides through /project-management-docs]
```

### Creating a Specific Document

```
You: /project-management-docs Help me write a project charter for a website redesign

Claude: I'll help you create a comprehensive Project Charter. Let me start with the
structure and guide you through each section...
[Provides template and guidance]
```

### Understanding Document Differences

```
You: /docassist What's the difference between Project Charter and Business Case?

Claude: Great question!
- Project Charter: Authorization document that defines WHAT the project is
- Business Case: Justification document that explains WHY we should do it
[Detailed explanation]
```

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
├── project-management-docs/    # Project Management documents
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
