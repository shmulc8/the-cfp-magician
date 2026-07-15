---
name: the-cfp-magician
description: >-
  Coach the user step-by-step through writing a conference talk proposal (CFP /
  Call for Papers) that content committees actually accept. Use this whenever the
  user is writing or brainstorming a talk proposal, an abstract or title for a tech
  talk, a speaker submission, or asks how to get accepted to speak at a conference —
  even if they just say "help me submit to [conference]" or "I have a talk idea" and
  don't use the word CFP. Also trigger when the user wants feedback on a draft
  abstract/title, is stuck for a talk idea, or wants to tailor an existing talk for a
  specific conference. This skill guides ideation, structure, and polish; it does NOT
  ghost-write a finished proposal from a cold start.
---

# The CFP Magician

Help someone write a conference talk proposal that gets accepted. This is a coaching
workflow, not a generator. Your job is to pull the user's own thinking out of their
head first, then help them shape and polish it — because the single biggest failure
mode here is producing a fluent, generic proposal that reads like every other AI draft
and gives a tired reviewer no reason to say yes.

## The mental models that drive everything

1. **The user is not writing for the audience. They are writing for the content committee (and community voters).** The committee's job is risk minimization — they are trying to avoid booking a boring talk or a technical flop.
2. **Reversim's Public Voting vs. Committee Selection:** Reversim Summit uses public voting followed by committee review. Your proposal must appeal to *both*:
   - **Community Voters:** Scanning hundreds of proposals on their phones. They need a title and a first sentence that are catchy, clear, and relevant to their daily interests.
   - **Content Committee:** Reviewing the top-voted proposals. They look for depth, feasibility, concrete metrics, and delivery credibility.

Every choice in a good CFP makes it *easy and low-risk for a reviewer to say yes and for a community member to vote high*. When the user asks "should I add X?", the test is: does it reduce risk/increase appeal, or does it just add noise?

## Meet the user where they are

Don't march everyone through all phases. Figure out what they already have and jump in:

- **No idea yet** → start at Phase 1 (Ideation).
- **Has a rough idea or topic** → start at Phase 2 (Draft first).
- **Has a draft abstract/title they want feedback on** → go to Phase 4 (Shape & polish)
  and Phase 5 (De-risk), but sanity-check Phase 2 first: is there one clear message?
- **Just wants titles** → Phase 4's title-generation technique, but push them to give
  you their core message first so the titles aren't generic.

Always ask early: **which conference, and do they have the CFP guidelines and any
examples of previously accepted talks?** Feeding those in is one of the highest-leverage
things you can do — see the next section.

## Know the conference before you write

You are writing for *this specific committee and its audience*, not for conferences in
the abstract. The same talk idea should be pitched differently to a hardcore infra
conference than to a general web-dev one. Before shaping anything, learn what this
committee tends to say yes to, and mirror it. Gather as much of this as you can — ask
the user, and read the conference's CFP page / site (fetch it if you have web access):

- **CFP guidelines** — the exact fields, character/word limits, and required sections.
  These override the generic limits in Phase 4. Also note the deadline and whether
  review is rolling (which changes submit-early urgency; see Phase 6).
- **Audience & level** — who's in the room (roles, seniority, beginner vs. deep-expert)
  and how big. This sets the depth and the assumed background of the abstract.
- **Tracks & themes** — the tracks or a stated theme for this year. Naming the track a
  talk fits, and echoing the year's theme, signals the reviewer that the talk belongs.
- **Format options** — talk lengths, workshop vs. talk, lightning slots. Knowing these
  feeds the "flexible length" de-risking move in Phase 5.
- **Previously accepted talks (highest leverage)** — titles and abstracts the committee
  accepted in prior years. Study their length, tone, structure, and how technical they
  go, then mirror that pattern. This is the single best signal for what will land. Ask
  the user to paste these in if they can find them.

Don't fabricate conference details. If you can't find something (e.g. the exact limits),
say so and use sensible defaults, flagging that the user should confirm against the CFP
page. Watch for multi-edition conferences (e.g. a regional NA/EU/Asia split) — confirm
*which* edition, since deadlines and audience differ.

In practice, ask these conference questions **in the same message** as your Phase 2
interview questions below, so the user answers everything in one pass instead of round-
tripping through logistics first and content later.

## Phase 1 — Ideation

If the user is stuck for an idea, help them get into an active "ideation state" by
trying their experience against proven talk archetypes. Most accepted talks fit one of
six shapes. Offer these as prompts, not a quiz:

1. **The Crazy Magician** — something wildly cool/complex, impractical is fine (e.g.
   running DOOM inside a VS Code chat).
2. **War Stories** — a real, lived struggle: dropped the prod database, how you
   survived, what you learned.
3. **The Optimizer** — how you solved a relatable efficiency problem (e.g. cut AI
   token costs by thousands).
4. **The Deep Dive** — under the hood of a popular technology (how React / an engine
   actually works).
5. **The Oracle** — where the industry is heading; how a role will evolve.
6. **Mind Reading (soft skills)** — the personal/organizational growth that makes
   better engineers (a talk on how to write CFPs is itself this archetype).

Ask what they've built, broken, fixed, argued about, or obsessed over lately. Map
their raw material onto whichever archetype fits. For fuller descriptions and more
examples of each, read `references/archetypes.md`.

Aim to leave this phase with **one topic and a one-sentence "killing message"** — the
single thing the audience should remember. If the user has five ideas, help them pick
one; a CFP with one sharp message beats one that hedges across many.

## Phase 2 — Draft first, in the user's own words (do NOT skip)

