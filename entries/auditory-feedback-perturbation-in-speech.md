# What auditory-feedback perturbations reveal about speech control

## The basic experimental logic

A participant speaks into a microphone and hears their voice through headphones. The experimenter alters a property of the returning sound—often vowel formants (F1 or F2), fundamental frequency (pitch), or timing—without changing the participant's actual vocal tract movement. The difference between what was produced and what was heard is controlled experimentally. The central distinction is between **online compensation** during an altered utterance and **adaptation** persisting in later productions, including unaltered-feedback trials. Compensation can occur without lasting learning; aftereffects provide a more direct indication of recalibration.

A shift of F1 toward a different vowel may prompt a speaker to change their produced F1 in the opposite direction. The response is often incomplete and varies across speakers, contexts and perturbation sizes. Delayed auditory responses make a controller relying only on incoming sound implausible: internal prediction, feedforward commands and somatosensory feedback must also matter. The computational model in \citet{parrell:2019_facts} reviews approximately 150-ms auditory responses versus much faster mechanical responses (Introduction), and simulates the combination of prediction and sensory state estimation. These are qualitative model fits, not proof that a particular neural controller is uniquely correct.

## What we know, and what remains disputed

**Phonetic category matters to error correction.** \citet{niziolek:2013_vowel} selected each speaker's vowel perturbation using a pretest of their own category boundaries, comparing matched-size shifts near versus far from those boundaries. Near-boundary trials produced over threefold larger compensatory responses and stronger activity especially in right posterior superior temporal gyrus (abstract, Methods). The finding is about category-sensitive feedback processing; it does not imply that perception is exclusively categorical or that the speaker's intention encodes a vowel boundary. The near/far classification also exploited naturally variable utterances, and the imaging sample was 18 selected speakers, important limits for generalisation.

**Lexical context can affect adaptation.** \citet{bourguignon:2014_lexicalperceptual} compared shifts that changed real-word/pseudoword status with shifts that preserved it. Their result supports sensitivity to lexical-perceptual context, not a general law that all lexical information governs motor learning. It is one study, in *Frontiers in Human Neuroscience*, requiring independent replication and scrutiny of group and stimulus effects.

**Adaptation can change later perceptual judgements.** \citet{lametti:2014_plasticity} manipulated F1 while speakers repeatedly produced *head*, then tested category judgements on *head–had* or *head–hid* continua. The perceptual changes tracked the direction of the *compensatory vocal output* more closely than the altered sound participants heard. A listening control helps discriminate motor-learning-related from passive-exposure accounts. Nevertheless, the dependent variable was phonetic categorisation, not experienced event boundaries or newly acquired action concepts.

**A prepared but cancelled utterance can support learning.** In \citet{parrell:2026_audiomotor}, a visual cue cancelled a planned word after preparation had begun; at the expected speaking time participants heard a shifted recording from a preceding trial. The next utterance shifted opposite the perturbation even on successfully inhibited trials, though less than after actual speech. Passive listening did not show the same effect. The authors report cancellation failures on about 22% of attempted no-movement trials and exclude them; the analysed effect was small. This favours learning from prediction error associated with motor preparation over accounts requiring an overt corrective movement, without isolating propositional intention from a prepared speech plan.

**Models identify the control-level question.** \citet{parrell:2019_facts} starts with a *gestural score*: constriction locations, degrees and onset/offset times supplied by a linguistic planning module. It estimates articulator state from forward predictions and auditory/somatosensory feedback, then drives task-level constrictions and articulator commands. It explains how a specified task may be realised and corrected, while assuming that a suitable score has already been provided. DIVA/GODIVA models are a second influential family, surveyed by \citet{meier:2023_neurocomputational}; their detailed assumptions still require full-text checking here.

## Further high-quality evidence: generalisation, timing and individual differences

The earlier vowel-formant examples are only part of the field. Recent original research provides useful tests of the scope of auditory-feedback learning.

