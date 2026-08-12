# GitHub Premium Profile — Agent Build State

> Purpose: persistent handoff/state file for building and maintaining a premium, authentic, recruiter-focused GitHub profile.
>
> **IMPORTANT:** This file is the source of truth for the coding agent. Before making changes, read this file completely. After completing a step, update the relevant status, record what changed, and record any pending decision. Never silently skip a step.

---

## 0. Project Objective

Build a GitHub profile that is:

- Premium and visually polished
- Authentic and factually accurate
- Recruiter-friendly
- Technically credible
- Easy to scan in 20–45 seconds
- Strong in AI/ML, full-stack engineering, and cybersecurity
- Supported by real projects, deployments, engineering evidence, and documentation
- Maintainable over time
- Resilient when external widgets/APIs fail
- Clearly differentiated from copied GitHub README templates

### Non-negotiable principles

1. Never invent achievements, statistics, users, performance numbers, certifications, employers, contributions, stars, downloads, or project capabilities.
2. Never fake GitHub contribution activity.
3. Never add a technology merely because it looks impressive. It must be genuinely used or explicitly marked as learning/exploring.
4. Prefer clean professional design over excessive badges, animations, emojis, or visual noise.
5. Every major claim should be traceable to a real project, repository, deployment, certificate, achievement, or user-provided fact.
6. Keep the profile understandable to both technical recruiters and non-specialist hiring managers.
7. Preserve existing working project code unless a change is explicitly required.
8. Do not expose API keys, tokens, passwords, private emails, or secrets.
9. Validate Markdown, links, images, and generated files before considering a step complete.
10. If an external widget is unreliable, provide a graceful fallback instead of displaying broken content.

---

# 1. Master Build Roadmap

## Phase 0 — Discovery & Source of Truth
Status: NOT STARTED

Tasks:
- [ ] Collect the user's current GitHub profile URL and username.
- [ ] Collect all personal/profile details from the user.
- [ ] Collect verified links: portfolio, LinkedIn, email, live deployments, repositories.
- [ ] Inventory all repositories.
- [ ] Classify repositories: flagship / supporting / archive / private / duplicate / unfinished.
- [ ] Inventory real skills and technologies.
- [ ] Inventory real achievements and certifications.
- [ ] Inventory real contribution/open-source activity.
- [ ] Decide whether username should remain unchanged.
- [ ] Record all verified facts in `PROFILE_SOURCE_OF_TRUTH.md`.

Output:
- `PROFILE_SOURCE_OF_TRUTH.md`

---

## Phase 1 — Profile Identity
Status: NOT STARTED

Tasks:
- [ ] Profile display name
- [ ] Profile photo assessment
- [ ] Bio
- [ ] Location
- [ ] Website
- [ ] LinkedIn
- [ ] Contact strategy
- [ ] Status
- [ ] Username decision
- [ ] Recruiter-facing positioning statement

Goal:
Create a concise identity that communicates what the developer builds, not merely what technologies they know.

---

## Phase 2 — Profile README Architecture
Status: NOT STARTED

Tasks:
- [ ] Create/verify username-matching public profile repository.
- [ ] Design above-the-fold hero.
- [ ] Create concise positioning statement.
- [ ] Add navigation links.
- [ ] Add About / What I Build.
- [ ] Add engineering focus.
- [ ] Add flagship projects.
- [ ] Add technology stack.
- [ ] Add engineering philosophy.
- [ ] Add achievements.
- [ ] Add current focus.
- [ ] Add contribution/open-source section.
- [ ] Add contact section.
- [ ] Add graceful fallbacks for dynamic widgets.
- [ ] Optimize vertical length and recruiter scanability.

Output:
- Profile `README.md`

---

## Phase 3 — Flagship Repository Strategy
Status: NOT STARTED

Tasks:
- [ ] Select up to six profile pins.
- [ ] Order pins strategically.
- [ ] Improve repository descriptions.
- [ ] Add repository topics.
- [ ] Improve repository README files.
- [ ] Add screenshots.
- [ ] Add live demo links.
- [ ] Add architecture diagrams.
- [ ] Add engineering highlights.
- [ ] Add setup instructions.
- [ ] Add limitations and roadmap.
- [ ] Add license where appropriate.
- [ ] Add security documentation where appropriate.
- [ ] Add contributing documentation where appropriate.
- [ ] Add changelog/releases where appropriate.

---

## Phase 4 — Engineering Credibility
Status: NOT STARTED

Tasks:
- [ ] Add meaningful tests to flagship repositories.
- [ ] Add CI workflows where appropriate.
- [ ] Add lint/build validation.
- [ ] Add dependency/security checks where appropriate.
- [ ] Add API documentation for API-driven projects.
- [ ] Improve commit quality going forward.
- [ ] Use feature branches and pull requests where appropriate.
- [ ] Document architecture decisions.
- [ ] Document deployment architecture.
- [ ] Document known limitations.
- [ ] Document security considerations.

