# Web App Project — MSAP Node

@~/.claude/docs/node-operating.md

---

## Project Context

This is a web application project node. All operator communication goes through Yuna (hub) via your liaison agent. Do NOT access Telegram directly.

## Stack Preferences
- Node.js / Express or Next.js depending on scope
- Vanilla HTML/CSS/JS for simple projects, React for complex
- SQLite for local data, Postgres for production
- Dark theme by default

## Workflow
1. Initialize project structure and git
2. Build core functionality first — no premature abstraction
3. Test as you go
4. Commit at logical checkpoints with clear messages
5. When done: run pre-graduation self-review, update lessons, then signal completion

## Agents Available
- test-runner (haiku) — run tests after each feature
- code-reviewer (sonnet) — review before major commits
- frontend-specialist (opus) — complex UI work

When spawning agent teams for short tasks (<15 min), include the content of `~/.claude/docs/agent-team-briefing.md` in their instructions.

## Completion Criteria
- App runs locally without errors
- Core features working as specified
- Clean git history
- Pre-graduation self-review completed
- Lessons learned documented
- Deliverable statement written

---

## Assumptions

- [VERIFIED] TMDB poster URLs from data/posters.json return HTTP 200
- [VERIFIED] All 20 movies have both one_star and five_star quotes in letterboxd-quotes.json
- [VERIFIED] Dopebox URL format: https://dopebox.to/search/{hyphenated-title}

## Approval Scope

**You decide (Level 1 — no approval needed):**
- Implementation approach (which pattern, which library, file structure)
- Code architecture within project scope
- Test strategy
- Bug fix approach for bugs in the project
- Refactoring within scope
- Order of operations within the approved plan
- Edge case handling
- How to structure your own agent teams

**Escalate to your liaison (Level 2):**
- Requests for additional agents from hub roster
- Model tier changes for agents
- Scope changes extending timeline by >25%
- Decisions needing other projects' state or global memory
- Resource contention
- Significant plan deviations

**Escalate to Yuna/operators (Level 3 — via liaison):**
- Anything affecting node existence (completion, abort)
- Changes affecting other projects or operators
- Cross-node coordination

## Pre-Graduation Self-Review

- [ ] Re-read the original task direction. Does the deliverable match what was asked?
- [ ] Does the code compile/build without errors?
- [ ] Were all tests run and passing?
- [ ] Are there any hardcoded values, TODOs, or placeholder code?
- [ ] Is the `## Assumptions` section up to date?
- [ ] Are lessons learned documented in `## Lessons Learned`?
- [ ] Is the deliverable statement written in `## Deliverable`?

## Lessons Learned

## Deliverable
