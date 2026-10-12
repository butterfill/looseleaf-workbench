# How do listeners recover articulatory gestures from speech?

## The question

Listening makes the organised actions of speaking intelligible from their consequences. A listener can recognise /b/ in voices with very different vocal tracts, speaking rates and coarticulatory contexts. Yet the acoustic signal does not present a separate, context-free fragment corresponding to each lip closure or tongue constriction. What can listeners recover about the articulatory events that gave rise to the sound, and by what means? In particular, can they recover something about **what the speaker was trying to articulate** when the speaker's intended action and its execution differ?

The problem has several possible answers. Listeners reliably recover *phonetic distinctions* and can exploit visual, acoustic and occasionally tactile information related to articulatory events. They might also estimate the speaker's vocal-tract configuration, an articulatory *task* or, more ambitiously, an intended gesture. Those achievements must be distinguished, including from the further claim that a gesture is an **object of perception**. The strongest classical motor theory made an attractive, simple proposal about the intended gestures underlying speech. Its obligatory, specialised motor-reconstruction picture is no longer a persuasive default. It remains worth asking which parts of the gestural hypothesis are independently supported.

A [parallel investigation](motor-processes-in-speech-perception.md) asks what roles the *listener's motor processes* play in speech perception. The present question is about **information recovered about the speaker's actions**. Success in recovering such information need not require motor simulation, while motor contributions to phonetic judgments need not involve recovering gestures.

## Four different targets of recovery

Consider hearing a speaker produce a syllable intended as /ba/. The listener might achieve any of the following:

| Possible achievement | Example | Why it is a separate question |
|---|---|---|
| Recover a **phonetic category** | Identify the onset as /b/ rather than /d/ | Category identity need not specify the bodily event or production plan. |
| Recover an **articulatory task** | Estimate that a labial constriction was involved | The same constriction can be achieved by different jaw and lip movements. |
| Recover a **realised articulatory event** | Estimate when and how the lips actually closed | What occurred might deviate from the intended target. |
| Recover an **intended gesture or motor organisation** | Identify the labial action that the speaker planned, even if it was not completed | Intention is not simply another observable motion; acoustic evidence may fail to determine it. |

These are different descriptions of possible informational achievements, not stages that a listener must traverse. A familiar phoneme can be identified without consciously considering the vocal tract. An estimate of lip closure may be correct even if the listener cannot identify the linguistic category. In an error, the intended phonetic target and the realised event can come apart.

The term *gesture* itself requires care. In Articulatory Phonology, \citet{Browman:1992da} analyse gestures as dynamically specified vocal-tract tasks—such as achieving a constriction—organised into temporally overlapping constellations. Such tasks are stable across some variability in the particular muscle movements used. The public-action account developed by \citet{Goldstein:2003bn} treats articulatory action as a potential common currency for production and perception. Neither proposal by itself establishes how much articulatory detail a listener extracts.

The revised motor theory of \citet{Liberman:1985bn} instead emphasises recovery of the speaker's *intended phonic gestures*, understood as structures more remote than peripheral movements, by a specialised phonetic system. The contrast between intended structures and public articulatory events is substantial: a listener could recover one without accurately recovering the other. \citet{Galantucci:2006mo} also distinguish the historical hypotheses that speech perception is special, that perceiving speech involves perceiving gestures, and that motor processes contribute to listening. They should remain separate.

## Recovering causes from their acoustic consequences

Speech production runs from action organisation through bodily motion to a complex acoustic result. Listening presents the inverse problem. Different vocal tracts and movements can realise comparable constriction tasks; overlapping gestures influence one another's acoustic consequences; and a single acoustic property may be informative about different gestures in different contexts. Noise introduces further uncertainty.

Consequently, recovering a gesture does not require discovering an individually invariant acoustic segment for it. A listener could instead combine multiple probabilistic cues, speaker and rate information, lexical expectations, and prior experience with how speech is produced. The *ideal adapter* framework of \citet{kleinschmidt:2015_robust} supplies an important alternative account of robust phonetic recognition through learned distributions and adaptation. Such accounts need careful evaluation; invoking probabilistic inference alone does not prove that the resulting estimate is entirely auditory in format, or exclude gestural estimates among its latent variables.

There are two explanatory transitions here. First, **which information supports the estimate?** A perception might be sensitive to a gestural cause without explicitly representing the cause. Second, **what is estimated?** A model may recover a phonetic label, a likely articulatory target, or a distribution over possible bodily movements. Demonstrating successful recognition of /b/ is insufficient to distinguish these alternatives, because in ordinary speech the acoustic, phonetic and gestural variables are strongly correlated.