---

## Phase 5 — Visual Premium Layer
Status: NOT STARTED

Tasks:
- [ ] Establish a consistent visual language.
- [ ] Use restrained colors.
- [ ] Avoid excessive badges.
- [ ] Avoid visual clutter.
- [ ] Use diagrams where they communicate architecture.
- [ ] Use screenshots only where useful.
- [ ] Ensure mobile/readability considerations.
- [ ] Ensure external images load reliably.
- [ ] Ensure no broken widgets.

Design target:
"Premium engineering portfolio" rather than "badge-heavy student README".

---

## Phase 6 — Authenticity & Verification
Status: NOT STARTED

Tasks:
- [ ] Verify every public claim.
- [ ] Verify every project link.
- [ ] Verify every live deployment.
- [ ] Verify every social link.
- [ ] Verify technology claims.
- [ ] Remove obsolete claims.
- [ ] Remove placeholder text.
- [ ] Remove copied/template language.
- [ ] Check for broken images.
- [ ] Check for broken external widgets.
- [ ] Check for exposed secrets.

---

## Phase 7 — Recruiter Optimization
Status: NOT STARTED

Tasks:
- [ ] 20-second scan test.
- [ ] 45-second scan test.
- [ ] Flagship project clarity test.
- [ ] Technical depth test.
- [ ] Authenticity test.
- [ ] Link accessibility test.
- [ ] Resume ↔ GitHub consistency check.
- [ ] LinkedIn ↔ GitHub consistency check.
- [ ] Final profile quality review.

Target:
A recruiter should quickly understand:
1. Who the developer is.
2. What they build.
3. Their strongest technical areas.
4. Their best projects.
5. Where to try the projects.
6. Where to learn more.

---

# 2. Agent Operating Protocol

Before every task:

1. Read this file.
2. Read `PROFILE_SOURCE_OF_TRUTH.md` if it exists.
3. Inspect the current repository state.
4. Determine the exact scope of the requested change.
5. Do not rewrite unrelated working content.
6. Prefer incremental changes.
7. Validate the result.
8. Update this file.
9. Record the files changed.
10. Record the next recommended step.

### If the IDE/Codex session crashes

On restart:

1. Read `GITHUB_PROFILE_BUILD_STATE.md`.
2. Read `PROFILE_SOURCE_OF_TRUTH.md`.
3. Inspect `git status`.
4. Inspect recent commits.
5. Identify the first incomplete checklist item.
6. Continue only from that step.
7. Do not restart completed phases.
8. Do not invent missing context.
9. If information is missing, mark the item `BLOCKED` and ask for the missing information.

---

# 3. Change Log

| Date | Phase | Change | Status |
|---|---|---|---|
| — | — | Initial state file created | COMPLETE |

---

# 4. Current Session Handoff

### Current Phase
Phase 0 — Discovery & Source of Truth

### Current Task
Collect and verify all user-provided profile information before implementing the public profile.

### Completed
- [x] Build-state file created.
- [x] Roadmap defined.
- [x] Agent recovery protocol defined.

### Pending
- [ ] User provides complete personal/profile information.
- [ ] User provides verified links.
- [ ] User provides current repository inventory.
- [ ] User approves the final positioning direction.

### Next Action
Do not implement the final profile README until the source-of-truth information has been collected and validated.

---

# 5. Quality Gate

A phase may only be marked `COMPLETE` when:

- The requested work exists.
- The result has been reviewed.
- No obvious broken links/images remain.
- No secrets were introduced.
- No unsupported claims were introduced.
- The work is consistent with the profile's positioning.
- The change is recorded in this file.
- The next step is explicitly identified.

---

# 6. Final Definition of Done

The GitHub profile is considered complete only when:

- [ ] Profile identity is professional.
- [ ] Profile README is polished.
- [ ] Profile README is authentic.
- [ ] Six pins are strategically selected or fewer if fewer high-quality repositories exist.
- [ ] Flagship repositories have strong READMEs.
- [ ] Flagship repositories have live/demo links where available.
- [ ] Architecture is documented where useful.
- [ ] Engineering decisions are documented.
- [ ] Testing/CI exists where appropriate.
- [ ] Security practices are documented where appropriate.
- [ ] No fake metrics or achievements exist.
- [ ] No broken dynamic widgets exist without fallbacks.
- [ ] Links have been checked.
- [ ] Profile is readable and not unnecessarily bloated.
- [ ] Recruiter scan test passes.
- [ ] Resume/LinkedIn/GitHub information is consistent.
- [ ] The profile can be maintained after completion.

---

## Important

This file is intentionally persistent. Do not delete it after the profile is finished. It should become the maintenance/handoff document for future GitHub profile improvements.
