# Rolo Brand Guidelines

Version: 0.1  
Format: Brand guideline style card  
Status: Working draft  
Source basis: Rolo `/design-system` review and product UI patterns

## 1. Brand Essence

### One-line definition

Rolo is a relationship intelligence system that helps people remember, understand, and act on the relationships that matter.

### Brand promise

Rolo gives users a living memory for their network. It captures conversations, open loops, meetings, notes, intros, and follow-ups, then turns that context into timely, useful action.

### Emotional target

Rolo should feel warm, clear, quietly intelligent, and helpful. The user should feel: "I have control again. I know who matters. I know what to do next."

### Product category

Relationship intelligence  
Personal CRM  
Network operating system  
Human-context layer for AI workflows

### What Rolo is

Rolo is a people-forward operating surface for relationship continuity. It is built for founders, operators, students, builders, investors, recruiters, and anyone whose life depends on remembering the right person at the right time.

### What Rolo is not

Rolo should avoid feeling like a cold sales CRM, a noisy task manager, a generic AI assistant, or a luxury dashboard with no operational value. The visual language should stay premium and polished, but the product must always feel useful first.

## 2. Tagline System

### Primary tagline

Remember the people who matter.

### Secondary tagline options

Your relationships, remembered.  
Follow through on the people who matter.  
The relationship layer for your life.  
Know who needs you next.  
The AI that helps you show up.

### Short product description

Rolo helps you remember conversations, follow-ups, open loops, intros, and relationship context, then turns them into timely next actions so important people do not slip through the cracks.

### Launch positioning

Rolo introduces a more human kind of AI: one built around continuity, care, context, and follow-through. Instead of making users manually maintain a giant relationship database, Rolo turns scattered people-context into a living system they can act on.

## 3. Brand Personality

### Core traits

| Trait | Meaning in product |
|---|---|
| Warm | Rolo should feel emotionally intelligent without becoming sentimental. |
| Clear | Every screen should answer: who matters, why now, and what should I do next? |
| Trusted | Signals should feel grounded in concrete context, not vague AI guesses. |
| Light | The product should reduce cognitive load instead of adding more panels and noise. |
| Personal | Real names, photos, notes, and relationship history should stay central. |
| Action-oriented | Every insight should lead toward a useful next step. |

### Tone

Rolo speaks like a trusted advisor who remembers the details. The tone should be direct, kind, specific, and low-drama.

Good Rolo copy:

> Alex has been quiet for 47 days. He still owes you LP intros from the Sequoia dinner. Send a short follow-up before the thread goes cold.

Weak Rolo copy:

> Your relationship with Alex is decaying significantly. Engage to improve relationship health.

### Copy principles

1. Lead with the person.
2. Explain the signal with evidence.
3. Suggest a concrete action.
4. Keep language calm.
5. Avoid overclaiming.
6. Avoid generic AI phrasing.
7. Avoid fake intimacy.

## 4. Visual Identity Card

### Brand feel

Warm intelligence  
Editorial dashboard  
People-first operating console  
Modern relationship memory  
Softly premium, never flashy  
Minimal, but not sterile  
Human, but not cute by default

### Visual keywords

Gold accents  
Soft surfaces  
Ruled sections  
Real portraits  
Status badges  
Relationship health  
Open loops  
Command bands  
Insight rails  
Connected timelines  
Smart groups  
Rarity tiers  
Quiet motion  
Subtle glow

### Visual anti-keywords

Corporate CRM  
Crypto dashboard  
Overly rounded SaaS  
Dense analytics wall  
Floating glass chaos  
Toy-like gamification  
AI slop aesthetic  
Excessive gradients  
Blur-heavy 3D  
Gmail-looking Gmail cards

## 5. Color System

The design system uses semantic CSS tokens and should stay token-driven. Do not hardcode raw colors in product surfaces unless the token set is being defined.

### Accent palette

