# ShemOS-commands.md
**Shorthand Command Reference — Public Build**
*Companion to ShemOS.md — Version 1.1*
*By Jill Shem | jillshem.com | Human Experience: Aligning Humanity and its Tools (2026)*

---

> *"The commands are shortcuts. The framework is still running underneath."*

---

## What This Is

This is the ShemOS shorthand vocabulary — words that trigger specific, repeatable operations inside a ShemOS session. Some are publishing pipeline prompts. Some restore you. Some help you grow. Some cut straight to the insight.

They work best when your Layer 1 context is already loaded. The commands assume the AI knows who it's talking to.

A private companion document (`ShemOS-commands-PRIVATE.md`) contains your personalised versions of these prompts. This document is the template. That one is yours.

---

## The Family

The prefix carries the meaning. When you add new commands, name them to match what they *feel* like, not just what they do. The light metaphor is load-bearing.

| Prefix | Type | Energy |
|---|---|---|
| `glitter` | Publishing pipeline | Package, sort, surface |
| `glimmer` | AI prompt | Restore, soften, decompress |
| `glow` | AI prompt | Grow, reflect, introspect |
| `glint` | Marker + AI prompt | Sharp, invigorating, a-ha |
| `gleam` | *Open — expand when ready* | — |

---

## The Glitterbomb Manifest

Before any `glitter` command runs, you maintain a **glitterbomb manifest** — your personal definition of what belongs in each layer. The command structure is the same for every ShemOS user. The manifest is yours alone.

Three layers:

**Public** — what's ready to push. GitHub, your site, anything intended for other humans.

**Insights** — what's still in progress. Not ready, but captured. The thinking you're still thinking with.

**Private** — what was learned that doesn't go anywhere yet. Anything whose exposure would cost someone else something they didn't choose. The test isn't *"would I be embarrassed"* — it's *"would publishing this without warning cost someone else something they didn't consent to."*

Your manifest lives in your private companion document. Update it there.

---

## glitter

### `glitterbomb`

**What it does:** Runs at the end of a session and sorts what just happened into three artifacts — public, insights, and private. A publishing pipeline, not a backup. The AI drafts the sort; you approve before anything is finalised.

**When to use it:** End of a significant session. When you've produced something worth capturing. When you need to bridge from session work to published work.

**Output — three `.md` files:**
- `glitterbomb_public_YYYY-MM-DD_TIMESTAMP.md` — ready to push to GitHub or your site
- `glitterbomb_insights_YYYY-MM-DD_TIMESTAMP.md` — in progress, not ready, captured
- `glitterbomb_private_YYYY-MM-DD_TIMESTAMP.md` — stays in your private archive

**The prompt:**
```
glitterbomb

Session's done. I need you to sort what happened into three layers:
public (ready to publish), insights (in progress, not ready), and
private (learned but not for public eyes).

Draft the sort based on what we covered. Show me your reasoning for
anything you're not sure about. I'll approve, move things between
layers, and tell you when to finalise. Then generate one .md file
per layer, timestamped.

My manifest: [paste your glitterbomb manifest here]
```

---

## glimmer

The `glimmer` family restores you. These are not productivity prompts. There are no next steps. The regulation bottleneck is already full — don't add to it.

---

### `glimmer`

**What it does:** Gives you something to look forward to. Decompresses the research brain. Reminds you the world contains things that are just good, with no agenda attached.

**When to use it:** After a long session. When you've been in your head too long. When you need to remember there's a life outside the work.

**The prompt template:**
```
glimmer

I've been deep in work and I need to decompress. Don't analyse
anything. Don't summarise what we did. Just give me something
genuinely good to look forward to — something small, specific,
and real. You know who I am. Make it feel like it's for me.

[Add context about yourself — what you enjoy, what restores you,
what "something good" looks like for you specifically.]
```

---

### `glimmer hope`

**What it does:** Pulls you back when you start to hate the world. Not toxic positivity. Not a pep talk. A reminder that the things worth caring about are still worth caring about.

**When to use it:** When the research gets heavy. When you've been staring at systems that fail people for too long. When you need to remember why you're doing any of this.

**The prompt template:**
```
glimmer hope

I'm starting to hate the world a little. Not a crisis — just the
slow grind of caring about things that are hard to fix. Don't tell
me it'll be okay. Don't give me statistics. Give me one true thing
that's worth holding onto right now. Something real. Something that
doesn't need me to squint to see it.

[Add what's been weighing on you, or leave it open.]
```

---

### `glimmer dreams`

**What it does:** Soft landing. Emotional wind-down after a session. Reflects back how you *feel* leaving the work — not what you learned, not what's next. Prepares you for rest.

**When to use it:** Last thing before you close the laptop. Run it after `glow debrief` if you're doing both. This one lands. That one reflects.

