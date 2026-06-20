# Glossary

Shared vocabulary for the Gareeb Showcase repository. Terms are defined from a **product and behavioral design** perspective — not implementation detail.

---

## A

### Awareness Journey

A structured product flow — onboarding, daily use, monthly rollover — designed to build financial self-understanding over time rather than one-time budget setup.

### Ambient Feedback

Non-verbal product response: visual mood shifts, companion state changes, environmental color — used especially in Watcher personality mode.

---

## B

### Behavioral Finance Companion

Gareeb's product category. A digital product that helps users understand spending **behavior** through pattern recognition, reflection, and character-driven feedback — distinct from ledger or budgeting tools.

### Behavior Engine

The conceptual system that converts spending signals, mood context, and historical patterns into timed, personality-appropriate responses. See [Behavior Engine](../architecture/behavior-engine.md).

### Behavior Moment

The atomic unit of Gareeb's product model: a spending event plus its contextual metadata (category, mood, time, note) — treated as a moment in a narrative, not merely a transaction.

---

## C

### Calm (Personality)

The default Gareeb personality. Prioritizes de-escalation, gentle pacing, and safe return visits. See [Personalities](./personalities.md).

### Character-Driven Feedback

Insight delivered through the companion's voice and visual state rather than through impersonal alerts or raw charts.

### Companion

The persistent character presence in Gareeb — a mirror for behavioral patterns, not a financial advisor or authority figure.

### Context Capture

The product act of recording mood, category, time, and optional notes alongside a spending amount.

### Critical Stage

The highest level on the shared behavioral intensity ladder — sustained escalation warrants the strongest (still non-shaming) response for the selected personality.

---

## D

### Daily Reflection

A short mood note or end-of-day emotional check-in that creates a parallel timeline to spending data.

---

## E

### Emotional UX

Deliberate use of color, motion, copy pacing, and silence to reduce finance-related anxiety and support reflection.

### Escalation Curve

How quickly and intensely a personality moves through behavioral stages (Normal → Suspicious → Warning → Critical).

---

## H

### Honest (Personality)

A Gareeb personality optimized for direct, consistent pattern confrontation without insult. See [Personalities](./personalities.md).

---

## I

### Insight Timing

Product decision about *when* to surface a pattern — balancing relevance, attention, and personality fit.

---

## M

### Mood Snapshot

The emotional label attached to a spending moment at capture time — used for pattern correlation and reflection, not clinical assessment.

---

## N

### Normal Stage

Baseline behavioral state — no elevated pattern concern. Companion presence reflects personality default.

---

## P

### Pattern Detection

The product capability of recognizing repetition across category, time, mood, and amount clusters. See [Pattern Detection](../architecture/pattern-detection.md).

### Pattern Memory

Historical retention of behavioral clusters that informs whether a current moment is novel or repeating.

### Personality Mode

User-selected companion voice and response philosophy (Calm, Honest, Watcher).

### Product Mirror

Conceptual framing: the companion reflects behavior back to the user in a chosen tone — externalizing self-bias.

---

## R

### Reflective Insight

A readable observation that connects data to behavior ("this showed up again," "late-night orders clustered") without prescribing a specific action.

### Response Composition

The process of selecting feedback type (verbal, visual, ambient), intensity, and copy pool based on personality and behavioral stage.

---

## S

### Shame-First Language

Copy framing that assigns moral failure to spending — explicitly avoided in Gareeb. Contrast with [Reflective Insight](#reflective-insight).

### Spending Rhythm

The user's emergent pace of spending over days or weeks — a behavioral signal more meaningful than a single daily total.

### Suspicious Stage

Early pattern emergence — the system notices something forming but does not yet treat it as established repetition.

---

## T

### Threshold Philosophy

Personality-specific sensitivity settings that determine when behavioral stages advance — Calm tolerates more drift; Honest advances faster.

### Tone Calibration

Matching message intensity and style to both personality mode and user emotional context.

---

## W

### Warning Stage

Established repetition or clear drift — warrants explicit surfacing in Calm and Honest; often visual-first in Watcher.

### Watcher (Personality)

A Gareeb personality optimized for quiet observation and minimal copy. See [Personalities](./personalities.md).

---

## Related Documents

- [Product Context](./product-context.md)
- [Docs Index](./README.md)