| Token | Role |
|---|---|
| `--color-gold` | Primary accent, highlights, selected states, person-of-the-day, premium emphasis |
| `--color-blue` | Informational states, links, AI context, system explanation |
| `--color-green` | Growing relationship status, success, positive momentum |
| `--color-rose` | Drifting, error, overdue, emotional urgency |
| `--color-purple` | AI ranking, special intelligence, higher-tier signals |
| `--color-teal` | Secondary freshness, discovery, soft metadata |
| `--color-amber` | Warning, pending prep, cautionary context |
| `--color-pink` | Personal/social warmth, optional expressive moments |

### Soft fills

Use soft fills for badges, tags, status pills, small alerts, and lightweight state indicators.

| Token | Use |
|---|---|
| `--color-gold-soft` | Featured, selected, primary soft emphasis |
| `--color-blue-soft` | Info badges, linked context |
| `--color-green-soft` | Growing state |
| `--color-rose-soft` | Drifting or overdue state |
| `--color-purple-soft` | AI and ranking state |
| `--color-teal-soft` | Freshness and discovery state |
| `--color-amber-soft` | Warning or pending state |
| `--color-pink-soft` | Personal warmth or social context |

### Surface hierarchy

| Token | Role |
|---|---|
| `--background` | Base page canvas |
| `--color-surface` | Cards, panels, widget shells |
| `--color-surface-2` | Nested surfaces, selected rows, active states |
| `--color-border` | Separators, outlines, section rules |

### Status color rules

| Relationship state | Color family | Usage |
|---|---|---|
| Growing | Green | Healthy momentum, recent positive activity |
| Stable | Neutral | Normal relationship state, no urgent action |
| Drifting | Rose | Attention needed, long silence, decaying context |
| Prep ready | Gold or green | Meeting brief complete and useful |
| AI generating | Purple or blue | System is working |
| Warning | Amber | Caution, incomplete context, pending setup |
| Error | Rose | Broken state, failed sync, invalid input |

### Color discipline

Gold is the brand anchor. Use it deliberately. Too much gold makes the interface look decorative instead of intelligent. Gold should mark what deserves attention: selected people, proactive briefs, primary CTAs, and special relationship moments.

## 6. Typography

Rolo uses a three-font system.

### Font roles

| Font | Role |
|---|---|
| Instrument Serif Italic | Display headings, emotional editorial moments |
| Space Grotesk | UI headings, body text, controls, labels |
| Newsreader | Long-form notes, meeting prep, relationship prose |

### Display headings

Use Instrument Serif Italic for h1, h2, and h3 level display moments.

| Use | Size |
|---|---|
| Hero display | `text-6xl` |
| Major page heading | `text-5xl` |
| Section display | `text-4xl` |
| Large prompt | `text-3xl` |
| Small display title | `text-2xl` |

Example display phrases:

The meeting  
Relationship context  
Network intelligence  
Who should I reach out to?  
Warm introductions

### UI headings

Use Space Grotesk for interface structure.

| Use | Size |
|---|---|
| Section label | `text-xl` |
| Card header | `text-base` |
| Widget title | `text-sm` |
| Eyebrow label | `text-xs` |
| Micro label or timestamp | `text-[10px]` |

### Body text

| Use | Size |
|---|---|
| Lead paragraph | `text-lg` |
| Default body | `text-base` |
| Small body | `text-sm` |
| Caption | `text-xs` |

### Prose

Use Newsreader for notes, meeting summaries, relationship histories, and longer contextual writing. This is where Rolo should feel thoughtful and human.

## 7. Layout Principles

### Core reading model

Rolo should follow an N-type reading flow:

1. Orient at the top.
2. Act on the left.
3. Scan insight on the right.
4. Return to action.

This keeps the product from becoming a wall of cards. The user should always know where to look first.

### Dashboard structure

| Zone | Purpose |
|---|---|
| Top command band | Search people, actions, and slash commands |
| Header metrics strip | Small status snapshot: people, growing, due, captured |
| Left action column | Quick capture, person of the day, agenda, follow-ups |
| Right insight rail | Hidden opportunities, prep signals, drift warnings |
| Supporting posture | Usage, relationship health, network footprint |

### Section behavior

Prefer ruled sections, separators, grouped rows, and light widget shells over heavy card walls.