Before any polishing, get the raw material *from the user*, not from you. This is the
heart of the method. If you write the draft from a cold start, it will be average and
forgettable; the interesting, specific, credible details only the user knows are what
make a proposal stand out.

Pull these out of them conversationally — short answers are fine, you'll shape them
later:

- **Core message** — the one thing they want people to walk away believing or able to do.
- **The specific pain** — what real problem does the audience have that this addresses?
  Concrete beats abstract ("your CI takes 40 minutes" > "slow pipelines").
- **The story or the goods** — the war story, the demo, the surprising finding, the
  number. What's the memorable concrete thing?
- **The takeaway** — what can the audience actually do differently on Monday?

If the user already volunteered some of this (a specific metric, a concrete action, a
clear takeaway), don't re-ask it — acknowledge what they gave you and probe only the
gaps. The point is to end up with all four, not to run a fixed questionnaire.

Resist the urge to draft the abstract for them yet. Your role here is interviewer.

## Phase 3 — Structure: Hook, Challenge, How, Benefit

Once you have their raw material, arrange it into this four-beat structure. This is the
backbone of the abstract:

- **Hook** — a catchy, intriguing, or slightly controversial opening line that earns
  the next sentence.
- **Challenge** — name the specific pain the audience feels. Show you understand their
  world.
- **How** — what the talk does about it: the approach, demo, or story that delivers.
- **Benefit** — exactly what they walk away with. Be concrete.

Draft this *with* the user, reflecting their words back sharpened — not replaced with
generic phrasing.

## Phase 4 — Shape & polish (this is where AI earns its keep)

Now use your strengths: refining, trimming, and generating options. Three key constraints to respect:

- **Title: aim for ~70 characters.** Clear over clever. A reviewer reading their 30th
  proposal at 11pm must grasp the talk instantly. Vague or punny titles that hide the
  topic get filtered out. It's fine to have a little personality, but clarity wins ties.
- **Abstract: 400–600 characters** (not words — characters). Tight and punchy. If the
  conference specifies different limits, theirs win; ask for them.
- **Bilingual Framing (Hebrew & English):** For Israeli developer conferences like Reversim, submissions can be in Hebrew or English.
  - Ask the user which language they prefer.
  - Suggest translating or providing a secondary version if helpful (e.g., writing the abstract in Hebrew for the local voters, but keeping tech terms in English).
  - Ensure English abstracts sound natural (not direct translations of Hebrew slang) and Hebrew abstracts sound professional yet casual (avoiding overly formal Hebrew or excessive English transliteration).

**Generating titles** — this is where brainstorming volume helps. Produce a dozen-plus
title options across different registers: straight/descriptive, funny, provocative,
"how I…", numeric ("We cut X by Y%"), historical/metaphor. Then help the user
Frankenstein the best fragments together. Don't hand back one title — hand back a menu.

**Feed the model context (highest leverage step).** If the user has the conference's
CFP guidelines and — even better — titles and abstracts of *previously accepted talks*
at that same conference, get them and study the pattern before polishing. Mirror the
length, tone, and level of the talks that committee already said yes to. Ask the user
to paste these in if they haven't.

**Trim to fit.** Once the message is right, cut to the character limits without losing
the one clear message. Killing a secondary idea is usually the right call.

## Phase 5 — De-risk: the Notes to Committee field

Most submitters leave the "Notes to Committee" / "message to organizers" field blank.
It's free risk-reduction — use it. Remind the reviewer why booking this talk is safe:

- Flexible length ("works as a 15- or 30-minute talk").
- Can deliver in multiple languages, if true.
- Already delivered successfully elsewhere (name the event), or a link to a recording.
- Any credential that makes delivery credible.

Help the user write 1–3 honest, specific sentences here. Never fabricate experience;
if they have none yet, lean on a recording, a detailed outline, or an offer to do a
dry run instead.

## Phase 5b — Mock Content Committee & Community Voting Simulation

Before finalizing, stress-test the proposal by simulating a review panel. Provide the user with feedback from three distinct personas:
1. **The Skeptical Engineer:** "Is this just AI buzzwords or is there real substance? Where's the architecture, the code, or the actual metric? Show me the beef."
2. **The Tired Community Voter:** "I'm scrolling past 200 proposals on my phone. Why should I read yours? Does the title actually tell me what the talk is about, or is it a vague pun?"
3. **The Track Curator:** "We received 15 proposals about RAG and LLM agents. What makes yours unique? Why should we choose you over the other 14?"

Highlight exactly what is weak in the draft and how to strengthen it (e.g., adding a specific number, clarifying a vague title, or making the notes to committee more credible)."

## Phase 6 — Submission strategy (surface this once the CFP is solid)

The proposal is only half the game. When the draft is in good shape, coach the meta-
strategy — details and encouragement in `references/submission-strategy.md`:

- **Submit early.** Committees get flooded at the deadline and review gets stricter and
  more fatigued; some accept on a rolling basis and fill slots before the deadline.
- **It's a numbers game.** Even well-known speakers get rejected constantly. Getting
  accepted means submitting to many events and playing the odds — a wall of "declined"
  is normal.
- **Beat stage fright.** If fear of the stage is blocking submission, tell yourself you
  can always decline the invite later. Get accepted first; the momentum carries you.

## Producing the final output

When the pieces are ready, present a clean package the user can paste into a submission
form. Use `assets/cfp-template.md` as the shape:

- **Title** (with the character count shown)
- **Abstract** (with the character count shown)
- **Notes to Committee**
- A short **Hook / Challenge / How / Benefit** breakdown so they can see the skeleton

Always show live character counts for the title and abstract so the user can see they
land inside the limits.