**Generalisation is possible, but design-dependent.** A 2024 study, *Sensorimotor adaptation to a nonuniform formant perturbation generalizes to untrained vowels*, applied feedback perturbations to four English corner vowels and assessed five other vowels not used during exposure. The authors reported adaptation and transfer to untrained vowels. This demonstrates that a trained acoustic item is not necessarily the limit of speech motor learning. It does not establish that a propositional intention controls the transferred representation. [Original open-access article](https://pmc.ncbi.nlm.nih.gov/articles/PMC11573274/).

**Timing perturbations are a separate test.** Karlin and colleagues (2021), *Auditory Feedback Is Used for Adaptation and Compensation in Speech Timing*, used real-time temporal perturbations with baseline, ramp, hold and washout phases. The experiment addresses speech timing rather than treating the vowel formant as a proxy for all speech. The authors report 20 participants, with one stimulus condition excluded because of perturbation-implementation issues. This is a reminder to audit engineering failures and exclusions as well as reported adaptation. [Original article](https://pmc.ncbi.nlm.nih.gov/articles/PMC8642089/).

**Speakers differ in how much they rely on sensory channels.** *Sensory Preference in Speech Production Revealed by Simultaneous Alteration of Auditory and Somatosensory Feedback* (2012) found an inverse relation between compensation to the two perturbation types. This challenges any simple inference from the absence of an auditory response to the absence of a motor target: a speaker may weight somatosensory information more heavily. [Original article](https://www.jneurosci.org/content/32/27/9351).

**Prediction error has direct physiological tests.** *Neurophysiological Evidence of Sensory Prediction Errors Driving Speech Sensorimotor Adaptation* (2025) measured speaking-induced auditory suppression while speakers adapted to perturbed formants. Its interpretation favours updating sensory predictions, while noting that compensation remained partial (mean about 13.6% of the perturbation). The physiological interpretation and model fit should not be treated as unique proof of one computational architecture. [Original article](https://www.jneurosci.org/content/45/27/e2084242025).

The main conceptual point is that *online compensation*, *aftereffects*, *generalisation*, *sensory weighting* and *prediction updating* are distinct observables. A model of one does not automatically explain the others, and none alone demonstrates the intention–motor match.

## Sources not in my library

The four studies in the preceding section were identified and checked at the original journal or open-access article pages using Exa and Parallel Search. Exact citation keys were **not** found in Personal Papers metadata; the descriptive titles and linked originals are retained rather than inventing keys. Detailed full-text methods and supplementary data still require audit. See the [source checklist](../sources/auditory-feedback-perturbation-in-speech/checklist.md).

## How to interpret an experiment quickly

| Contrast | What it helps establish | What it does not establish |
|---|---|---|
| Sudden unpredictable shift within an utterance | Online error response, latency and gain | Durable learning or intentional goal selection |
| Sustained shift plus unshifted probe or washout | Adaptation and aftereffects | Which representational level set the original target |
| Equal-size shifts near/far from a phonetic boundary | Category sensitivity of correction | Category-only perceptual coding |
| Real word/pseudoword manipulation | Lexical contextual influence | Direct influence of propositional intention |
| Cancelled preparation versus passive listening | Contribution of prepared predictions to learning | Intention–motor matching in the philosophical sense |
| Perturbation plus perceptual pre/post test | Coupling of sensorimotor learning and classification | Action-concept acquisition or event-based phenomenology |

For future comparisons record perturbation dimension and magnitude, within-trial timing, adaptation exposure, control stimuli, masking, response latency, aftereffect, individual differences and whether effects generalise to untrained utterances. Pitch, formant and timing perturbations need not share a mechanism. The field is experimentally rich, but the above is a **selective, not exhaustive, state-of-the-art map**: systematic comparison of replications, pitch studies, developmental samples and the newest reviews remains outstanding.

## Why this might matter for the Interface Problem

The Interface Problem asks how an intention and a motor representation non-accidentally specify matching outcomes, not merely how a motor controller repairs an error. Perturbations reveal which target-related constraints survive changes to sensory evidence, and whether category and lexical organisation affect sensorimotor updates. It is **plausible but presently unestablished** that such experiments can discriminate mechanisms that make intention–motor matches non-accidental. The first task is to connect an experimentally operationalised target to a genuinely propositional intention rather than assuming they are the same representation.

[Interface inquiry](speech-actions-interface-problem.md) · [Source checklist](../sources/auditory-feedback-perturbation-in-speech/checklist.md)
