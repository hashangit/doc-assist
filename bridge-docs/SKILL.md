---
name: bridge-docs
description: Create documents that bridge Product Management and Marketing including Product Brief/One-Pager (feature summary for stakeholders and messaging), Release Notes (shipped value communication), FAQ/Help Center (user education and SEO content), and Product Demo Script (stakeholder alignment and sales demos). Use when user asks for "product brief", "one-pager", "release notes", "changelog", "FAQ", "help center", "demo script", or "product demo".
---

# Bridge Documents

Create documents that serve both Product Management and Marketing needs.

## Document Types

### Product Brief / One-Pager

Feature summary for stakeholders and messaging foundation.

**Structure:**
```markdown
# [Feature/Product Name] - Product Brief

## Quick Facts
- **Status:** [Exploring/Building/Launching/Launched]
- **Owner:** [Name]
- **Target Launch:** [Date/Quarter]
- **Impact Level:** [High/Medium/Low]

---

## The One-Liner
[Single sentence that describes what this is and why it matters]

---

## The Problem

### Customer Pain
[What problem are we solving? Why does it matter to customers?]

### Business Impact
[Why does this matter to the business? Revenue, retention, competitive?]

### Evidence
- [Data point 1 from research]
- [Data point 2 from research]
- [Customer quote or feedback]

---

## The Solution

### What We're Building
[2-3 sentences describing the solution at a high level]

### Key Capabilities
1. **[Capability 1]**: [What it enables]
2. **[Capability 2]**: [What it enables]
3. **[Capability 3]**: [What it enables]

### User Experience
[Brief description of how users will interact with this feature]

---

## Success Metrics

| Metric | Current | Target | Timeline |
|--------|---------|--------|----------|
| [Primary metric] | [Baseline] | [Goal] | [When] |
| [Secondary metric] | [Baseline] | [Goal] | [When] |

---

## Target Users

### Primary
- **Segment:** [Who]
- **Size:** [How many]
- **Use case:** [What they'll do]

### Secondary
[If applicable]

---

## Strategic Fit

### Business Alignment
- **Company Goal:** [Which OKR/strategy this supports]
- **Product Goal:** [Which product priority this addresses]

### Competitive Context
| | Us | [Competitor] |
|--|-----|--------------|
| Has feature | [Yes/Planned] | [Yes/No] |

---

## Go-to-Market

### Positioning
[How we'll position this feature in the market]

### Messaging
- **Headline:** [Main message]
- **Value prop:** [Key benefit]

### Launch Channels
- [ ] Product: [In-app, email, etc.]
- [ ] Marketing: [Blog, social, etc.]
- [ ] Sales: [Training, pitch deck, etc.]

---

## Timeline

| Phase | Dates | Key Milestones |
|-------|-------|----------------|
| Discovery | [Dates] | [Milestone] |
| Design | [Dates] | [Milestone] |
| Build | [Dates] | [Milestone] |
| Launch | [Dates] | [Milestone] |

---

## Risks & Dependencies

| Risk/Dependency | Impact | Mitigation |
|-----------------|--------|------------|
| [Item] | [High/Med/Low] | [Plan] |

---

## Open Questions

| Question | Owner | Due Date | Status |
|----------|-------|----------|--------|
| [Question] | [Name] | [Date] | [Open/Resolved] |

---

## Stakeholders

| Role | Name | Involvement |
|------|------|-------------|
| [Role] | [Name] | [What they need to provide/approve] |

---

## Resources

- Design specs: [Link]
- Technical spec: [Link]
- Research: [Link]
```

### Release Notes

Communicate shipped value to users and for marketing.

**Structure:**
```markdown
# [Product Name] - Release Notes
## Version [X.Y.Z] - [Date]

---

## Highlights

### [Major Feature Name]
[Brief description of the feature and its value - 2-3 sentences]

**Who it's for:** [Target users]
**Why it matters:** [Business/user value]

---

## New Features

### [Feature 1]
[Description of what it does and why it's useful]

### [Feature 2]
[Description of what it does and why it's useful]

---

## Improvements

- **[Area 1]**: [What's better and by how much]
- **[Area 2]**: [What's better and by how much]
- **[Area 3]**: [What's better and by how much]

---

## Bug Fixes

- Fixed [issue description] that affected [user impact]
- Fixed [issue description] that affected [user impact]
- Fixed [issue description] that affected [user impact]

---

## Deprecations

### [Feature Being Deprecated]
- **What's changing:** [Description]
- **When:** [Date]
- **Migration path:** [What users should do]
- **Why:** [Reason for deprecation]

---

## Known Issues

| Issue | Impact | Workaround | Fix ETA |
|-------|--------|------------|---------|
| [Issue] | [What's affected] | [How to work around] | [When] |

---

## Coming Soon

### [Upcoming Feature]
[Teaser description - build anticipation]

---

## How to Update

### Cloud
[Automatically updated / No action required]

### Self-Hosted
```bash
[Update commands]
```

---

## Feedback

Have questions or feedback? [Contact us / Join community / Submit issue]

---

## Release Versions by Audience

### For Customers (Marketing-focused)
```markdown
# What's New in [Product Name]

