# \citet{parrell:2019_facts} — FACTS: task control and state estimation

**Original publication:** Parrell, Ramanarayanan, Nagarajan & Houde (2019), *PLOS Computational Biology* 15(9), e1007321. DOI: https://libkey.io/libraries/3907/10.1371/journal.pcbi.1007321. Research ref: papers:parrell:2019_facts.

## What the model implements

FACTS combines Task Dynamics with a nonlinear articulatory state estimator (unscented Kalman filter). The desired tasks are constrictions in the vocal tract, specified by location and degree. A task-level controller converts a desired constriction into a command given the *estimated current* task state; a lower controller translates task-level control into articulator movement. A forward model predicts articulatory state and auditory/somatosensory feedback; discrepancies update the estimate (original paper, Introduction and Model overview, pp. 2–7).

The paper illustrates this with a gestural score for *mod*: overlapping bilabial closure, velum opening and vowel constriction followed by tongue-tip closure (Fig. 3). Such a score specifies gestures and their activation times. It is **provided by a linguistic planning module**. FACTS models the execution and adjustment of the schedule, not how an intention to say *mod* generates it. That is the crucial scope restriction for the philosophical inquiry.

The simulations reproduce qualitatively several properties of feedback control, including resistance to auditory masking and responses to altered auditory or somatosensory signals (abstract; Results beginning p. 7). The architecture explains how distinct articulator configurations can accomplish the same task-level constriction, without treating the constriction as a bare sequence of muscle commands.

## Limits and relevance

This is a computational demonstration, not a direct measurement of the neural encoding of the input gestural score. Its target space is constriction-based; the authors expressly leave a controller with auditory goals for later work (Model overview, p. 5). The model cannot independently establish that propositional intentions non-accidentally match motor representations: the linguistically relevant input is stipulated upstream.

## Access and checks

Research / Personal Papers original fulltext retrieved on 11 October 2026. Read abstract, Introduction, Model overview and early Results, approximately pp. 1–9, including the specified gestural-score input and Fig. 3 caption. Remaining simulation results and supplementary methods were **not** audited in full; no claim of exhaustive validation is made.

[Speech interface entry](../../entries/speech-actions-interface-problem.md) · [Perturbation entry](../../entries/auditory-feedback-perturbation-in-speech.md) · [Checklist](checklist.md)
