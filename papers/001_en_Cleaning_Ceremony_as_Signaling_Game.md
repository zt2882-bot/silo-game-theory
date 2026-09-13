# Paper 1: The Cleaning Ceremony as a Signaling Game

**Core game**: Administration vs. residents, signaling and Bayesian updating
**Tools**: signaling game, commitment problem, fear as a public good
**Show anchor**: cleaners sent out, lens wiped, residents watching, death broadcast
**Core thesis**: the cleaning ceremony is not punishment but an information-control device — it mass-produces fear through public execution
**Falsifiable corollary**: a single surviving cleaner collapses the signal system immediately

---

## Abstract

The most harrowing image in *Silo* is the cleaning ceremony: a person who asks to "go out" is suited up, pushed through the airlock, led to the lens, and made to wipe the sensor before dying in full view of everyone. The common reading treats this as punishment — killing one to warn many. This paper argues that reading is wrong. The cleaning ceremony is fundamentally a **signaling game**: what the administration manufactures is not a signal about "what happens to rule-breakers," but a signal about "the outside is death." Its real product is not deterrence but **fear** — a public good that must be continuously produced and maintained. And its fatal weakness lies precisely in the fact that **the signal is manufactured by the administration, not emitted by the environment itself.**

## 1. The Scene: A Designed Death

The silo has a strict rule: anyone who expresses the wish to "go out" is granted it — but instead of being released, they are sent to clean. The cleaner dons a suit, steps through the airlock, wipes the lens that relays the "outside world" into the silo, and collapses. The whole event is broadcast to the entire silo: a public death, livestreamed.

What residents see is the equation: *going out = death*. This equation is replayed until it is carved into every generation's beliefs.

## 2. The Model

There are two classes of players:

- **Administration (M)**: knows the true state of the outside (toxic or safe), controls how information is presented.
- **Residents (R)**: do not know the outside state, and can only update beliefs from observed signals.

**Signal structure**: residents observe the event "a cleaner died." But this event has two possible generative mechanisms:

1. **Environmental mechanism**: the outside is genuinely toxic, and the cleaner died from the environment.
2. **Administrative mechanism**: the outside may not be fatal; the administration manufactured the death through suit defects, airlock design, or outright selective execution.

The crucial point: **residents cannot distinguish the two mechanisms.** The signal "a cleaner died" is thus a variable the administration can manipulate.

**Bayesian updating**: let $p$ be the residents' prior that "the outside is safe." After observing one cleaner death, the posterior is:

$$p' = \frac{p \cdot q}{p \cdot q + (1-p) \cdot r}$$

where $q$ is the probability a cleaner still dies when the outside is safe (i.e., the administration's manufacturing probability), and $r$ is the probability a cleaner dies when the outside is toxic (near 1). When the administration can reliably manufacture death ($q \to 1$), the residents' posterior drifts toward "toxic" regardless of the true state. **Signal decouples from truth.**

## 3. Equilibrium Analysis: Fear as a Public Good

The cleaning ceremony's real output is a **public good: fear.**

Fear's value is that it makes residents **self-censor** — without the administration watching anyone individually, everyone autonomously abandons exploration because they believe "going out is death." This saves the administration enormous surveillance costs.

But a public good carries its public-good price: **it must be continuously produced.** Fear does not sustain itself — each new generation re-questions "what is really outside," so the administration must stage the ceremony again and again, refreshing fear with each death. This is a **consumptive, unsustainable equilibrium**:

- Each ceremony drains the administration's credibility (truth may leak through some detail);
- Each ceremony also drains the residents' fear threshold (the more death broadcasts, the lower the marginal deterrence);
- While the breaker needs only **one** successful counter-signal — one surviving cleaner — to zero out the entire fear public good.

## 4. Show Verification

The show itself supplies the collapse point of this signaling game. The protagonist Juliette is sent out to clean, but she **does not die.** She reaches the lens, sees what the outside truly looks like, survives, and even walks into the neighboring Silo 17.

This single survival event is that "one successful counter-signal." By the model, it should instantly destroy the belief "outside is death" — and the plot's reaction confirms it: the administration's first move is not explanation, but **injecting her with memory-erasing drugs to wipe the memory.** Because they know a single living cleaner is more destructive than a hundred dead ones.

## 5. Falsifiable Corollary

The core thesis translates into a falsifiable claim:

> **In any closed system that maintains a belief through "death signals," if a single observable "survival counterexample" appears and cannot be immediately erased by the administration, the system's signal mechanism enters irreversible collapse.**

Conversely, if the administration can erase all survival counterexamples **immediately and completely** (memory drugs + record destruction), the signal mechanism can be prolonged — but at an erasure cost that rises over time and eventually exceeds the mechanism's benefit.

## Conclusion

The cleaning ceremony teaches one thing: **manufacturing fear through death is the most fragile form of control.** Because it bets on "there is never an exception" — and game theory tells us the defender cannot afford to bet on "never."

---

*Paper 1 of the "Silo Game Theory" series. Uses a fictional show as a case study to discuss the information-control structure of closed systems in general.*
