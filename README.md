# Free Architect Skills — Claude AI for Indian Architects

25 free Claude AI skills built specifically for Indian architects. One released every Saturday.

No subscription. No login. No paywall.

---

## Skills Available

### 1. /client-decoder
**Decode what Indian clients actually mean.**

Paste in a meeting transcript, WhatsApp thread, or voice note summary — get back:
- Every vague phrase translated into a specific design instruction
- Full Vastu room placement map as hard design targets
- All family conflicts surfaced and named
- 3–5 clarifying questions that actually change the design
- A WhatsApp message to send the client — ready to copy-paste

Understands: joint families, Vastu, regional aesthetics (Rajasthan, Kerala, Punjab, Gujarat, Tamil Nadu, Bengal, UP/Bihar), NRI clients, mid-construction projects, phased construction, budget signals.

**[Download SKILL.md](client-decoder/SKILL.md)**

---

### 2. /design-critique
**Get a verdict-first architectural critique — the way a senior architect gives it verbally.**

Upload 1–4 images of a built space, interior render, or design competition sheets — get back a structured critique with the most important finding first. Every fix names the problem, the root cause, and the specific solution.

> **Requires Sonnet or Opus. Do not run on Haiku.**

**Space Critique mode** (photos or renders of built/designed spaces):
- The single most important finding — stated as a verdict, not a description
- India material reality check (WPC panels, vitrified tile, POP moulding — not their Western equivalents)
- Authority configuration audit for government and institutional cabins (Group A/B/C protocol, desk position, visitor chair height, inner-circle side chair)
- Cultural identity rating: Absent / Token / Integrated — with a specific fix to move up one level
- Vastu orientation check + RPWD Act 2016 accessibility flag
- Lighting diagnosis to IS 3646 / NBC 2016 Part 8 Section 1 standards — not just aesthetics
- Climate-zone-specific material checks: hot-humid (coastal AP, Kerala), composite (Hyderabad/Telangana), hot-dry (Rayalaseema)
- Three fixes ranked by what the client notices in the first 60 seconds — not design theory

**Competition sheet mode** (A0/A1 boards, auto-detected):
- Brief compliance table with elimination risk rating per requirement
- Jury scan test: 10-second / 60-second / 5-minute verdicts
- Concept extracted from drawings alone — without reading your text blocks
- Three elimination risks ranked by competition stage: shortlisting / scoring / final selection

**[Download SKILL.md](design-critique/SKILL.md)**

#### Sample output — what you actually get

Here is an excerpt from a Space Critique on a senior government officer's cabin:

---

**The Single Most Important Finding**

This cabin is designed as a waiting room, not a command space. The officer's desk is positioned with its back to the entry door — a subordination error that reverses the authority relationship between officer and visitor before a word is spoken. Every visitor who enters this cabin reads the officer's back first. In a functioning Indian government cabin at this designation level, the desk back faces the wall and the officer's face faces the entry. This single correction — rotating the desk 180° and repositioning the credenza behind — would transform every other element in the room.

**Priority 1 Fix — Desk reorientation**
Problem: Desk back faces the entry door; officer faces the window wall.
Root cause: The layout treated window light as the primary driver — a residential design reflex applied to an institutional program.
Fix: Rotate desk 180°. Officer faces the entry door. Credenza moves to the window wall behind the officer. Command position restored.
Cost tier: No-cost — furniture repositioning only.

**Cultural Identity Rating: Token**
One framed Kalamkari print on the side wall. The craft is present but not doing work in the design. Move it to the focal wall behind the officer's desk — the wall every visitor faces — frame it in a brass shadow-gap frame at 8' wide, and let it anchor the room's color palette. That is integrated, not decorative.

---

*This is what the skill produces. The India-specific intelligence — cabin protocol, Kalamkari placement, IS code lighting standards — comes from the skill's calibration for Indian institutional practice.*

**[Download SKILL.md](design-critique/SKILL.md)**

---

## How to Install (2 minutes)

**Step 1 — Download the SKILL.md file**
Click the skill link above. On GitHub, click the "Raw" button, then save the file (Ctrl+S / Cmd+S).

**Step 2 — Create the skill folder**

On **Windows:**
```
C:\Users\[YourName]\.claude\skills\design-critique\
```
This folder does not exist by default. Create it manually in File Explorer.
Note: `.claude` is a hidden folder. In File Explorer: View → Show → Hidden items.

On **Mac / Linux:**
```
~/.claude/skills/design-critique/
```
Run in Terminal: `mkdir -p ~/.claude/skills/design-critique/`

**Step 3 — Put the SKILL.md file inside that folder**

**Step 4 — Open Claude Code and type:**
```
/design-critique
```
Then attach your image(s) and describe the project briefly.

**That's it.**

> **First use tip:** Upload the original image file from your camera or project folder — not a WhatsApp-forwarded photo. WhatsApp compresses images to ~600px, which loses the material and detail information the skill needs. Name your images in the message: "main view," "artwork wall," "Sheet 1 — concept plan."

> **No Claude Code?** Paste the SKILL.md contents as your Claude Project instructions. Works the same way without setup.

---

## Coming Every Saturday

| # | Skill | What it does | Status |
|---|-------|-------------|--------|
| 1 | /client-decoder | Decode Indian client briefs | ✅ Available |
| 2 | /design-critique | Critique spaces and competition sheets | ✅ Available |
| 3 | /scope-guard | Handle scope creep and mid-project changes | Coming soon |
| 4–25 | More coming... | Every Saturday | — |

---

## Scope and Limitations

These skills are calibrated for: residential, commercial offices, government/institutional cabins, and design competition submissions.

Not yet covered: healthcare facilities, educational institutions, religious spaces, showrooms, and hospitality. These program types use different evaluation frameworks and will be addressed in future skill updates.

---

## Why This Exists

Indian architects are underpaid, overworked, and spend 40% of their time on communication that nobody taught them to handle.

These skills change that.

Built by an architect, for architects. Free forever.

Found a factual error or a wrong code citation? [Open an issue](../../issues) — India-specific standards evolve and corrections are welcome.

---

## License

CC BY 4.0. Free for all uses including professional practice and billable client projects. If you share or adapt this file, credit 9 Brics Studio. Your project outputs belong to you.

---

## Follow for Weekly Releases

New skill every Saturday — LinkedIn and Instagram.

Built by [9 Brics Studio, Hyderabad](https://www.linkedin.com/in/deepu-sathyanarayana-6b5b7619b/)