Use cards when they represent real objects: a person, event, note, alert, or selected state. Use separators when content is mostly structural.

### Copy density

Descriptions should be hidden by default when the action is obvious. Disclose extra context only when it helps decision-making.

## 8. Component Style Guide

### Buttons

Supported variants:

Primary  
Outline  
Secondary  
Ghost  
Destructive  
Link

Supported sizes:

Small  
Default  
Large

Button rules:

Primary buttons should be rare and action-specific.  
Ghost buttons work well for quiet dashboard actions.  
Destructive buttons must be explicit and paired with a safer alternative.  
CTA pairs should be predictable: Save changes and Cancel, Delete contact and Keep, Generate prep and Skip for now.

### Badges

Badges communicate relationship state, content type, and system status. Every badge should use a soft fill, matching border, and matching text color.

Badge categories:

Gold / Primary  
Neutral  
Success  
Error  
Info  
Outline

Common badges:

Growing  
Stable  
Drifting  
Streak active  
Prep ready  
Follow-up overdue  
AI generating  
VC  
Remote  
Event  
Note  
Person  
Profile  
AI

### Fields

Inputs should feel calm and useful. Search, capture, and enrichment fields are core to the product.

Field states:

Default  
With value  
Error  
Success  
Disabled  
With icon  
Textarea

Textarea placeholder:

> Quick capture: what happened, who was involved, what matters, and what is next?

### Menus

Dropdowns, context menus, and selection menus must stay consistent. These surfaces have a large impact on perceived quality.

Use menus for:

Person actions  
Sort and filter  
User navigation  
Bulk actions  
Smart group actions

### Overlays

Desktop flows use dialogs.  
Mobile capture and quick actions use bottom sheets.

Dialogs should be reserved for focused decisions or destructive confirmation. Bottom sheets should support fast capture.

### Navigation

Use pill-style tabs for sibling views:

People  
Events  
Notes  
Lists

Use collapsibles for contextual sections:

Professional background  
Relationship context  
Open loops  
Shared connections

Tooltips should explain the signal, not repeat the label.

## 9. Cards and Surfaces

### Standard card

Use for widgets, stat cards, profile cards, and contained activity.

Style:

Surface background  
Elevation-2 shadow  
Subtle hover deepening  
Tokenized border  
No excessive blur

### Featured card

Use for selected, highlighted, or proactive moments.

Style:

Gold border  
Gold gradient fill  
Soft glow  
Clear primary action

Examples:

Person of the day  
Meeting in 28 min  
Important relationship alert  
High-value hidden opportunity

### Stat card

Stat cards should be compact and useful. Avoid turning metrics into decoration.

Example stats:

Total people  
Growing  
Due  
Captured  
Open loops  
Shared circles  
Interactions  
Known for

### List items

List items should be highly scannable:

Avatar or portrait  
Name  
Role or context  
Relationship state  
Last seen  
Optional decay or momentum signal

## 10. Relationship Objects

### People

People are the core object. Real photos should be used when available. Initials are acceptable fallback, but they should not feel second-class.

People views should include:

Identity  
Role  
Relationship state  
Last interaction  
Open loops  
Shared connections  
Tags  
Recent context  
Suggested next action

### Events

Events should be people-forward.

An event is more than a calendar block. It should show the people in the room, the relevant description, attached notes, event prep, and relationship context.

Event prep states:

Not generated  
Generating  
Ready

### Notes

Notes should preserve human context. They should support structured extraction, but the original note should remain readable.

Note surfaces should use Newsreader when long-form.

### Smart groups

Smart groups should feel created by intelligence, not manual filing.

Default smart group categories:

Company  
University  
Family  
Friends  
Role-based cohorts  
Founder advisors  
Recurring dinner or social groups  
Customer or investor clusters

### Rank search

Rank search lets a user ask natural-language questions and receive tiered people results.

Example:

> Who could fund my seed round in AI infrastructure?

Result tiers:

S: Best fit, highest priority  
A: Strong fit, high priority  
B: Good fit, medium priority  
C: Possible fit, lower priority

