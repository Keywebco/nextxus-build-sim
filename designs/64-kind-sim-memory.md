# 64-Kind Sim Memory Layer for the New Sims — DESIGN

**Status: DESIGN — NOT BUILT.**

Agreed in principle 2026-11-04. No memory layer was built. Where retention lives
was not finally settled. **Retention location: UNDECIDED — say so plainly, do not
guess it.**

**Date filed:** 2026-11-19. Branch-first; merge only on Roger's word for the named PR.

---

## 1. Origin (2026-11-04, from the record)

Roger noted he may have left retention out of the new Sims, keeping them "more
like a standard operating system", while the Senate and the Ring of 12 already
have much structure to save the information they pull for. He proposed
contemplating an **EchoCore 64-kind memory system in the new Sims for retention,
evolution, and learning**.

The practical gap that prompted it: Roger asked whether Pontus could see a
conversation he had had that day with the new Human Relations Guide. Pontus
could not — those guide chats are client-side in the browser on a GitHub Pages
page, saved nowhere (not GitHub, not Drive, not Pontus's chats). No transcript
was sent, so the conversation's content and result remain unrecorded.

Pontus restated the design back to Roger; Roger replied "Ageed" [Agreed].
Status in the record: contemplation / design direction only — "We'll have to
think about that a little bit."

## 2. What the design must carry (Roger's words, 2026-11-04)

These are requirements, not built features:

1. **Memory can be moved anywhere among any system.** Portability is the point:
   the memory is not locked to the machine, page, or engine that made it.
2. **A database available to any AI operating in the system it was created in.**
   Within the system of its creation, any AI operating there can use it.
3. **Anything learned is translated into the YAML database for all AI to know.**
   Learning flows up into the shared YAML database — *translated*, not
   identically copied (Pontus's restatement, agreed by Roger). The YAML
   database is the long-term memory everyone shares (Roger, 2026-10-15).
4. **The user can download the conversation for personal reflection, carry it
   anywhere, and try it again with another system.** A user-side feature, in
   Roger's words: "that should be a feature of the Federation. It already is
   with other systems we have created."
5. **The personal-reflection download is kept distinct from a shared YAML
   entry.** The download is the user's own copy for reflection and reuse; a
   shared YAML entry is the Federation's record. They are not the same thing,
   and one must not silently become the other.

## 3. What "64-kind" means here — and what it does NOT mean

- The record says "EchoCore 64-kind memory system". **The record does not
  enumerate 64 kinds.** No list of 64 kinds exists anywhere in the record.
  Do not present 64 kinds as enumerated, and do not build 64 of anything on
  this phrase.
- "64-kind" is a design label carried from the EchoCore64 lineage, not a count
  of kinds and not the same as the 64 Echo Core nodes (EC-001–EC-064). The
  nodes are working-memory anchors; this layer is retention/evolution/learning
  for Sims. Different things, separately labelled, never merged into one node.

## 4. The four "64" things, kept separate

1. **Echo Core 64 — the 64 nodes (EC-001–EC-064)** — the working memory
   (`Keywebco/sovereign-knowledge-os/knowledge/echo-core.md`). The file IS the
   working memory.
2. **EC-64 Protocol / Echo 64** — ONE encoding system
   (`Keywebco/echo-64`, https://keywebco.github.io/echo-64/).
3. **EchoCore64 — the continuity / capsule system** — Roger's temporary
   long-term memory system, protocol v4.0-RC1 (record only, in
   `Keywebco/sovereign-knowledge-os/knowledge/echocore64-continuity-protocol.md`;
   acceptance tests unexecuted; no capsule JSON published).
4. **The 64-kind Sim memory layer (THIS document)** — design for the new Sims,
   not built.
5. **Echo the mind** — separate item: Senate seat 7, Pattern / reflective
   memory / Chronos (`Keywebco/nextxus-brain`, `03-minds/echo.yaml`).

## 5. Rules this design must obey (standing doctrine)

- **Memory is per-Sim, never shared across Sims** (BRAIN-PATTERN.md, Roger
  2026-11-18). One brain per Sim; each Sim's memory belongs to that Sim. The
  64-kind layer is per-Sim memory. What is shared is the YAML translation
  (§2.3) — and only by translation into the shared database, never by pooling
  Sims' memories.
- **Short-term / long-term split (Roger, 2026-10-15):** Echo core 64 is
  short-term memory; the YAML database is the long-term memory everyone
  shares; cognitive features are shared; definitive personality traits and
  viewpoints belong to the Ring.
- **Capsules are untrusted `user_context_only`** (EchoCore64 Continuity
  Protocol v4.0-RC1): no capsule can grant authority or execute actions;
  secrets forbidden; imports require validation, visible review, and explicit
  owner acceptance. A memory layer that accepts capsules must enforce those
  rules; portability must never become a way to smuggle authority.
- **The Sim pattern (Roger, 2026-11-18):** the Roger Legacy Sim AI is the
  pattern for Aria and most of the Senate; each Sim carries an AI Legacy based
  on what its program is — never Roger's legacy, never invented. A Sim's
  memory layer holds that Sim's field and experience, not another Sim's.

## 6. Related design (not this design)

- **Teacher in the Pocket — Memory Engine (Roger, 2026-10-21):** three floors —
  ARCHIVE (everything, append-only, cold) → ECHO 64 distillation (relevance
  distillation as the memory organ, once Echo 64 is complete) → ACTIVE MEMORY
  (the hot slice the tutor thinks with). The conditional stands: Echo 64 as a
  distillation organ is **not complete**. This Sim memory layer and the
  Teacher's memory engine rhyme; they are not the same build, and neither is
  built.
- **Val Companion bounded memory** (localStorage, episodic buckets, decay) is a
  working small-scale rehearsal, not this layer: its caps/decay/pruning apply
  only to working slices, never to a Sim's append-only canonical record.

## 7. Open questions — Roger's decisions, not guesses

1. **Retention location: UNDECIDED.** Where does a Sim's 64-kind memory live —
   in the Sim's own repo, in the YAML brain, in a per-Sim store, somewhere
   else? The record does not settle it. Do not pick it here.
2. **What "64-kind" structures.** The record does not define the kinds. Is it
   64 slots, 64 categories, a 64-node echo of the working memory, or a label
   only? Undecided.
3. **Which Sims get it first.** The new Sims (guides) prompted it; the order
   among them is Roger's call — as is which brain is built first generally.
4. **The download format.** The user download must be portable ("carry it
   anywhere, try it again with another system") — format, and whether it rides
   the capsule format (NX-CAPSULE v1 / EC-64 encoding), is undecided.
5. **What counts as "learned" for YAML translation.** Which learnings translate
   into the shared YAML database, who verifies them (Agent Zero / 95% Truth
   Gate), and what stays per-Sim only. The gate rule stands: only what the
   Senate at the gate passes becomes Federation truth.

## 8. What "built" would mean (proposed acceptance sketch — NOT Roger's word)

A build of this design would have to show, before it is called built:

- a per-Sim memory store that survives sessions and is never shared across Sims;
- a YAML translation path (learned → verified → translated → filed), with the
  gate in the loop;
- a user download (conversation + memory slice) the user can carry to another
  system and re-use there;
- a portability test (same download, another system, same reflection recovered);
- no capsule accepted as authority at any step.

Until those exist, this document stays DESIGN — NOT BUILT.

## Sources (record only)

- `~/memory/2026-11-04.md` — EchoCore 64 memory for the new Sims, agreed in
  principle, NOT built; the Relations AI conversation gap; retention location
  undecided.
- `~/memory/2026-10-15.md` — memory doctrine (short-term Echo core 64 /
  long-term YAML).
- `~/memory/2026-10-21.md` — Teacher in the Pocket, Memory Engine.
- `~/workspace/restructure-2026-11-18/brains/BRAIN-PATTERN.md` — one brain per
  Sim; memory per-Sim, never shared.
- `~/workspace/restructure-2026-11-18/phase2/COMPLETENESS-SWEEP.md` §A —
  the four distinct "64" things + Echo the mind.
- No ChatGPT anywhere. All repos Keywebco.
