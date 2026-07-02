# DESIGN.md

## Design North Star

LifeAdmin AI should feel like the competent friend who reads the small print, spots the trap, and hands you the next move before the admin machine eats another evening. The interface is dry, direct, and on the user's side: it treats bureaucracy as the absurd villain, not the user. Every screen should make three things obvious fast: what matters, what could cost money or time, and what needs the user's approval before anything goes out.

## Experience Principles

- Deadlines, money, and obligations outrank everything else; put renewal dates, notice periods, penalties, and required actions at the top.
- Show the chain of custody: extracted from document, explained by AI, drafted by AI, waiting for approval, sent. The user always gets the final say.
- Use wit as pressure relief, not decoration. The product can roll its eyes at a clause, but it must never sound like it is judging the user.

## Visual System

- Typography: Use a crisp workhorse sans for the product UI, such as Inter, IBM Plex Sans, or a similar practical face with strong numerals. Pair it with a restrained mono for deadlines, clauses, account numbers, and evidence snippets. Keep labels short, sentence case, and plain-spoken.
- Color: Build on ink black, clean white, and cool administrative gray. Use bureaucratic blue for neutral structure, highlighter yellow for "buried detail found," deadline red for risk, and approval green only when a user-authorized action is complete. No purple AI glow, no soft wellness palette.
- Layout: Favor dense, scannable work surfaces over big marketing panels. Use list-first navigation: Inbox, Documents, Deadlines, Drafts, Sent. Detail views should use a split layout: source clause or email on one side, plain-language meaning and next action on the other. Give risky items heavier visual weight without turning the whole app into an alarm.
- Imagery/Iconography: Use sharp line icons, document fragments, stamps, highlights, checkmarks, and redaction-style blocks. Avoid mascots, robot heads, floating orbs, abstract blobs, and stock photos of relieved people holding laptops.

## Interaction Feel

The product should move like a sharp admin operator: quick triage, plain explanations, explicit confirmation. Hover or tap on any claim should reveal the source clause, page, or email line it came from. Loading states can be dry but useful, such as "Checking the notice period" or "Finding the fee they hid in paragraph 12." Error states should explain what is missing and how to fix it. Drafted outbound emails must switch to formal, neutral language and clearly show recipient, subject, attachment status, and the approval button before sending. Never imply legal advice; frame outputs as explanations, reminders, and user-approved drafts.

## Key Screens Or Moments

- Command Center: A compact queue of contracts, subscriptions, landlord emails, insurance docs, and university paperwork, grouped by urgency and cost.
- Document Explainer: A split view that highlights the original clause, translates it into plain language, and names the consequence: "Cancel by July 14 or pay another month."
- Deadline Radar: A calendar/list hybrid focused on notice periods, auto-renewals, response windows, and documents still missing from the user.
- Draft Approval: A formal email preview with editable fields, source evidence, and a clear state change from "AI-drafted" to "User-approved" to "Sent."

## Anti-Generic Rules

- Avoid the standard AI SaaS look: blue-purple gradients, sparkles, chat bubbles as the main product, and claims about magic.
- Avoid cutesy productivity coaching. This is not a habit app telling people to get organized; it is a tool for fighting hostile paperwork.
- Avoid legal-tech heaviness: dense walls of clauses, intimidating terminology, and fake authority. Keep the source visible, but make the next action obvious.
- Make it feel more like a sharp friend at the municipal counter and less like a corporate dashboard trying to sound inspirational.