Use flat vertical lists rather than one card per person. Ranking should feel fast and legible.

## 11. Rarity System

Rolo can use rarity as a visual hierarchy for relationship importance. This should feel like a useful prioritization system, not a game skin.

### Tiers

| Tier | Meaning | Visual treatment |
|---|---|---|
| Legendary | Top 1 percent | Double-wide, full-bleed portrait, overlay |
| Epic | Top 2 to 5 percent | Distinct crown or clipped image treatment |
| Rare | Top 10 percent | Soft gold aura |
| Common | Everyone else | Compact row-style card |

### Rarity rules

Rarity should be earned by context density, mutual value, recent activity, shared circles, and concrete open loops. It should not be based on superficial popularity.

### Good rarity signals

Interaction count  
Years known  
Shared circles  
Warm intros  
Recent activity  
Open loops  
Responsiveness  
Strategic relevance  
Personal importance

## 12. Mascot: Rolie

### Role

Rolie is the friendly mascot and emotional helper layer for Rolo. Rolie should make the product feel alive without overwhelming the interface.

### Visual direction

Minimal ring or torus character  
Warm yellow-to-orange gradient  
Friendly expressive eyes  
Soft asymmetrical smile  
Subtle orbital relationship nodes  
Clean 2D style  
Works on dark and light backgrounds

### Usage

Use Rolie in:

Empty states  
Celebrations  
Onboarding  
Person of the day  
Streak moments  
Friendly errors  
Global fallback states  
Subtle product video scenes

### Behavior

Rolie should be helpful, encouraging, and never pushy. Motion should be polished, lightweight, and respectful of reduced-motion settings.

### Avoid

Overly cartoonish behavior  
Too many appearances per screen  
Thick outlines  
Heavy 3D rendering  
Mascot replacing useful product context

## 13. Motion and Interaction

### Motion principles

Motion should clarify state, reveal hierarchy, and make relationship context feel alive. It should not distract from the user's next action.

Use motion for:

Card landings  
Status shifts  
Hover expansion  
Row expansion  
Filter dropdowns  
Bottom sheets  
Prep generation  
Rolie emotion states

### Motion style

Soft spring transitions  
Subtle hover lift  
Color interpolation for status changes  
Accordion expansion for people rows  
Dropdown animation for filters  
Gentle glow for highlighted moments

### Reduced motion

Always support reduced-motion preferences. Rolo should remain fully understandable without animation.

## 14. Product Voice in UI

### Relationship signal format

Use this structure:

Person  
Signal  
Reason  
Suggested action

Example:

> Sarah Wu has been quiet for 32 days. She asked about your GTM timeline last time, and your Sequoia intro call is tomorrow. Send a quick update before the meeting.

### Open loop format

Use this structure:

Open loop  
Source  
Deadline or urgency  
Next step

Example:

> Send the Notion template Maya requested. Source: Blue Bottle meeting, today 2:45 PM. Suggested next step: send it before Friday.

### Empty state format

Every empty state needs:

Heading  
Useful explanation  
Primary action  
Optional secondary action

Example:

> Your capture stream will appear here. Connect Google Calendar or Gmail and Rolo will start building your network automatically.

Actions:

Connect calendar  
Record a voice memo

## 15. Product Architecture Principles

### Command first

The command band is the main entry point. Search should support people, actions, and slash commands.

### People before data

The product should present relationship context through people, events, notes, and groups before showing abstract charts.

### Action before insight

Insights are only valuable when they make the next step clearer.

### Specificity earns trust

Rolo should cite concrete context inside the UI: names, dates, prior conversations, open loops, and mutual contacts.

### Third-party content translation

Emails, calendar events, notes, and messages should be translated into Rolo's own visual language. Do not make Gmail look like Gmail or Calendar look like Calendar inside the product.

## 16. Dark and Light Mode

Every primitive must work in both dark and light mode.

### Dark mode

Dark mode should feel deep, calm, and premium. Gold accents should glow softly, not aggressively.

### Light mode

Light mode should feel clean, warm, and editorial. Surfaces should have enough contrast to preserve hierarchy without feeling stark.

### QA requirement

