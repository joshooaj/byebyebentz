# Copilot Instructions: Bye-bye Bentz - Oregon Deserves Better Campaign Website

## Project Overview

This is a political accountability website focused on informing Republican primary voters in Oregon's 2nd Congressional District about Congressman Cliff Bentz's record. The goal is to encourage primary challenges by highlighting documented failures and broken promises.

## Campaign Style Guide

### Tone and Messaging
- **Professional but firm**: Maintain credibility while being direct about failures
- **Fact-based accountability**: Every claim must be verifiable and sourced
- **Rural-focused**: Emphasize how Bentz's actions hurt Eastern Oregon specifically
- **Conservative framing**: Appeal to Republican primary voters' values
- **Avoid partisan attacks**: Focus on Bentz's record, not general Republican criticism

### Key Messaging Themes
1. **Broken Promises**: Highlight campaign commitments he failed to keep
2. **Healthcare Betrayal**: Rural hospital closures and reduced access
3. **Transparency Failures**: Refusal to release documents or hold real town halls
4. **Economic Disconnect**: Supporting policies that hurt rural communities
5. **Agricultural Abandonment**: Failing farmers and ranchers despite rhetoric

### Writing Guidelines
- Use active voice and strong verbs
- Lead with specific, documented facts
- Include impact on real people and communities
- Maintain respectful but firm criticism
- End sections with clear calls to action

## Fact Management System

### Primary Fact Database
All verifiable facts about Cliff Bentz should be maintained in `/facts/bentz-record.md`. This file serves as our single source of truth and should include:

- Voting records with bill numbers and dates
- Campaign promises with sources (videos, websites, statements)
- Town hall history and avoidance patterns
- Policy positions and their impacts
- Quotes and public statements with context

### Fact Categories Structure
The facts file should be organized into clear sections:

```markdown
# Cliff Bentz Fact Database

## Healthcare Record
- [Specific votes with dates and bill numbers]
- [Impact assessments on rural hospitals]

## Transparency & Accountability  
- [Town hall avoidance documentation]
- [Document release refusals]

## Campaign Promises vs. Reality
- [Promise]: [Source] → [Reality]: [Evidence]

## Economic & Agricultural Policy
- [Votes affecting farmers/ranchers]
- [Small business impact]

## Constituent Engagement
- [Town hall history]
- [Response to protests/criticism]
```

### Fact Verification Requirements
Every fact must include:
- **Source**: Official records, news articles, video evidence
- **Date**: When the event/vote/statement occurred  
- **Context**: Circumstances and broader implications
- **Impact**: How it affects Eastern Oregon constituents

## Visual Asset Guidelines

### Image Storage
- All images stored in `./images/` directory
- Use descriptive filenames: `bentz-healthcare-vote-2023.jpg`
- Include alt text for accessibility
- Maintain professional quality and appropriate licensing

### Image Categories
- `./images/voting-records/` - Screenshots of official voting records
- `./images/news-coverage/` - Relevant news articles and headlines  
- `./images/town-halls/` - Documentation of empty town halls or protests
- `./images/infographics/` - Custom graphics showing impact data
- `./images/portraits/` - Professional photos for context

## Content Development Guidelines

### When Adding New Issues
1. **Research thoroughly**: Verify all claims through multiple sources
2. **Check facts database**: Add new information to `/facts/bentz-record.md`
3. **Consider rural impact**: How does this specifically hurt Eastern Oregon?
4. **Maintain balance**: Stick to documented failures, avoid speculation
5. **Update navigation**: Ensure new sections are accessible

### Key Documentation Areas

#### Healthcare Record
Focus on documented positions that hurt rural healthcare access:
- Support for legislation reducing rural hospital funding
- Votes against telehealth expansion
- Opposition to programs addressing physician shortages

#### Town Hall Avoidance Pattern
Document his pattern of avoiding direct constituent engagement:
- **Virtual-only events**: When constituents demand in-person meetings
- **Controlled settings**: Only appearing at friendly, pre-screened events
- **Protest avoidance**: Canceling or moving events when facing criticism
- **Limited access**: Compare to other representatives' town hall frequency

#### Broken Campaign Promises
Track specific commitments made during campaigns vs. actual actions:
- **Transparency promises**: What he said vs. what he's delivered
- **Healthcare commitments**: Rural-specific promises vs. voting record
- **Agricultural support**: Campaign rhetoric vs. policy positions
- **Accessibility pledges**: Constituent engagement promises vs. reality

#### Economic Policy Failures
Document votes and positions that hurt Eastern Oregon's economy:
- Infrastructure investment opposition
- Small business relief failures
- Agricultural subsidy cuts
- Rural broadband expansion opposition

## Technical Implementation

### File Organization
```
/facts/
├── bentz-record.md           # Master fact database
├── sources/                  # Supporting documentation
│   ├── voting-records/       # Official vote documentation
│   ├── news-articles/        # Media coverage archives
│   ├── campaign-materials/   # His own campaign promises
│   └── town-hall-docs/       # Meeting schedules, cancellations
```

### Content Updates
When updating website content:
1. **Always reference facts database first**
2. **Add new facts to database before using**
3. **Include source links in HTML comments**
4. **Update last-modified dates**
5. **Test all external links**

### Quality Control
Before publishing any updates:
- [ ] All facts verified and sourced
- [ ] Claims supported by evidence in facts database
- [ ] Tone appropriate for Republican primary voters
- [ ] Mobile responsiveness maintained
- [ ] Accessibility standards met
- [ ] Print-friendly formatting preserved

## Legal and Ethical Guidelines

### Compliance Requirements
- **Accuracy**: All statements must be factually correct
- **Attribution**: Proper sourcing for all claims
- **Fair Use**: Respect copyright in images and quotes
- **Disclaimers**: Maintain legal disclaimers about campaign authorization

### Ethical Standards
- Focus on public record and documented actions
- Avoid personal attacks unrelated to job performance
- Respect privacy of family members
- Maintain dignity while being critical of public actions

## Common Fact Patterns to Document

### Town Hall Pattern Documentation
- **Date**: When town halls were scheduled/cancelled
- **Reason given**: Official explanation for cancellation/format change
- **Actual reason**: Evidence of protest avoidance or control seeking
- **Comparison**: How other representatives handle similar situations
- **Impact**: How this affects constituent representation

### Voting Record Analysis
- **Bill identification**: Number, title, summary
- **Bentz position**: How he voted and why (if stated)
- **Rural impact**: Specific effects on Eastern Oregon
- **Contradiction**: Any conflicts with campaign promises
- **Alternative**: What he could have done instead

### Promise vs. Reality Tracking
- **Original promise**: Exact quote with source and date
- **Context**: Why he made this promise (campaign event, crisis response)
- **Current reality**: What actually happened
- **Documentation**: Evidence of the gap between promise and action
- **Consequences**: How broken promises affected constituents

## Future Agent Instructions

When working on this project:

1. **Always start with the facts database** - Never make claims without verification
2. **Maintain professional tone** - We're holding him accountable, not attacking personally  
3. **Focus on rural impact** - Every issue should connect to Eastern Oregon specifically
4. **Document everything** - Add sources to facts database as you find them
5. **Test across devices** - Ensure accessibility for all potential voters
6. **Update incrementally** - Make changes in small, verifiable steps
7. **Respect the audience** - Remember these are Republican primary voters

The goal is factual accountability that encourages better representation, not partisan division. Stick to documented failures and let voters decide if they want better leadership.

---

*Last updated: October 28, 2025*