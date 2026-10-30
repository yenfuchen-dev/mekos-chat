# MekOS — Projects experience

Three clickable prototypes of the same idea, built in order. No build step,
no server, no dependencies — open an HTML file and it runs.

**[index.html](index.html)** is the one to look at. Versions A and B are kept
for the trail, not for review.

---

## The idea being tested

The five MekOS stages — Briefs, Strategy, Concepting, Production, Impact —
stop being a sequence you walk and become **skills you call**.

No "stage 2 of 5". No locked stage 3. No sign-off gate. A project is a
conversation plus whatever the skills produced, in whatever order the work
actually needed them.

Two consequences the layout has to carry:

1. **The composer is the control surface.** Skills are armed from the chat
   box, not picked from a stepper in the nav.
2. **Every skill switches on its own connectors.** Claude and Waldo are
   always on; Sprout, Higgsfield, Excel and the rest arrive with a skill.

---

## The three files

| | What it is |
|---|---|
| **index.html** | **Version C** — the demo cut. Same model, far less furniture. Start here. |
| version-b.html | Version A's thesis, fully built: 27 skills, connector chips, receipts on everything. Right, and too much for a first look. |
| version-a.html | The first pass, where stages were still a chain in the sidebar. Useful only as a before. |

---

## A path through version C — about three minutes

1. **Open Amtrak.** Two sections. *Context* is the standing profile every
   skill reads before it does anything. *Live signals* sit in their own band
   underneath, because they expire and Context doesn't.

2. **Open "Acela relaunch" → "Positioning from the brief".** A brief went in
   with one skill attached; a 4C positioning came back. Click the grey
   summary line inside the card for the six steps it actually ran.

   Then read the second half: a line gets refined and **no run card appears**.
   Editing an artifact isn't a skill call, so the UI doesn't pretend it is.

3. **Switch to "Why did bookings dip?"** No skills at all — just a question
   and an answer. This one matters: if chat is only a launcher for skills,
   the whole model is a stepper with extra clicks.

4. **Open "FY27 roster RFI".** An Excel RFI in, a response draft out. Nothing
   here is creative and the layout doesn't change to carry it — that's the
   test. Look for the pink block: seven questions the agent refused to answer
   because it couldn't source them.

5. **Skills** (bottom left). All 27, grouped the way the team talks about the
   work. The groups are labels, not steps. Each card is name, what it does,
   and what it plugs into — **click one** for the rest: what it takes, what
   it gives back, and what wakes up when it runs.

6. **+ New skill → Draft it → Add to workspace.** Describe a skill in a
   sentence and MekOS drafts the definition. Add it, then open the chat box
   and type `tone` — it's there. That round trip is the point.

7. **Connectors** (bottom left). What's plugged in, what's live now, what's
   still available. The usage counts are read off the skills themselves, so
   the page can't drift from reality.

8. **In any chat box, press `/`.** The menu opens on what can run *right now*
   given what's in that project. "Show all 27" opens the rest; greyed rows
   name the input they're waiting for.

---

## What's real and what isn't

Everything is a mock. Nothing sends, nothing saves, no agent runs. The copy is
written against Amtrak's real profile so the shape can be judged against
plausible work rather than lorem — **the work itself is invented**, including
the RFI answers and every capability claim in them.

A skill you add really is added: it appears on the Skills page, changes the
connector counts and becomes callable from the chat box. It disappears on
refresh.

Deliberately inert: *Edit* on Context, *+ Add connector*, and the *Connect*
links.

Fonts load from Google, so be online. Offline it falls back to a system font.

Built for desktop. Below ~880px the sidebar hides and there's no replacement
nav yet, so don't review this on a phone.
