# Universal learnings

Cross-project insights promoted from individual client learnings-queue.md files. These are battle-tested principles that work across multiple clients and industries.

---

## How this works

1. Individual project learnings are captured in each client's `learnings-queue.md`
2. Learnings marked as "universal principle" get reviewed periodically
3. Confirmed universal insights are promoted here
4. This file feeds back into master guidelines (Smart Writing Guidelines, Messaging Framework CLAUDE.md, etc.)

---

## Messaging & copywriting

### VBF framework: values → benefits → features sequence
**Source:** Cogent Analytics discovery (2025-11-12)
**Principle:** Lead with VALUES (reader's problem/pain), then BENEFITS (how their world improves), then FEATURES (what you actually do). This isn't just "benefits over features" - it's the specific three-part sequence that matters.

### VBF stats pattern
**Source:** Connection Lab homepage (2025-12)
**Principle:** Stats work better with storytelling headlines above the number. Structure: `[Value headline] → [Big number] → [Simple label]`. Example: "A decade of practice together → 11 → Years of practice". Transforms stats from data dump to narrative.

### Human headlines over generic labels
**Source:** Connection Lab homepage (2025-12)
**Principle:** "FAQ" is boring. "Questions we hear" tells a story. Section headers should pay off the brand voice, not default to convention. Every label is a chance to reinforce messaging. Low effort, high brand payoff.

### Direct challenge to failed solutions
**Source:** Connection Lab + PowerTrack cross-project (2025-12)
**Principle:** When your A+ customer has been burned by previous solutions, name those solutions directly and call out their failures. "Your MBTI didn't change anyone's behavior." "Generic PM software doesn't understand electrical construction." Credibility comes from acknowledging what they already know didn't work.

### Core differentiator repetition
**Source:** Connection Lab + PowerTrack cross-project (2025-12)
**Principle:** Identify your single core differentiator and repeat it relentlessly. "Practice over performance" appears 20+ times in Connection Lab framework. "Purpose-built for electrical construction" throughout PowerTrack. Repetition creates recognition. Mention once = forgettable. Mantra-style repetition = positioning.

### Discovery questions: ground in concrete examples
**Source:** Cogent/Connection Lab (2025-07-30)
**Principle:** Frame discovery questions to elicit concrete examples from the past rather than hypotheticals. "What exact words did a customer use?" triggers specific memory recall vs generic aspirational responses.

### "What would competitors say?" discovery technique
**Source:** Cogent Analytics discovery (2025-11-12)
**Principle:** Asking "What would make your competitors think 'how the hell did they do that?'" reveals more honest differentiators than asking clients directly what makes them special.

---

## Workshops & meetings

### Slides over interactive tools
**Source:** Megan sync (2025-07-30)
**Principle:** Default to slide-based workshop discussions rather than interactive collaborative tools. Slides keep participants present; interactive tools require teaching overhead that pulls attention from content.

### Pre-work time constraints
**Source:** Workshop planning (2025-07-30)
**Principle:** When sharing pre-work questions, include explicit time constraints ("maximum one hour to prepare") to balance preparation depth with authentic responses.

---

## Design process

### Wireframe feedback language: "layout" not "design"
**Source:** Client feedback patterns (2025-07-30)
**Principle:** Use "layout" and "structure" instead of "design" in wireframe reviews. Clients naturally give visual/aesthetic feedback, then feel redirected when told "that's for design phase." Better language prevents friction.

### Maintenance burden test
**Source:** Connection Lab homepage (2025-12)
**Principle:** When designing sections for small teams, ask "How much upkeep does this require?" Episode cards, dynamic content, CMS-heavy features = ongoing work. Static touts, evergreen copy = set and forget. Small teams need the latter. Don't create work they can't sustain.

### CTA context matching
**Source:** Connection Lab homepage (2025-12)
**Principle:** CTAs should match where user IS in the journey. Homepage CTAs pointing to program pages should be discovery-oriented ("Bring this to your team"), not conversion-oriented ("Buy now"). Discovery pages get discovery CTAs; conversion pages get conversion CTAs.

### Secondary content simplicity (podcast touts, etc.)
**Source:** Connection Lab homepage (2025-12)
**Principle:** Secondary content sections (podcast tout, blog preview, etc.) should feel instantly familiar and match effort to the section's job. Podcast tout = name, tagline, subscribe buttons. That's it. The job is "hey, we have a podcast" not "sell you on the podcast."

---

## Client experience

### Tool selection as brand touchpoint
**Source:** PM tool discussions (2025-07-30)
**Principle:** PM and collaboration tools are brand touchpoints, not just internal efficiency. Small improvements in client-facing tools (10% better) create outsized satisfaction gains (30-50% happier).

---

## Customer segmentation

### Three-story customer segmentation
**Source:** Cogent Analytics discovery (2025-11-12)
**Principle:** Organize customer types as "three stories" ranked by both conversion difficulty AND lifetime value. Forces prioritization: easiest-to-convert (lowest value), hardest-to-convert (highest value), and aspirational (ego-driven but unstable).

### A+ customer specificity
**Source:** Connection Lab + PowerTrack cross-project (2025-12)
**Principle:** Don't describe A+ customer in vague terms ("small to medium businesses," "leaders"). Use specific revenue ranges ($400M-$1B), specific project types (multi-year data center installations), specific psychographics ("in their 40s, remembers when people knew how to talk to each other"). Specificity creates targeting clarity.

### "Skeptical but ready" burned-buyer framing
**Source:** Connection Lab + PowerTrack cross-project (2025-12)
**Principle:** When your market has been burned by previous solutions, name the skepticism explicitly. "Skeptical but desperate" (Connection Lab). "Skeptical but ready for real solutions" (PowerTrack). This phrasing honors their wariness while positioning your solution as the real answer.

---

## Automation & system ops

### AppleScript `activate` causes focus-stealing
**Source:** LFI Operations debugging (2025-12-10)
**Principle:** Never use `activate` in background automation AppleScripts. It steals focus from whatever the user is doing. Instead, target the app directly with `tell application "System Events" to tell process "AppName"`. Combined with `KeepAlive` restart behavior, `activate` in a failing script creates rapid focus-stealing loops.

### Granola MCP returns metadata but not transcripts
**Source:** LFI Operations debugging (2025-12-10)
**Status:** Known bug as of 2025-12. Workaround: Use locally synced transcripts in `_ Operations/granola/_archived-raw-exports/` instead of relying on MCP `get_meeting_transcript` calls.

---

## Pending review

[Learnings awaiting confirmation across multiple projects before promotion]

---

## Update log

| Date | Learning added | Source project |
|------|----------------|----------------|
| 2025-12-15 | VBF stats pattern | Connection Lab |
| 2025-12-15 | Human headlines over generic labels | Connection Lab |
| 2025-12-15 | Maintenance burden test | Connection Lab |
| 2025-12-15 | CTA context matching | Connection Lab |
| 2025-12-15 | Secondary content simplicity | Connection Lab |
| 2025-12-15 | Direct challenge to failed solutions | Cross-project |
| 2025-12-15 | Core differentiator repetition | Cross-project |
| 2025-12-15 | A+ customer specificity | Cross-project |
| 2025-12-15 | Skeptical but ready framing | Cross-project |
| 2025-12-10 | AppleScript activate focus-stealing fix | LFI Operations |
| 2025-12-10 | Granola MCP transcript bug workaround | LFI Operations |
| 2025-12-06 | Initial population from Cogent learnings-queue | Cogent Analytics |
