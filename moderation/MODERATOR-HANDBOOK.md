# Moderator Handbook

> **Version:** 1.0
> **Last updated:** 2026-03-18

This is the operational guide for Breachers of Tomorrow moderators (Security Officers). It covers the principles and practices we try to follow, especially as the community continues to grow.

**Related documents:**

- [Code of Conduct](../CODE-OF-CONDUCT.md) — The public-facing rules members agree to
- [Moderation Guidelines](GUIDELINES.md) — Philosophy and escalation ladder
- [Incident Response](INCIDENT-RESPONSE.md) — Scenario-specific quick reference

---

## Table of Contents

1. [Moderator Mindset](#moderator-mindset)
2. [Your First Shift](#your-first-shift)
3. [Day-to-Day Moderation](#day-to-day-moderation)
4. [Handling Common Situations](#handling-common-situations)
5. [Growth & Raid Preparedness](#growth--raid-preparedness)
6. [Discord Tools & Permissions](#discord-tools--permissions)
7. [Communication Standards](#communication-standards)
8. [Moderator Self-Care](#moderator-self-care)
9. [Escalation Matrix](#escalation-matrix)
10. [Onboarding New Moderators](#onboarding-new-moderators)

---

## Moderator Mindset

### You are a host, not a cop

Your primary job is to **keep the community welcoming and productive** — not to catch people breaking rules. The best moderation is invisible: members feel safe and conversations flow naturally.

### Core principles

| Principle | What it means |
|-----------|---------------|
| **Assume good intent** | Most problems are miscommunication, not malice. Start from that assumption. |
| **De-escalate first** | Lower the temperature before taking action. A calm redirect fixes 80% of situations. |
| **Be consistent** | Apply rules the same way for everyone — friends, regulars, newcomers, and even Keepers. |
| **Be proportional** | Match the response to the severity. A first-time off-topic post doesn't need the same response as targeted harassment. |
| **Document everything** | If you took an action, log it. Patterns become visible only when incidents are recorded. |
| **You don't have to act alone** | When in doubt, ask in `#moderation-general`. There's no shame in a second opinion. |

### The 10-second rule

Before taking any moderation action, pause for 10 seconds and ask yourself:

1. **Is this urgent?** (If yes — act now, discuss after. If no — discuss first.)
2. **Am I reacting emotionally?** (If yes — tag another moderator.)
3. **What's the minimum action that resolves this?** (Do that.)

---

## Your First Shift

If you're a new Security Officer, here's your onboarding checklist:

### Access verification

- [ ] You have the `Security Officer` Discord role
- [ ] You can see the `Moderation` channel category
- [ ] You can access Discord's moderation tools (timeout, kick, ban, message delete)
- [ ] You've read the [Code of Conduct](../CODE-OF-CONDUCT.md)
- [ ] You've read the [Moderation Guidelines](GUIDELINES.md)
- [ ] You've read the [Incident Response](INCIDENT-RESPONSE.md) playbooks

### Shadowing

For your first week, **shadow before acting:**

1. Watch how experienced moderators handle situations in `#moderation-general`
2. Ask questions — there are no stupid questions about moderation
3. Start with low-stakes actions (redirecting off-topic conversations, welcoming newcomers)
4. Discuss any action you're unsure about before taking it

### Your first actions should be

- Welcoming new members
- Gently redirecting off-topic conversations if needed
- Answering questions
- Reporting concerning behavior in `#moderation-general` for others to triage

---

## Day-to-Day Moderation

### What to monitor

| Priority | What to Watch | Where |
|----------|---------------|-------|
| 🔴 High | Harassment, hate speech, doxxing, threats | All channels |
| 🔴 High | Spam/raid attacks | High-traffic channels, new member introductions |
| 🟡 Medium | Heated arguments escalating | Discussion channels |
| 🟢 Low | Off-topic conversations | Topic-specific channels |
| 🟢 Low | Light rule-bending | Everywhere |

### Routine tasks

**Daily (when active):**

- Skim recent messages in high-traffic channels
- Check `#reports` for anything flagged
- Welcome notable new member waves

**Weekly:**

- Review `#moderation-general` for any pending mod decisions
- Check for patterns — same person causing low-level issues repeatedly?

**As needed:**

- Log incidents in `#moderation-log`
- Update this handbook with new scenarios or lessons learned

---

## Handling Common Situations

### Situation: Off-topic conversation

**Severity:** Low | **Action:** Redirect

> "Hey folks — love the energy! This conversation might be a better fit for `#off-topic`. Mind moving it over there?"

**Don't:** Delete the messages or scold. **Do:** Be friendly and redirect.

### Situation: Mild argument / heated debate

**Severity:** Low–Medium | **Action:** De-escalate

> "This is a great discussion, but let's keep it on the ideas and not get personal. Everyone take a breath."

If it continues after one warning:

1. Enable slowmode (30–60 seconds) on the channel
2. DM the primary participants individually — remind them of expectations
3. If one person is clearly the aggressor → temporary mute (1 hour)

### Situation: Self-promotion / spam

**Severity:** Medium | **Action:** Remove + warn

1. Delete the message
2. DM the person:

> "Hey — we don't allow self-promotion or advertising in the server. If you'd like to share something relevant to the community, reach out to a Keeper first."

3. If they repost after the warning → temporary mute (24 hours)
4. If they're clearly a spam bot → ban immediately

### Situation: New member wave

**Severity:** Situational | **Action:** Proactive management

When a large number of new members join in a short window (game drops, events, social media mentions, etc.):

1. **Post a welcome message** in the main channel:

> "Welcome to all the new Breachers! 👋 We're glad you're here. Quick tips:
> - Read `#rules` to get oriented
> - ARG discussion happens in the research channels
> - `#off-topic` for everything else
> - Have fun and be respectful!"

2. **Increase monitoring** for the next few hours — new member waves bring excitement but occasionally bad actors
3. **Enable slowmode** if the message rate gets overwhelming (15–30 seconds)
4. **Be welcoming** — the goal is to convert visitors into long-term community members, not gatekeep

### Situation: Harassment / personal attacks

**Severity:** High | **Action:** Protect → Investigate → Act

1. **Screenshot everything** before acting (messages may be deleted)
2. **Mute the aggressor** immediately if the behavior is ongoing
3. **DM the target** — acknowledge the situation, explain what you're doing
4. **Post in `#moderation-general`** — coordinate with the mod team on appropriate action
5. **Log the incident** in `#moderation-log`

See [Incident Response](INCIDENT-RESPONSE.md) for detailed playbooks.

### Situation: Doxxing / personal information shared

**Severity:** Critical | **Action:** Immediate removal

1. **Delete the message immediately** — do not wait for discussion
2. **Ban the poster** — this is an immediate-ban offense
3. **DM the affected person** — let them know the content was removed
4. **Report to Discord Trust & Safety** if the situation is severe
5. **Log the incident** in `#moderation-log`

### Situation: Raid / coordinated attack

**Severity:** Critical | **Action:** Lockdown

See [Incident Response — Spam / Raid](INCIDENT-RESPONSE.md#spam--raid) for the full playbook. Quick version:

1. Enable Discord Community Safety features (DM verification, phone verification level increase)
2. Ban obvious bot/raid accounts
3. Post coordination messages in `#moderation-general`
4. Consider temporarily restricting new member posting ability
5. **After:** Debrief and log the incident

---

## Growth & Raid Preparedness

As the community grows, we'll encounter more situations where large groups of new people arrive at once. The key principles:

| Scenario | Response |
|----------|----------|
| Wave of genuine new members | Welcome message, increased monitoring, slowmode ready |
| Bad actors mixed in | Watch for brand-new accounts posting immediately, look for patterns |
| Trolls / griefers | Quick mute, Automod rules, moderator presence in active channels |
| Coordinated harassment | Lockdown procedures, Discord safety features, ban-on-sight criteria |

**The goal is always the same:** welcome the good-faith newcomers, remove the bad actors quickly, and keep the existing community feeling safe.

---

## Discord Tools & Permissions

### Moderation channels

| Channel | Purpose |
|---------|---------|
| `#moderation-general` | General mod discussion, coordination, second opinions |
| `#moderation-log` | Record of moderation actions taken |
| `#incidents` | Active incident tracking and discussion |
| `#reports` | Member-submitted reports |
| `Moderation-Voice` | Voice channel for mod discussion |
| `Interview` / `Pre Interview` | Voice channels for member interviews |

### Moderation actions reference

| Action | How (Discord) | When to Use | Reversible? |
|--------|---------------|-------------|-------------|
| **Delete message** | Right-click → Delete | Rule violation, spam | No |
| **Timeout (mute)** | Right-click → Timeout | Disruption, repeated warnings | Yes (auto-expires) |
| **Kick** | Right-click → Kick | Serious violation, warning shot before ban | Yes (they can rejoin) |
| **Ban** | Right-click → Ban | Extreme violations, raids | Manual unban required |
| **Slowmode** | Channel Settings → Slowmode | High traffic, heated conversations | Yes |
| **Lock channel** | Channel Permissions → deny Send Messages | Emergencies, raids | Yes |

### Message deletion guidelines

- **Delete:** Hate speech, doxxing, NSFW, spam, threats — immediately
- **Delete + DM:** Self-promotion, off-topic in important channels — educate
- **Don't delete:** Bad takes, unpopular opinions, mild swearing, things you personally disagree with — let the community self-moderate

### Timeout durations

| Situation | Duration |
|-----------|----------|
| Cooling off a heated argument | 5–15 minutes |
| Repeated off-topic after redirect | 30 minutes |
| Disrupting conversation | 1–2 hours |
| Moderate rule violation after warning | 12–24 hours |
| Serious violation | 1–7 days |

---

## Communication Standards

### How to DM a member about an issue

**Always be:**

- Specific about what they did
- Clear about what the expectation is
- Respectful — they're a person, not a case number

**Template for minor issues:**

> Hi [name]! I'm one of the moderators for Breachers of Tomorrow. I wanted to reach out about [specific behavior] in [#channel]. [Explain why it's an issue]. Could you [specific ask]? No hard feelings — just trying to keep things running smoothly for everyone. Thanks!

**Template for formal warnings:**

> Hi [name]. I'm reaching out about [specific behavior] in [#channel] on [date]. This falls under [specific rule] of our community guidelines. This is a formal warning — continued behavior of this nature will result in [next escalation step]. If you have questions about our rules, I'm happy to clarify. We want you to be part of the community — we just need everyone following the same expectations.

**Template for bans:**

> Hi [name]. After review by the mod team, we've made the decision to [temporarily/permanently] remove you from Breachers of Tomorrow due to [specific behavior]. [If temporary]: You may rejoin after [date]. [If permanent]: This decision was based on [reason]. If you believe this was made in error, you can appeal after 48 hours by contacting a Keeper.

### How to post in public channels as a moderator

- **Use your personal account** — We don't have a mod bot identity (yet)
- **Be firm but friendly** — Authoritative without hostility
- **Don't argue publicly** — If a member pushes back on a mod action, take it to DMs
- **Don't over-explain** — A brief statement is better than a paragraph justification in the channel
- **Never mock or shame a member publicly** — Even if they "deserve it"

### How to report to the mod team

When posting about an incident in `#moderation-general`:

```
🔴 [SEVERITY] — [Brief description]
Who: @username (Discord ID: XXXX)
Where: #channel
What: [1-2 sentence summary]
Evidence: [Screenshots / message links]
Action taken: [What you already did]
Action needed: [What needs to happen next]
```

---

## Moderator Self-Care

### This is volunteer work

**You are not paid. You are not on-call 24/7. You are not obligated to respond to every incident.**

### Setting boundaries

- **It's OK to step away.** If a situation is affecting your mental health, tag another moderator and take a break.
- **You don't have to read every message.** Skim, don't deep-read.
- **Mute notifications when you're off.** The community will survive without you for a few hours.
- **Rotate difficult duties.** Don't let one person handle all the hard stuff.

### Burnout signals

Watch for these in yourself and other moderators:

| Signal | What it looks like |
|--------|-------------------|
| Cynicism | "These people are all idiots" |
| Over-enforcement | Handing out warnings for borderline-at-best violations |
| Withdrawal | Going silent in `#moderation-general` |
| Resentment | "Why am I the only one who does anything?" |
| Emotional reactivity | Taking mod actions while angry or upset |

**If you notice these:** Talk to a Keeper or another moderator. Take a break. It's OK. The community benefits more from a healthy you than a burned-out you.

---

## Escalation Matrix

Quick reference for "this just happened, what do I do?"

| Situation | Immediate Action | Escalation | Log? |
|-----------|-----------------|------------|------|
| Off-topic conversation | Friendly redirect | None needed | No |
| Mild argument | De-escalation message | Slowmode if continues | No |
| Heated / personal argument | Separate parties, DM both | Discuss in `#moderation-general` | If action taken |
| Self-promotion | Delete, DM warning | Mute if repeated | If pattern |
| Spam bot | Ban immediately | Report to Discord | Yes |
| Harassment | Mute aggressor, DM target | Mod team discussion, ban decision | Yes |
| Hate speech / slurs | Delete + mute immediately | Mod team discussion, ban likely | Yes |
| Doxxing | Delete + ban immediately | Report to Discord T&S | Yes |
| Threats of violence | Delete + ban immediately | Report to Discord T&S + law enforcement if credible | Yes |
| Raid / mass spam | Lockdown procedures | All hands in `#moderation-general` | Yes |
| NSFW content | Delete + ban | Report to Discord T&S | Yes |
| Moderator disagreement | Pause, discuss | Default to less severe action | Decision logged |

---

## Onboarding New Moderators

When bringing on a new Security Officer:

1. Grant the `Security Officer` Discord role
2. Walk them through the `Moderation` channel category
3. Point them to this handbook, the [Guidelines](GUIDELINES.md), and [Code of Conduct](../CODE-OF-CONDUCT.md)
4. Pair them with an experienced moderator for their first week (shadowing)
5. Check in after the first week — answer questions, address concerns

---

## Changelog

| Date | Change | By |
|------|--------|----|
| 2026-03-18 | Graduated to public community repo — v1.0 | Keepers team |

---

*This handbook is a living document. It describes how we try to moderate — not a rigid set of rules. Update it as we learn what works and what doesn't. The best moderation playbook is one that evolves with the community.*
