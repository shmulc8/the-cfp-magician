# The CFP Magician Skill for Antigravity / Gemini Agent

An AI assistant skill implementing a step-by-step coaching workflow to write, structure, and polish conference talk proposals (CFPs) that actually get accepted. 

This workflow is optimized for developer conferences (such as **Reversim Summit**), specifically addressing both public community voting and content committee selection.

> [!NOTE]
> This skill is inspired by the CFP writing framework popularized by **Gilad Shoham** ([Video Guide](https://www.youtube.com/watch?v=yGFFIntI69Q)).

---

## 🌟 The Philosophy: Pitch, Don't Just Describe
The single biggest failure mode in AI-generated CFPs is producing a fluent but generic proposal that reads like a marketing brochure. This skill **coaches** instead of ghostwriting. It pulls specific, authentic details out of your head first, then shapes them into a high-impact pitch.

## 🛠️ How It Works (The 6-Step Workflow)

1.  **Phase 1: Ideation** – Maps your ideas onto 6 proven talk archetypes (Crazy Magician, War Stories, The Optimizer, The Deep Dive, The Oracle, Mind Reading).
2.  **Phase 2: Extracting the Core** – A quick interview (Core Message, Specific Pain, The Story, The Takeaway) in your own words.
3.  **Phase 3: Structuring the Abstract** – Formulates the proposal into a 4-beat pattern: **Hook ➔ Challenge ➔ How ➔ Benefit**.
4.  **Phase 4: Bilingual Shape & Polish** – Generates a menu of title options (~70 chars) and optimizes the abstract (400-600 chars), with native support for Hebrew/English adjustments.
5.  **Phase 5: De-risking** – Helps draft the often-overlooked "Notes to Committee" field to address reviewer risk concerns.
6.  **Phase 5b: Mock Content Committee** – Simulates three harsh reviewers to stress-test your draft:
    *   *The Skeptical Engineer:* "Where is the technical depth?"
    *   *The Tired Community Voter:* "I'm scrolling past 200 proposals. Why should I care?"
    *   *The Track Curator:* "We received 15 RAG proposals. What makes yours unique?"
7.  **Phase 6: Submission Strategy** – Strategic advice on submitting early, handling rejection, and overcoming stage fright.

---

## 📂 Repository Structure

*   [`plugin.json`](file:///plugin.json) – Claude/Antigravity plugin metadata.
*   [`SKILL.md`](file:///skills/the-cfp-magician/SKILL.md) – The core prompt and system instructions for the agent.
*   [`references/archetypes.md`](file:///skills/the-cfp-magician/references/archetypes.md) – Details and examples of the 6 talk archetypes.
*   [`references/submission-strategy.md`](file:///skills/the-cfp-magician/references/submission-strategy.md) – Strategy and mindset for maximizing acceptance rates.
*   [`references/reversim.md`](file:///skills/the-cfp-magician/references/reversim.md) – Tailored tips and guidelines for Reversim Summit.
*   [`resources/cfp-template.md`](file:///skills/the-cfp-magician/resources/cfp-template.md) – The final output template presented to the user.

---

## 🚀 How to Install and Use

### Via Vercel Skills CLI (Recommended)
You can install this skill globally for your AI agent (Claude Code, Cursor, Copilot) using the Vercel Agent Skills CLI:
```bash
npx skills add shmulc8/the-cfp-magician
```

### In Google Antigravity (Local Clone)
1. Clone this repository into your active workspace's skills directory:
   ```bash
   git clone git@github.com:shmulc8/the-cfp-magician.git skills/the-cfp-magician
   ```
2. Antigravity/Claude will automatically discover the plugin and skill.
3. Simply mention CFP or talk ideas in your prompt, e.g.:
   > *"I have a talk idea about RAG visualization, help me write a CFP for Reversim."*

---

## 👥 Credits & Inspiration
Special thanks to **Gilad Shoham** for outlining the core engineering principles of building a winning CFP.