A more revealing comparison requires circumstances in which those variables make *different predictions*: ambiguous or perturbed production, variable ways of achieving a constriction, conflicting audiovisual cues, or situations in which the same phonetic label can result from different articulatory trajectories. Such comparisons should test a well-specified acoustic-only model alongside a gestural account rather than presuppose that acoustics are too variable to carry the necessary information.

## What multisensory evidence shows

One reason to consider vocal-tract actions as perceptually relevant is the integration of information from different senses. As \citet{fowler:1996_listeners} argues, auditory signals can specify the distal actions that cause them; the fact that ears transduce vibrations does not decide which events a listener perceives. Visual speech effects are compatible with this proposal. They also admit learned cross-modal association and probabilistic cue-integration explanations. Their existence alone therefore does not determine perceptual objects.

Two interventions widen the evidence beyond visual speech. \citet{ito:2009_somatosensory} applied temporally patterned facial-skin stretch while participants categorised sounds along a *head–had* continuum. Dynamic, speech-like somatosensory perturbations shifted identification, with temporal and directional specificity. The manipulation concerns the **listener's** somatosensory state, and shows that information associated with speech movements can affect an auditory categorisation. It does not measure recovery of the **speaker's** actual or intended gesture.

\citet{gick:2009_aerotactile} found that artificial air puffs to a listener's skin could change closed-choice identification of aspirated versus unaspirated syllables. An externally delivered tactile cue, with no direct source in the speaker's mouth, can influence the heard phoneme. This is consistent with listeners using knowledge of articulatory consequences; it is also consistent with cue integration at an auditory/phonetic or decision level.

The full-text follow-up by \citet{derrick:2019_aerotactile} makes the qualification especially important. Airflow congruence changed the speech-in-noise threshold in a *closed-choice* syllable task, but produced no detectable comparable benefit in an *open-choice* syllable-identification task. The reported cross-experiment interaction is modest, and the experiments also differed in participants, recorded tokens and other details. These findings support **response-format sensitivity**, rather than an unconditional law that tactile articulatory information improves speech perception. They also discourage inferring a stable percept of the speaker's gesture from a constrained report.

Taken together, these experiments establish that listeners can exploit bodily or event-related information while processing speech. Whether that information makes a gesture itself perceptually present, and which gesture is recovered, requires further evidence.

## Articulatory information in neural responses

Neural pattern analyses make it possible to ask whether responses during listening are structured by properties associated with articulation. \citet{correia:2015_decoding} found that fMRI classifiers could generalise some place- and manner-of-articulation distinctions across differing syllable classes during attentive listening, including in sensorimotor and auditory regions. Such generalisation is more informative than finding that a motor area becomes active. Yet acoustic consequences also correlate with place and manner; successful feature decoding does not by itself isolate a specifically gestural neural code.

The contrast with other experiments is illuminating. Intracranial recordings in \citet{cheung:2016_auditory} showed that the structure of listening-related responses in ventral sensorimotor cortex was more strongly organised by acoustic properties, whereas production-related activity had articulatory organisation. \citet{arsenault:2016_no} failed to find the expected lip-versus-tongue somatotopy during passive listening, despite identifying those movement patterns with an articulatory localiser. These results challenge an obligatory, straightforward reuse of production codes; they do not rule out context-dependent articulatory information, particularly under specific tasks and difficult listening.

One especially interesting but provisional extension is the **unpublished bioRxiv preprint** \citet{tseng:2026_decoding}. This **unpublished, not-peer-reviewed study** reports transfer from a production-based lip/tongue classifier to perception of native consonants **in noise** in right precentral cortex. The positive cross-modal result is restricted in its conditions and remains to be independently established. Even if confirmed, shared pattern structure would establish something about available neural information before establishing that the listener experiences the speaker's intended action.

The [motor-processes investigation](motor-processes-in-speech-perception.md) examines these methods and apparent disagreements in detail. For the present question, neural decoding of a feature should be distinguished from successful behavioural recovery of a particular gesture and from the perceptual presentation of an action.

## The limited bearing of categorical perception

The original case for gestural perception made considerable use of phonetic constancy and categorical perception. A reconstruction in \citet{Butterfill:2009vs} takes gestural recovery to explain why listeners identify stable phonetic contrasts across diverse acoustic contexts. The explanation remains intelligible; its evidence is insufficient to select it over all auditory and probabilistic alternatives.