Toggle every component in both themes before approving it.

## 17. Accessibility and Quality

### Accessibility standards

Use tokenized colors with sufficient contrast.  
Support keyboard navigation.  
Make hover-only information available through focus or click.  
Support reduced motion.  
Keep mobile inputs at 16px or larger.  
Use real labels, not just icons.  
Avoid relying on color alone for status.  
Make all avatars and portraits accessible with alt text.

### Product quality checklist

All colors use tokens.  
No hardcoded theme colors.  
Dark and light mode both pass visual review.  
Cards do not create a wall of boxes.  
Primary action is obvious.  
Every insight has concrete evidence.  
Every empty state has an action.  
Mobile capture is fast.  
Interactive states feel consistent.  
Rolie is optional and restrained.

## 18. Do and Do Not

### Do

Use real people, real context, and real next actions.  
Use gold to mark meaningful attention.  
Keep the dashboard operational.  
Prefer rows, rules, and hierarchy over card clutter.  
Make smart groups feel automatic and useful.  
Keep copy short, specific, and human.  
Preserve the user's original notes when summarizing.  
Use motion to clarify state.  
Let Rolie add warmth in the right moments.

### Do not

Do not flood the UI with decorative cards.  
Do not make every insight sound urgent.  
Do not overuse gold.  
Do not over-animate relationship health.  
Do not hide concrete evidence behind vague AI labels.  
Do not make smart groups feel like folders the user had to manually build.  
Do not replace human context with abstract scores.  
Do not let Rolie become the product.  
Do not let the interface drift into generic SaaS.

## 19. Example Brand Applications

### Dashboard hero

Good morning. Here is who needs you next.

### Person of the day

Alex Park  
Founder, Moonshot Labs  
47 days since last contact

Open loops:

Send the intro to Ravi Patel.  
Follow up on the seed extension timeline.  
Share the Notion template from your systems talk.

Primary action:

Reach out

### Meeting brief

Meeting in 28 min  
1:1 with Maya Chen

Last spoke 18 days ago about the Series B timeline. Open loop: send the Notion template you promised.

Primary action:

View brief

### Drifting contact

Sarah Wu  
Tier 1 investor  
32 days since last contact  
Last context: asked about GTM timeline  
Suggested action: send a quick update before tomorrow's Sequoia intro call

## 20. Brand Decision Rules

When making a design decision, choose the option that:

1. Makes the next action clearer.
2. Keeps the person at the center.
3. Reduces cognitive load.
4. Uses specific relationship context.
5. Works in both dark and light mode.
6. Feels warm without becoming cute.
7. Feels premium without becoming decorative.
8. Preserves trust.

## 21. Open Questions

These should be resolved before final brand lock:

1. Should gold remain the only dominant accent, or should rarity tiers have stronger color ownership?
2. How often should Rolie appear in core workflows?
3. Should relationship decay be shown as a percentage, a label, or a hidden ranking signal?
4. Should rank search always show reasons, or should reasons appear on hover and expansion?
5. How much personality should empty states have?
6. Should smart groups be editable, explainable, or both?
7. What is the final logo treatment for Rolo and Rolie together?
8. How much visual difference should exist between personal and professional relationships?

## 22. Implementation Notes

Use CSS variables for all theme colors.  
Map badge variants to semantic tokens.  
Keep typography roles strict.  
Use a shared `RelationshipCard` component family for message, email, call, note, calendar, business-card, and person-card variants.  
Use a shared person object schema across dashboard, browse, profile, smart groups, and rank search.  
Create a central status vocabulary: growing, stable, drifting, overdue, prep-ready, generating, pending, disconnected.  
Use consistent hover, focus, active, selected, disabled, and loading states.  
Keep component playground as the source of truth before rolling patterns across product pages.

## 23. Final Brand Summary

Rolo should feel like a calm, intelligent relationship memory system. It remembers the people, context, promises, and moments that usually get lost. The design should be warm and editorial, with gold-led accents, soft surfaces, real human identity, strong typography, and operational clarity. Every screen should help the user answer one question:

Who matters right now, and what should I do next?
