# Paper 3: Memory Erasure and Markovian State Control

**Core game**: administration resets individual state via drugs vs. the individual's memory recovery
**Tools**: Markov decision process, state erasure, dynamic programming
**Show anchor**: Juliette's amnesia, drug injection, fragmented memory recovery
**Core thesis**: memory reset cannot change structural constraints; structural knowledge survives in physical carriers
**Falsifiable corollary**: as long as external records exist, the erasure strategy fails in the long run

---

## Abstract

More extreme than destroying history is **erasing a person's memory.** In *Silo*, the administration injects amnesia drugs into anyone who has seen the truth, attempting to wipe the state of "knowing" from the individual entirely. This paper models the strategy as a Markov decision process and argues for its fundamental failure: **memory can be reset, but structural constraints cannot be reset.** That a person has "forgotten" something does not mean the system's knowledge of it has disappeared — it exists in physical carriers, independent of any individual's memory. The erasure strategy only works under the limiting assumption of "no external records exist," and that assumption almost never holds in reality.

## 1. The Scene: The Injected Truth

Juliette walks out of the silo, sees the truth of the outside, and survives into Silo 17 — the collapse point of the entire signal system. And Silo 18's administration responds not with explanation, not with negotiation, but by **injecting her with amnesia drugs** to make her forget everything she saw.

The underlying logic: **if you cannot stop the truth from being seen, stop the person who saw it from remembering it.**

## 2. The Model: State Erasure

Model individual memory as a state variable $s \in S$, where $s$ contains the individual's cognition of the system's structure. The administration applies an "erasure operation" $e$, resetting $s$ to the ignorant state $s_0$.

**Markov decision process**: the administration's strategy is to apply $e$ whenever it detects $s \neq s_0$ (the individual "knows"). In the short run this works — the individual's cognitive state does return to ignorance.

But the model's blind spot is this: **it assumes knowledge exists only in the individual's state $s$.**

In reality, knowledge simultaneously exists in:

- **Physical carriers $D$**: notes, blueprints, databases, AI parameters, words carved into walls;
- **Other individuals $R_{-i}$**: companions, students, anyone who heard the same thing;
- **The structure itself**: the silo's physical layout, the airlock's design, the pipe routes — these "silent" things are themselves encoded knowledge.

## 3. Equilibrium Analysis: Erasure vs. Persistence

Let the administration's erasure cost be $c(e)$ and the total number of knowledge copies be $n$. To maintain ignorance, the administration must satisfy:

$$c(e) \times n < \text{benefit}$$

But $n$ is not fixed — **it grows with every act of recording.** A person writes one line before being erased, and $n$ goes +1; two people tell each other before being separately erased, and $n$ goes +2. The administration's erasure speed can never catch up with the reproduction speed of recording.

**This is the structural reason the amnesia strategy fails in the long run: it fights not memory, but the reproduction of records.**

One layer deeper: structural knowledge (the ability to derive the truth backward from a system's boundaries) is itself a kind of knowledge — it can be transmitted through education, written into methodology, and passed from one generation to the next. Erasing one person's memory cannot erase a method.

## 4. Show Verification

The show confirms this itself. Though Juliette is injected with amnesia drugs, the way she ultimately recovers her memory is by **finding a physical carrier** — the PEZ dispenser George left behind. That dispenser is not in her memory; it exists in the world independently, waiting to be rediscovered.

The administration's amnesia drug can erase "what Juliette remembers," but it cannot erase "what George left behind."

## 5. Falsifiable Corollary

> **In a system where knowledge can be recorded and shared by many, the long-run effect of any "memory reset" strategy tends to zero — as long as at least one physical record independent of individual memory exists, the erased knowledge is necessarily rediscovered within finite time.**

The converse is falsifiable: if the administration could simultaneously erase **all** physical records, **all** sharers, and **all** structural traces, then memory reset could hold. But that condition is equivalent to "erasing the entire system" — it destroys the very object being controlled.

## Conclusion

The amnesia drug is the most desperate control instrument in this series — because what its designer truly wants to erase is not a particular memory, but the fact that **knowledge can be recorded.** And that fact is older and more undefeatable than any administration.

---

*Paper 3 of the "Silo Game Theory" series.*