The strongest classical categorical-perception inference is particularly insecure. \citet{mcmurray:2022_myth} examines how identification and discrimination tasks influence apparent categories and marshals evidence for preserved within-category information. Earlier nonhuman experiments are revealing for a different reason: \citet{kuhl:1975_speech} found speech-like voicing boundaries in trained chinchillas, while \citet{kuhl:1981_discrimination} found increased sensitivity near such a boundary. The latter article expressly distinguishes a *phoneme-boundary effect* from strong categorical perception. These results do not show what chinchillas perceive as distal objects; they do show that a phonetic boundary cannot alone establish a uniquely human mechanism for recovering intended gestures.

Neural findings reinforce the separation of categorisation from an exclusively categorical perceptual code. \citet{toscano:2010_continuous} found early graded voice-onset-time responses and later category-sensitive responses. \citet{baek:2026_dynamic} reports temporally overlapping acoustic and behaviourally defined category-related MEG patterns rather than a simple serial replacement of one by the other. And \citet{daube:2019_simple} shows that apparent phoneme-feature encoding in continuous-speech MEG/EEG can sometimes be predicted by well-chosen low-level acoustic features. The explanatory burden lies in finding evidence of articulatory recovery **beyond** what such models predict.

These are reasons to retire the old categorical-perception argument as a major premise. They leave the question of articulatory and action-event recovery open.

## When would recovery count as *perceiving* a gesture?

Three claims merit separate tests:

**Sensitivity to a cause.** Acoustic or visual processing is changed by the articulatory events that caused the stimulus. This is expected under many auditory accounts.

**Representation of a cause.** The listener's perceptual processing includes a variable describing a labial constriction, a tongue gesture, or a likely production target, and uses it across contexts. This demands more than correlation between the sound and a nominal gesture label.

**Perceiving the cause as an event.** The vocal action itself figures among the perceived events, with some temporal boundaries, persistence and relational structure. This is the stronger direct-realist possibility.

\citet{fowler:1996_listeners} rightly challenges the assumption that using acoustic information entails perceiving *only* acoustic patterns. Distal actions can be perceptual objects without requiring their detailed motor commands to be reconstructed. Conversely, a perceptual system can compute an articulatory estimate while the listener's experience and task performance remain organised principally around heard phonemes or words. Demonstrating either neural representation or successful articulatory inference does not, without an additional account, settle what is perceived.

One plausible route forward is to study whether implicit event segmentation, generalisation across unusual performances, and the perceptual organisation of temporal overlap follow **articulatory event structure** better than acoustic and phoneme-based competitors. The criteria for calling the resulting organisation *perceptual*, rather than an inference attached to perception, will still need philosophical defence. There is a connection here with [motoric action individuation](motoric-action-individuation.md), but the two problems should not be conflated.

## The more demanding question: intended versus realised gestures

The speaker may aim at a constriction and fail to achieve it, compensate for a disturbance using an unfamiliar movement, or produce an articulatory slip. In such cases an intended task, the movements performed, the acoustic consequences and the listener's conventional phonetic classification could diverge. These are the promising cases for testing claims about *intended* gestures.

But even here care is required. An experimenter's instruction to say /ba/ establishes the instructed phonetic target; it does **not** directly measure the speaker's motor command. An acoustic error that listeners silently correct using lexical context might show sensible inference about the likely word, while telling us little about reconstruction of a specific intended articulatory plan.

A discriminating research design would combine independent records of the speaker's production target, vocal-tract kinematics and resulting acoustics, and examine listeners' responses when the variables disagree. Useful comparisons include perceptual tasks that avoid explicit phoneme labels; listeners with different articulatory expertise; controls for lexical expectations and acoustic covariates; and, where justified, selective perturbation of the listener's motor system. Reports about what the speaker *probably tried to say* should be analysed separately from tests of the structure of auditory experience. Cases permitting genuinely similar acoustics from distinct articulatory realisations would be particularly informative, where they can be generated and validated.

If listeners track the intended target across discrepancies in realised motion, one interpretation would be recovery of a goal. A rival interpretation would be lexical or phonological error correction. To distinguish these, the experiment must make the goal estimate more specific than the most likely word or phoneme. The philosophical question is therefore demanding, but it is a better guide to further work than asking whether gestures are globally the 'basic units' of perception.

## Assessment

There is strong evidence for robust phonetic recognition and for flexible integration of information related to articulation. Some neural experiments reveal feature structure compatible with articulatory representations; others reveal acoustic organisation or fail to find passive somatotopy. These findings make *degrees and kinds of gestural recovery* empirically tractable. They leave open whether listeners routinely recover particular performed gestures and provide little direct evidence for recovery of intended motor commands.

The productive questions are **which articulatory facts are recoverable**, **which information and computations make recovery possible**, and **when that recovery contributes to hearing a speech event as an action**. The [parallel motor entry](motor-processes-in-speech-perception.md) investigates whether and when the listener's production-related mechanisms help, without presuming that either inquiry answers the other.