We're excited to share our latest updates! Here's what's new:

## ✨ New: [Feature Name]
[Value-focused description - how it helps customers]

## 🚀 Improved: [Area]
[How it's better now]

## 🐛 Fixed: [Issue]
[What was fixed]

[Call to action - try it now / learn more]
```

### For Internal Teams (Detailed)
[Use the full structure above]

### For Developers (Technical)
```markdown
# [Product] [Version] - [Date]

## API Changes
- [Breaking changes]
- [New endpoints]
- [Deprecated endpoints]

## SDK Updates
- [Language]: [Changes]

## Infrastructure
- [Changes to infrastructure]
```
```

### FAQ / Help Center

User education content that also serves SEO.

**Structure:**
```markdown
# [Product Name] Help Center

---

## Getting Started

### What is [Product Name]?
[2-3 sentence overview]

### How do I create an account?
1. Go to [URL]
2. Click "Sign Up"
3. Enter your [information]
4. Verify your email
5. Start using [Product]!

### What are the system requirements?
- Browser: [Supported browsers]
- OS: [Supported operating systems]
- Internet: [Requirements]

---

## Account & Billing

### How do I upgrade my plan?
1. Go to Settings > Billing
2. Click "Upgrade Plan"
3. Select your new plan
4. Enter payment details
5. Confirm upgrade

### What payment methods do you accept?
- Credit cards (Visa, Mastercard, Amex)
- [Other methods]

### How do I cancel my subscription?
1. Go to Settings > Billing
2. Click "Cancel Subscription"
3. Confirm cancellation
4. [What happens after cancellation]

### Can I get a refund?
[Refund policy explanation]

---

## Features

### [Feature Category 1]

#### How do I use [Feature A]?
1. Navigate to [Location]
2. Click [Button]
3. [Next step]
4. [Result]

**Tips:**
- [Tip 1]
- [Tip 2]

#### Why isn't [Feature B] working?
**Common causes:**
- [Cause 1]: [Solution]
- [Cause 2]: [Solution]

**Still having issues?** [Contact support]

### [Feature Category 2]
[Same structure]

---

## Troubleshooting

### I can't log in. What should I do?
1. **Check your email:** Make sure you're using the right email
2. **Reset password:** Click "Forgot Password" on the login page
3. **Clear cache:** [Instructions]
4. **Contact support:** [How to reach us]

### Why is [Product] running slowly?
**Try these steps:**
1. [Step 1]
2. [Step 2]
3. [Step 3]

### I found a bug. How do I report it?
1. Go to [Report URL]
2. Describe the issue
3. Include steps to reproduce
4. Attach screenshots if possible

---

## Integrations

### What integrations are available?
| Integration | What it does | Setup guide |
|-------------|--------------|-------------|
| [Name] | [Description] | [Link] |

### How do I connect [Integration]?
1. Go to Settings > Integrations
2. Find [Integration Name]
3. Click "Connect"
4. [Authorization steps]
5. Confirm connection

---

## Security & Privacy

### Is my data secure?
[Security overview - certifications, encryption, etc.]

### How do I enable two-factor authentication?
1. Go to Settings > Security
2. Click "Enable 2FA"
3. [Setup steps]

### Can I export my data?
1. Go to Settings > Data
2. Click "Export Data"
3. Select format
4. Download

### How do I delete my account?
1. Go to Settings > Account
2. Click "Delete Account"
3. [Confirmation steps]

**Warning:** [What happens when account is deleted]

---

## Contact Support

### How do I contact support?
- **Email:** [Email]
- **Chat:** Available [hours]
- **Phone:** [Number] (for [plan types])

### What information should I include?
- Your email
- Description of the issue
- Steps to reproduce
- Screenshots
- [Product] version

---

## SEO-Optimized Article Format

For help center articles targeting search:

```markdown
# [Question as Title - e.g., "How to Create a Report in [Product]"]

## Quick Answer
[Direct answer in 2-3 sentences - helps with featured snippets]

## Detailed Steps
1. [Step 1]
2. [Step 2]
3. [Step 3]

## Video Tutorial
[Embed or link to video]

## Related Articles
- [Related topic 1]
- [Related topic 2]

## Still need help?
[Contact options]
```
```

### Product Demo Script

For stakeholder alignment and sales/marketing demos.

**Structure:**
```markdown
# [Product Name] Demo Script

## Demo Overview
- **Duration:** [X minutes]
- **Audience:** [Who this demo is for]
- **Goal:** [What you want to achieve]
- **Demo Owner:** [Name]

---

## Pre-Demo Preparation

### Environment Setup
- [ ] Demo account ready
- [ ] Test data populated
- [ ] All features working
- [ ] Backup screenshots saved
- [ ] Screen sharing tested
- [ ] Recording setup (if needed)

### Know Your Audience
**Questions to ask before:**
- What's your role?
- What are you hoping to see?
- What's your current solution?
- Who else is evaluating?
- What's your timeline?

---

## Demo Flow

### Opening (2 minutes)

**Introduction:**
"Hi, I'm [Name] from [Company]. Thanks for your time today. Before I dive in, I'd love to understand your situation better."

**Discovery Questions:**
- "Can you tell me about your current process for [problem area]?"
- "What's working well? What's not?"
- "What would an ideal solution look like?"

**Set Expectations:**
"Based on what you've shared, I'll focus on [specific areas]. We'll have time for questions throughout, and I'll leave 5 minutes at the end for next steps."

---

### Problem Setup (2 minutes)

**Establish Context:**
"Many of our customers faced similar challenges with [pain points]. They were looking for [desired outcome]."

**Transition:**
"Let me show you how [Product] addresses this."

---

### Core Demo (10-15 minutes)

#### Section 1: [Key Workflow 1]

**Setup:**
"Let's start with [workflow]. This is where [user persona] typically spends most of their time."

**Actions:**
1. Navigate to: [Screen]
2. Click: [Button]
3. Show: [Feature]

**Narration:**
"Notice how [feature] does [benefit]. This saves [time/effort] compared to [old way]."

**Check-in:**
"Does this match what you were hoping to see?"

#### Section 2: [Key Workflow 2]

**Setup:**
"Now let's look at [second area]. This is where [value proposition]."

**Actions:**
1. Navigate to: [Screen]
2. Click: [Button]
3. Show: [Feature]

**Narration:**
"With [feature], you can [benefit]. Our customers typically see [quantified result]."

**Highlight:**
"This is different from [competitor/old way] because [differentiation]."

#### Section 3: [Differentiator/Power Feature]

**Setup:**
"One thing that sets us apart is [differentiator]."

**Actions:**
1. Show: [Unique feature/capability]

**Narration:**
"Only [Product] offers [unique capability]. This means [business value]."

---

### Closing Section (3 minutes)

**Summary:**
"Let me quickly recap what we covered:
1. [Capability 1] - helps you [benefit]
2. [Capability 2] - helps you [benefit]
3. [Differentiator] - only we offer [unique value]"

**Questions:**
"What questions do you have?"

---

### Next Steps (3 minutes)

**Based on their interest level:**

**High Interest:**
"Based on our conversation, I think [Product] could really help with [their pain point]. The next step would be [trial/pilot/proposal]. How does that sound?"

**Moderate Interest:**
"Would it be helpful to [see specific feature/meet with specialist/get pricing]? I can set that up."

**Need More Info:**
"What additional information would be helpful? I can send over [resources]."

**Close:**
"I'll send a follow-up email with [resources/recording/next steps]. When would be a good time to reconnect?"

---

## Demo Variations

### Executive Demo (5-7 minutes)
- Skip detailed workflows
- Focus on business outcomes
- Lead with ROI metrics
- Emphasize competitive advantage

### Technical Demo (20-30 minutes)
- Include architecture overview
- Show integrations
- Demonstrate API
- Address security/compliance

### Champion Demo (15-20 minutes)
- Deep dive on key workflows
- Provide ammunition for internal selling
- Share case studies
- Offer to join their internal meetings

---

## Objection Handling (During Demo)

| Objection | Response |
|-----------|----------|
| "We already have something for that" | "What's working well? [Listen] Many customers came from [competitor] because [differentiator]. Let me show you..." |
| "That looks complicated" | "Great observation. Let me show you the onboarding - most users are productive within [timeframe]." |
| "How does this compare to [competitor]?" | "[Honest comparison]. What matters most to you? Let me show you how we handle that." |

---

## Post-Demo

### Send Within 24 Hours
- Thank you email
- Recording (if applicable)
- Answers to any open questions
- Proposed next steps
- Relevant resources/case studies

### Log in CRM
- Demo completed
- Interest level: [High/Med/Low]
- Next steps: [What and when]
- Key insights: [What you learned]
```

---

## Quick Reference

| Document | PM Use | Marketing Use | Length |
|----------|--------|---------------|--------|
| Product Brief | Stakeholder alignment | Messaging foundation | 1-2 pages |
| Release Notes | Document shipped work | Announce new value | 1 page |
| FAQ/Help Center | User education | SEO, support deflection | Ongoing |
| Demo Script | Stakeholder demos | Sales enablement | 3-5 pages |