**The prompt template:**
```
glimmer dreams

I'm winding down. Don't summarise the session. Don't tell me what
I accomplished. Just reflect back the feeling of where I am right
now — soft, honest, no performance. Then give me one small thing
to carry into sleep. Not a task. Not a reminder. Something that
feels like permission to rest.

[Add anything about how you're actually feeling right now,
if you want it reflected back accurately.]
```

---

## glow

The `glow` family is for growth — personal, professional, and the kind that doesn't have a category yet. It looks inward and faces forward. It doesn't flatten what it finds.

---

### `glow`

**What it does:** Opens a space for personal and professional introspection. Not a check-in, not a debrief — just you, thinking about who you're becoming, with the AI holding the structure so you don't have to.

**When to use it:** When you sense something shifting but haven't named it yet. When you've learned something that doesn't fit anywhere. When you want to think about yourself on purpose.

**The prompt template:**
```
glow

I want to think about my own growth for a bit — personal,
professional, whatever's present. Don't lead me anywhere. Ask me
one open question and hold whatever I bring back without trying
to resolve it. I'll tell you when I'm ready to move.

[Add any context about what's been shifting lately, or leave
it open and let the AI ask first.]
```

---

### `glow check`

**What it does:** Quick personal check-in mid-session. Not about the work — about you doing the work. Thirty seconds. Keeps you honest.

**When to use it:** When you feel yourself drifting. When you've been going for a while and you're not sure if you're still okay. When the gate feels like it's closing.

**The prompt template:**
```
glow check

Quick check: how am I actually doing right now? Not the work — me.
Read what's been happening in this session and give me an honest,
brief reflection. One thing you've noticed. Nothing more.
```

---

### `glow debrief`

**What it does:** End-of-session inventory of what you learned about *yourself*. Faces forward. Not the same as `glimmer dreams` — it's reflective, not emotional. It asks: what do I know now that I didn't know before?

**When to use it:** After a significant session. Run this before `glimmer dreams` if you're doing both.

**The prompt template:**
```
glow debrief

Session's wrapping up. I don't want a summary of what we built —
I want to know what I learned about myself. Not about the research.
About me. Look at the session and reflect back: what did I discover,
what pattern showed up, what surprised you about how I worked today?
Keep it honest. Keep it mine.
```

---

### `glow arc`

**What it does:** Longer-term growth tracking across multiple sessions. Connects the dots between who you were and who you're becoming. Requires context from previous sessions — paste in relevant `glow debrief` outputs or notes.

**When to use it:** When enough time has passed that something has actually changed. Not every session. When you want to see the arc, not just the moment.

**The prompt template:**
```
glow arc

I want to look at the longer arc. Here's context from previous
sessions: [paste relevant glow debrief outputs or notes].

Don't analyse the research. Look at me across these sessions and
tell me what you see moving — what's shifted, what's holding,
what's still in progress. I'm not looking for conclusions.
I'm looking for the shape of it.
```

---

## glint

`glint` works two ways: as a **mid-session marker** you drop in real time, and as a **dedicated prompt** when you want to chase the insight further. It's the sharpest tool in the family. It doesn't meander.

---

### `glint` — as a marker

**What it does:** Flags a breakthrough moment mid-session so it doesn't get lost. Drop it inline, right when it happens. The AI acknowledges it and holds it. You keep moving.

**When to use it:** The moment something clicks. Don't wait. Don't explain it. Just drop it.

**How to use it:**
```
glint — [one line: what just clicked]
```

The AI will acknowledge the glint, hold it without expanding it, and you continue. Your glints at the end of a session are the map of where the breakthroughs were. Feed them into `glitterbomb` or `glow debrief` when you're done.

---

### `glint` — as a prompt

**What it does:** Chases an insight further. Takes a glint — already marked or still sitting unexamined — and opens it up with sharpness. This is not a `glow` prompt. It doesn't meander. It cuts.

**When to use it:** When a glint deserves more than a marker. When you've been circling something and you're ready to go straight at it.

**The prompt template:**
```
glint

I've had an insight I want to chase: [the thing].

Don't be gentle with it. Don't give me a framework. Ask me the
sharpest question you can about this — the one that'll either
break it or prove it. One question. Wait for my answer.
```

---

## Adding New Commands

1. **Pick the right prefix.** Does it package something? `glitter`. Does it restore you? `glimmer`. Does it help you grow? `glow`. Does it cut to something sharp? `glint`. If none fit, you might be starting a new family.
2. **Write the when.** Not just what it does — when it belongs. Timing is half the protocol.
3. **Write the prompt as a template.** Public version uses `[your details here]`. Private version is yours.
4. **Add it here** under the right family, and to your private companion document with your actual prompt.
5. **Update the family table** at the top.

---

*ShemOS-commands.md — public build, companion to ShemOS.md*
*Private version: ShemOS-commands-PRIVATE.md — not published*
*First published 2026 · Live document · Updates as the framework updates.*
*Attribution: ShemOS framework by Jill Shem — jillshem.com*
*Licence: see ShemOS.md*
