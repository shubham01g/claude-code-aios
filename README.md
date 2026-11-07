# AIOS: how my AI operating system is built

You commented "AIOS," so here's the setup.

I run my agency from one folder in Claude Code. It knows who I am, what my agency sells and what I'm working on this week. Most days I don't open ten different tools. I just talk to it.

There's no magic in it. It's a folder with the right files in the right places. Here's how it's built, plus a [template](template/) to start yours today.

## The folder

```
my-aios/
├── CLAUDE.md              ← the brain: who I am, my goals, how to work with me
├── context/
│   ├── about-me.md        ← my role, strengths, what I want off my plate
│   ├── about-business.md  ← what we sell, to whom, real proof
│   └── priorities.md      ← this week + this quarter (updated weekly)
├── references/
│   ├── voice.md           ← real samples of how I write
│   ├── arise-method.md    ← the framework I use to decide what to automate
│   └── <tool>-api.md      ← one guide per connected tool, researched once
├── decisions/
│   └── log.md             ← every decision + WHY, append-only
├── connections.md         ← every tool it can reach, and how
├── archives/              ← old stuff. Never delete, move here.
└── .claude/skills/        ← the abilities (one folder per skill)
```

## The 5 parts that matter

**1. `CLAUDE.md`: the brain.** Claude Code reads this file at the start of every session. Mine says who I am, my revenue goal, my 90-day priorities, my biggest pain, and how I want answers (direct, no fluff). Without it, every chat starts from zero.

**2. `context/`: the facts.** What my agency sells, who buys, and the real proof (client names, real numbers). Claude only uses numbers from here, so it never invents results.

**3. Skills: the hands.** Each skill is a repeatable job. Mine include:
- one that finds my next YouTube video from competitor data ([IDEAS](https://github.com/shubham01g/claude-code-ideas))
- one that edits my videos and reels ([VIDEO](https://github.com/shubham01g/claude-code-video), [EDIT](https://github.com/shubham01g/claude-code-edit))
- one that runs my cold email system ([COLD](https://github.com/shubham01g/claude-code-cold))

**4. `decisions/log.md`: the memory.** Every real decision goes in with the *why*. Three months later, Claude still knows why we dropped a lead source or changed an offer, so we don't make the same mistake twice.

**5. `/level-up`: the growth loop.** Every week it interviews me and finds one more task to automate. One per week, so it actually gets finished. ([LEVELUP](https://github.com/shubham01g/claude-code-levelup))

## Start yours in 15 minutes

1. Download this repo (green **Code** button → **Download ZIP**).
2. Copy the [`template/`](template/) folder somewhere and rename it, e.g. `my-aios`.
3. Open that folder in Claude Code and paste:
   ```
   Interview me to fill in CLAUDE.md and everything in context/.
   Ask one question at a time. Use my real answers only, never invent numbers.
   ```
4. Paste 3–5 things you've actually written into `references/voice.md`.
5. Run `/level-up` to find your first automation.

Then add one skill a week. After a couple of months it runs a real part of your business.

## Want one built for your business?

That's what my agency does. We set up the folder, connect your tools and build the skills for the work you repeat every week. DM me on Instagram: [@shubham_gunjal_ai](https://instagram.com/shubham_gunjal_ai)