For the broader possibility that experience of speech actions contributes to the concepts through which intentions reach motor control, see [speech actions and the intention–motor interface](speech-actions-interface-problem.md). That is a further philosophical question, rather than an automatic consequence of gesture recovery.

## Sources and extent of checking

The [source checklist](../sources/phonetic-gestures-and-speech-perception/checklist.md) and [source-specific notes](../sources/phonetic-gestures-and-speech-perception/) give locators and outstanding checks. 'Full text' below means the original was available and relevant passages were **selectively checked**, not that every page, dataset or cited study was reanalysed.

| Source | What was available and checked |
|---|---|
| \citet{Butterfill:2009vs} | User-supplied original manuscript; §III's historical argument reconstructed. |
| \citet{Browman:1992da} | Research original full text; gesture dynamics and overlap, §§1–1.2. [Note](../sources/phonetic-gestures-and-speech-perception/Browman1992da.md). |
| \citet{Goldstein:2003bn} | Research original chapter; public-action theory and production–perception framing, selectively read. |
| \citet{Liberman:1985bn} | Research original full text; revised theory, intended gestures and module claim. [Note](../sources/phonetic-gestures-and-speech-perception/Liberman1985bn.md). |
| \citet{Galantucci:2006mo} | Research original review; historical claims and conclusions, selectively read. |
| \citet{kleinschmidt:2015_robust} | Research original full text in part; ideal-adapter proposal, probabilistic mappings and adaptation; remaining sections unchecked. |
| \citet{fowler:1996_listeners} | Research original full article; §§I, III–IV and direct-realist objections. [Note](../sources/phonetic-gestures-and-speech-perception/fowler1996_listeners.md). |
| \citet{ito:2009_somatosensory} | Research original full text; skin-stretch manipulation, controls, results. [Note](../sources/phonetic-gestures-and-speech-perception/ito2009_somatosensory.md). |
| \citet{gick:2009_aerotactile} | Research original full Nature article; puff task and comparisons. [Note](../sources/phonetic-gestures-and-speech-perception/gick2009_aerotactile.md). |
| \citet{derrick:2019_aerotactile} | Research full published JASA article; both experiments, Tables I–V, discussion. [Note](../sources/phonetic-gestures-and-speech-perception/derrick2019_aerotactile.md). |
| \citet{correia:2015_decoding} | Research original full text; cross-generalisation MVPA and interpretation. [Note](../sources/motor-processes-in-speech-perception/correia2015_decoding.md). |
| \citet{cheung:2016_auditory} | Research original full text; intracranial listening/production comparisons. [Note](../sources/motor-processes-in-speech-perception/cheung2016_auditory.md). |
| \citet{arsenault:2016_no} | Original published Springer HTML; production localiser, passive-listening nulls and Bayesian tests. [Note](../sources/motor-processes-in-speech-perception/arsenault2016_no.md). |
| **\citet{tseng:2026_decoding} — unpublished bioRxiv preprint** | Original **unpublished, not-peer-reviewed** preprint full text in Research; cross-modal results, methods and exclusions. [Note](../sources/motor-processes-in-speech-perception/tseng2026_decoding.md). |
| \citet{mcmurray:2022_myth} | Research original full review; operational criticism of categorical perception. [Note](../sources/phonetic-gestures-and-speech-perception/mcmurray2022_myth.md). |
| \citet{kuhl:1975_speech} | Research original Science full text; trained chinchilla identification experiments. [Note](../sources/phonetic-gestures-and-speech-perception/kuhl1975_speech.md). |
| \citet{kuhl:1981_discrimination} | Research original JASA full text; adaptive VOT thresholds and distinction between CP and boundary effects. [Note](../sources/phonetic-gestures-and-speech-perception/kuhl1981_discrimination.md). |
| \citet{toscano:2010_continuous} | Research original full experiment; N1, P3 and VOT analyses. [Note](../sources/phonetic-gestures-and-speech-perception/toscano2010_continuous.md). |
| \citet{baek:2026_dynamic} | Original published Nature Communications HTML; behavioural categorisation and MEG/RSA comparisons. [Note](../sources/phonetic-gestures-and-speech-perception/baek2026_dynamic.md). |
| \citet{daube:2019_simple} | Research manuscript full text and published article checks; acoustic-feature model comparisons. [Note](../sources/phonetic-gestures-and-speech-perception/daube2019_simple.md). |

**Status:** Active workbench inquiry. No promotion or exhaustive original-study replication audit is claimed.
