# AI Use Disclosure — Setup Exercise (search/ personal layer)

**Student:** Laksh Dhamija
**Date:** 2026-06-25
**Tools used:** Claude Code (agent) — extraction, drafting, and formatting.

## What the AI did
- Extracted `search/resume.json` from my existing CV (`cv.md`) into structured, typed records.
- Drafted `search/profile.yml` from my intake answers.
- Drafted the `search/gaps.md` table (gaps, evidence, plan).

## What I did (the judgment the AI cannot do)
- **Attested and corrected** the record: confirmed which extracted facts were true and fixed the ones that weren't.
- Supplied the **visa/timeline facts** (F-1, pre-OPT, 0 unemployment days, DSO-confirmed STEM) and the search **preferences** (geography, sectors, company size, sponsorship gate).
- **Killed** a gap the agent generated that does not apply to me, and signed off on the files.

## What the AI could NOT do (specific instance)
The agent imported my **Radius** role as a full-time **"Software Engineer."** Nothing in the résumé text told it otherwise — but I know it was a **co-op**, and that distinction matters (it changes how the role reads to a recruiter and how the engine should weight it). I corrected the title and `employment_type` to `co-op`.

A second instance: the skills list included **Kafka, Spark, Airflow, and Jenkins**. The agent took them at face value because they were in the source text. Only I knew they were aspirational — not tools I've used in production — so I removed them. The agent had no way to tell a real skill from a hopeful one; that required my knowledge of my own record.

This is the course's point applied inward: extraction is fluent, but only the source of truth (me) can catch where the fluent output is wrong about my own situation.
