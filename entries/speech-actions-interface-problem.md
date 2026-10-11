# Speech actions and the intention–motor interface

## The question

Can research on speaking—and on hearing speech—help explain how thoughts interface with motor representations? The interface problem arises because a single action can be guided both by an intention and by motor representations which specify outcomes in a different format. The outcomes nevertheless sometimes match, and their matching is no accident. What makes that possible? And could the perception and acquisition of speech actions explain how we come to have thoughts capable of guiding them?

Speech is an attractive case because it connects familiar, sometimes quite explicit intentions to remarkably intricate action control. Someone can decide to say *paper*, yet carrying this decision out involves organising lip closures, releases, vocal-tract configurations and their timing. The movements depend on speaking rate, surrounding sounds, what the speaker is trying to emphasise, and many other circumstances. It is unlikely that the intention itself specifies these details. Nevertheless, a fluent speaker normally says the intended word.

There are two quite different reasons to investigate this case. **Speech production** may expose the processes by which relatively abstract action specifications recruit the appropriate motor structures. **Speech perception** may illuminate a more ambitious proposal: that motor representations contribute an event-based structure to experience, and that experience helps make available the action concepts by which intentions can reach motor control. These reasons could come apart. Either would be philosophically interesting.

The companion note, [*Are phonetic gestures the basic units of speech perception?*](phonetic-gestures-and-speech-perception.md), examines the motor theory of speech perception, articulatory phonology, categorical perception and the evidence that listening recruits production-related mechanisms. The issue here is what these discoveries might contribute to **the interface problem**.

## What exactly needs explaining?

The interface problem in \citet{butterfill:2012_intention} concerns **non-accidentally matching outcomes**, not identical contents. In a particular context, two specifications match if realising the outcomes specified by one would normally cause or constitute, at least in part, realising those specified by the other. An intention can specify pulling a lever while motor representations specify reaching, grasping and pulling it. Their outcomes need not be described in the same way, or at the same level of detail, to match.

The same point is easy to see in speech. An intention to pronounce *paper* might be fulfilled by a sequence of gestures whose bodily realisation varies considerably across occasions. A motor representation could specify a lip closure at a particular point in an unfolding utterance without itself specifying *saying the word “paper”*. The motor outcome can be among the normal means by which the intended speech action is accomplished. The question is why a motor plan for a suitable realisation is reliably recruited at all.

Here it matters which intention we are considering. An intention **to tell someone what to do** may leave entirely open which words to use; an intention **to say “paper”** is more determinate. A lexical choice or phonological plan can stand between either intention and the articulators. Such intermediate representations must not simply be baptised “intentions”. Otherwise the apparent explanation of the intention–motor interface may consist in silently changing the subject to a connection between phonological plans and motor control.

{==The issue has at least three parts.==}{##7f241e65-2a50-4463-860f-3db5e72ab7fb##} {==First==}{##2b732613-7f57-4b6d-9dc4-67c7de5ad939##}, how can representations at distinct levels specify *matching* outcomes? Second, among several articulatory realisations that could satisfy a speech goal, how is a suitable one *selected*? Third, how does the speaker acquire the capacity to make those matches and selections reliably? The distinction between matching and selection is particularly clear in \citet{brossel:2026_solving}; the distinction between the diversity of possible realisations and the specificity of an actual one is emphasised by \citet{burnston:2017_interface}. An explanation of feedback correction while speaking need not, by itself, be an explanation of any of these earlier achievements.

{##2b732613-7f57-4b6d-9dc4-67c7de5ad939:
^ update in the light of the ∞ comment.
##}


{##7f241e65-2a50-4463-860f-3db5e72ab7fb:
∞ lets be careful. The Interface Problem is one question, and its formulated in a way that is neutral about causation. There are also other questions that could be asked, and we might want to investigate those too. But if our focus is on the Interface Problem, then, strictly speaking, the issue does not have three parts.

I don't think this matters too much here but I want everyone to be clear about what the Interface Problem is vs what other questions are. (One risk is that opponents take as a premise that all questions must be answered.)
##}


## Why speech provides an unusually sharp test

Speech offers more experimentally tractable intermediate stages than a simple opposition between “intention” and “movement” suggests. **The Interface Problem itself remains the single, causally neutral question of why intention-specified and motor-specified outcomes match non-accidentally.** Questions about how a motor plan is selected, how a skill is acquired and how feedback corrects execution are related research questions, not extra parts that every solution to the Interface Problem must answer. A familiar psycholinguistic description distinguishes conceptual preparation, lexical selection, phonological encoding, phonetic planning and articulation \citep{levelt:2001_spoken}. The boundaries among these stages, and whether they operate serially, are debated. Still, the framework brings an important question into focus: *{==where is a content-sensitive bridge actually constructed, and where has the model simply taken the result of another process as its input?==}{##7630264a-b297-469d-a0f1-4991a4e34d72##}*

{##7630264a-b297-469d-a0f1-4991a4e34d72:
^do I'm not convinced this is a clear enough distinction to rely on. Check then clarify or drop.
##}


A concrete example makes the contribution of motor-control models clearer. To say /b/ requires closing the lips; that closure can be achieved by different combinations of jaw and lip movements. A task-level controller can aim at *lip closure* while a lower controller computes suitable articulator adjustments given the current vocal-tract state. When the jaw is unexpectedly displaced, the lip movements needed to preserve the closure change. This is a genuine explanation of task-relative flexibility, rather than a redescription of muscle commands. Modern motor-control models go considerably further than saying that words produce movements. DIVA/GODIVA models of speech learning and sequencing, surveyed by \citet{meier:2023_neurocomputational}, connect learned speech-sound programmes with sensory targets, motor commands and feedback. The FACTS model \citep{parrell:2019_facts} expresses speech control in terms of vocal-tract tasks, estimates of articulator state, forward prediction and corrective feedback. These are genuine explanatory advances: an articulatory **task**, such as achieving a constriction, can be stable across diverse muscular implementations, and the system can continually adjust an unfolding utterance{==.==}{##155dd834-bc94-40cf-a0dc-9ac32e3debc6##}

{##155dd834-bc94-40cf-a0dc-9ac32e3debc6:
^ this paragraph is too abstract. Explain properly (if, as I think, it matters) or else drop.
##}


The original FACTS paper makes the division of labour particularly explicit: its input is a *gestural score* supplied by a linguistic planning module, specifying the constrictions and their activation times (\citet{parrell:2019_facts}, Model overview, pp. 5–7; [original-text assessment](../sources/auditory-feedback-perturbation-in-speech/parrell2019_facts.md)). The model shows how the score is executed and updated, but does not derive it from an intention. There is, however, an important limit to what these advances establish. Specifying how a controller meets a vocal-tract target does not yet show how an intention to say a certain word comes to specify that target. A phonological representation may already constrain what the controller must do. {==Explaining its conversion into a usable articulatory specification would be progress on *one* interface==}{##48656aeb-940f-4bc4-ab7e-3a402e2733e6##}; it would not automatically solve the interface between propositional intentions and motor representations. The difference deserves an explicit treatment rather than an assumption that the whole chain has been explained. There are plausible *transitions* from communicative goal to lexical choice, lexical choice to phonological sequence, phonological sequence to gestural score, and gestural score to articulator commands. Each may require a distinct mapping because the variables relevant at one stage are not those used at the next. The FACTS model directly addresses the last transition and assumes the gestural score; a theory of lexical access addresses earlier transitions. But none of these transitions should automatically be equated with the philosophical interface between **intention** and **motor representation**.

{##48656aeb-940f-4bc4-ab7e-3a402e2733e6:
^ good: interesting that there are multiple interfaces. Be clearer about where there are likely to be interfaces (and provide preliminary justification for this)
##}


Speech also {==challenges an easy diagnosis of the problem as simply a clash between discrete thought and continuous movement==}{##91411e95-5159-494c-8854-2b57e73cf645##}. Phonological plans may be organised in discrete units, but gestural timing and articulatory parameters are graded, and motor representations themselves may combine symbolic structure with analog values. {==This kind of hybrid motor format is defended as a possibility by \citet{mylopoulos:2025_motoric}. Greater specificity at a later stage does not, by itself, prove a change of representational format.==}{##41aae636-c539-4739-9097-c8d603851164##}

{##41aae636-c539-4739-9097-c8d603851164:
^ this seems too compressed. I can't follow the line of thought.
##}


{##91411e95-5159-494c-8854-2b57e73cf645:
^ seems like a strawman. Has anyone defended such a view? Is it likely that your reader (Butterfill) or his audience would be tempted by this view?
##}


The lesson about representational format should be modest: greater articulatory precision at a later stage does not show that one representation has been translated from a wholly discrete code into a wholly continuous one. A gestural score can contain discrete task identities *and* graded constriction targets and timing parameters. The hybrid symbolic–analog proposal in \citet{mylopoulos:2025_motoric} (especially §§3–6) makes such combinations intelligible. This does not itself explain the match; it warns against inferring the architecture solely from the fineness of movement control.

The advantage of speech is that these distinctions can be investigated in a single activity. We can measure speech output acoustically, examine articulatory movement, disrupt auditory feedback, manipulate whether a sound is a word or nonword, and study how new articulatory patterns are learned. The unusual amount of observable structure makes it possible to ask which constraints are contributed at each stage—and therefore to identify more precisely what the interface problem requires us to explain.

## What feedback experiments might tell us

For a stand-alone, experiment-oriented overview, see [*Auditory-feedback perturbation in speech*](auditory-feedback-perturbation-in-speech.md). The results are likely to be informative about the constraints on speech control, but **exactly how they help explain non-accidental intention–motor matching is not yet established**. We should not infer a solution to the Interface Problem from the existence of compensation or adaptation.

{==Auditory-feedback perturbation studies are especially relevant.==}{##1bd5a339-8e3a-4f14-9f61-a090cb43f288##} A speaker prepares to produce a particular vowel; the acoustic feedback is unexpectedly shifted; the speaker changes production. This demonstrates control relative to a target without independently identifying the propositional intention that might have helped select it. Which aspects of the intended outcome are being maintained, and which adjustments are left to motor control?

{##1bd5a339-8e3a-4f14-9f61-a090cb43f288:
^do Agreed. Please create an independent looseleaf note covering the state of the art in auditory-feedback peturbation studies and link from here. That note should enable me to quickly see what we know about auditory-feedback peturbation.
##}


\citet{niziolek:2013_vowel} found larger compensatory responses to altered vowel feedback when an alteration approached or crossed a phonetic-category boundary than when the comparable alteration remained well within a category. \citet{bourguignon:2014_lexicalperceptual} reported that lexical status can affect speech sensorimotor adaptation. Such results make it difficult to imagine speech motor control as entirely insulated from phonological or lexical organisation. What counts as an error for a speaker is influenced by something more structured than an immediate sound-pressure target.

{==But these effects are not yet demonstrations that a *propositional intention* instructs a motor controller. ==}{##b32d65d3-2f4e-4bd1-b393-0def7547e98d##}A phonetic category or lexical representation could influence an error signal without being an intention; a motor system might learn the relevant correlations directly. To use the experiments philosophically, one must locate the intention, identify the contents of the intermediate representations, and determine which process accounts for their non-accidental correspondence.

{##b32d65d3-2f4e-4bd1-b393-0def7547e98d:
^ yes, of course. But why think that in the first place? Seems like misdirection?
##}


An intriguing experiment sharpens the distinction further. \citet{parrell:2026_audiomotor} report speech adaptation in a condition where participants **prepared but did not overtly execute** the expected movement and nevertheless received appropriately timed altered auditory feedback; a passive-listening comparison did not show the same adaptation. The result suggests that preparing a speech action can establish an auditory prediction capable of supporting motor learning even without an executed utterance.

This is a potentially useful dissociation among **intending**, **preparing**, **executing** and **hearing** an action. Yet the evidence directly concerns a prepared sensorimotor plan and its prediction errors. It does not establish whether the plan's relevant content was fixed by a propositional intention, by the experimental instruction, by a learned phonological–motor link or by some combination of these. A follow-up would need to distinguish those possibilities.

{==Taken together, these studies show why speech is more than a handy illustration.==}{##b7e233c8-26ce-46f6-a1e2-008f4b13eccd##} They allow linguistic constraints, motor predictions, movement and sensory consequences to be manipulated separately. They also reveal how far one may travel through the production system without yet reaching the philosophical interface that motivated the inquiry.

{##b7e233c8-26ce-46f6-a1e2-008f4b13eccd:
^ I'm keen to learn more about auditory peturbation and I do think they are relevant, but this section does not explain how they are relevant. In this situation, it's best not to write as if that had been explained: just write something along the lines of 'these are likely to be interesting but it's not yet clear how exactly they are relevant'
##}


## Could speech perception supply the missing connection?

A different line of investigation concerns **the role of experience in acquiring action concepts**. In \citet{butterfill:2012_intention}, one possible solution involves *reference by deference*: an action concept can refer to a way of acting partly by deferring to a motor representation. The paper illustrates how a thought such as “Do that!” might refer to an action without requiring the thinker to translate a motor representation into a fully articulated propositional description. On this proposal, experiences of acting or imagining action can help make such concepts available; the concept need not invoke fresh motor imagery every time it is used.

The [*Motor in Thought* chapter outlines](https://github.com/butterfill/motor-in-thought/blob/master/proposal/Chapter_outlines_revised.tex) develop a more general possibility. Motor representations may give experience an **event-based structure**. The resulting experiences could help us think about actions in ways that support associations, translations or other connections with motor control. Rather than choosing between deference and translation in the abstract, the hypothesis seeks to explain how an agent comes to have thoughts shaped suitably for either kind of connection.

Speech gives this conjecture a distinctive form. Hearing an utterance involves more than detecting an undifferentiated stream of changing acoustic energy. The listener can experience syllables, consonantal episodes and temporally organised speech events despite wide variation across speakers, contexts and rates. In an [earlier *Motor in Thought* outline](https://github.com/butterfill/motor-in-thought/blob/master/chapter-outlines-for-proposal/content.tex), phonetic actions were *already* used as a particularly clear illustration of this proposed event-based organisation: different acoustic and visible effects could be experienced as belonging to a single type of phonetic action.

The important hypothesis, for present purposes, is about a **route from motor representation through experience to thought**. It does not require the entire classical motor theory of speech perception to be true. Motor representations might contribute to segmenting or organising experienced speech events without being necessary for every instance of speech perception, and without the listener literally perceiving the speaker's private motor commands. Conversely, success at discriminating phonemes is not evidence on its own that the perceiver experiences gestures *as actions*. The competing perceptual claims are examined in the [companion note](phonetic-gestures-and-speech-perception.md).

{==A particularly revealing possibility is that learning to articulate a new contrast changes how an agent experiences speech events, and that this change subsequently supports a new kind of **intentional control**.==}{##ad557ce0-cc26-4fa0-811a-b7784ba7c788##} If so, the value of speech research would reach beyond perception: it would offer a way of investigating how motor-shaped experience contributes to the concepts needed for action.

{##ad557ce0-cc26-4fa0-811a-b7784ba7c788:
∞ nice idea!
##}


There are real complications. {==The older outline itself draws attention to a developmental gap between early speech-sound discrimination and the much later explicit capacity to think about phonetic gestures.==}{##5f266ce6-ed10-41dd-9da1-9ad0e5cdce9b##} This warns against treating perception as sufficient for concept possession. It may also not be necessary: some knowledge of what an unfamiliar speech action is can surely be gained through description and observation. The interesting question may concern **which forms of action thought become possible through acquiring the skill**, especially the capacity deliberately to make fine adjustments that previously escaped intentional control.

{##5f266ce6-ed10-41dd-9da1-9ad0e5cdce9b:
∞ if relevant, go back to that research and find if there's anything more recent that changes the picture too
##}


## Learning to speak and learning to intend

A further line of inquiry concerns acquisition of a speech action rather than an experienced speaker's performance. See the independent note on [second-language pronunciation training](second-language-pronunciation-training.md) for the distinction between perceptual practice, articulatory instruction and deliberate control, and for the substantial outstanding literature review. Consider adults learning to produce a phonetic contrast absent from their native language. Improvements in distinguishing the sounds, imitating them, producing them accurately on request and deliberately modifying their articulatory realisation are not the same achievement. Which of these changes together, and which comes first?

{==A useful design would compare **articulatory training** with training based principally on **perceptual exposure**, matching success in recognising the contrast as far as possible.==}{##dc3318f8-5285-4221-9232-6c1dbdcb6523##} After training, ask whether learners can *intentionally select and maintain* the new articulatory distinction under changing speaking rates, phonetic contexts and forms of feedback, including conditions in which an acoustically acceptable utterance could be achieved by different bodily means. Test whether any newly acquired control transfers beyond repeating the training examples.

{##dc3318f8-5285-4221-9232-6c1dbdcb6523:
^todo please search literature on how people learning a second language are taught. While I doubt that would directly confirm or refute the prediction, it will likely provide some hints that motivate proposing a conjecture related to the prediction. Dont' add that to this note: instead please create a new looseleaf note on this topic and link from it here.
##}


To probe the experience-mediated hypothesis specifically, the study would also need a measure of how participants organise heard or seen speech into **events**, rather than merely a forced-choice category judgment. It would then ask whether changes in that organisation predict new possibilities for deliberate control—over and above perceptual acuity, articulation skill and explicit instruction. Establishing genuine *mediation* would require especially careful design: all these capacities can develop together through ordinary associative learning.

{==Here several philosophical proposals make different suggestions.==}{##b6370ab3-2cc0-4115-98d1-c7c906fc9c01##} **Executable action concepts**, linked to reusable and parameterisable motor schemas, are central to \citet{mylopoulos:2016_intentions}. On that approach, new intentional control might result from learning an appropriate schema and connecting a concept to it. **{==Dimensional biasing**, developed by \citet{burnston:2017_interface}, suggests that higher-level representations narrow a range of motor possibilities while context supplies much of the detail.==}{##7faf1453-bf97-43b0-a6a9-05cf25f7e667##} **Conceptual-space approaches** can model the relevant action concept as a region of possibilities and a specific motor plan as a trajectory selected within it \citep{brossel:2026_solving}. A learned-translation account puts weight on the acquisition of systematic links across representational formats \citep{christensen:2021_skill}. The experience-mediated hypothesis adds that learning to act may change the very *structure of the thoughts* that participate in those links.

{##b6370ab3-2cc0-4115-98d1-c7c906fc9c01:
∞ One of the pay-offs I'm looking for: is there a case where the different proposals make interestingly different predictions.

This needs qualification: I'm also tempted to think that most of the proposals are not genuinely competing solutions to the Interface Problem but instead provide part of the picture.
##}


{##7faf1453-bf97-43b0-a6a9-05cf25f7e667:
∞ I don't think it's useful to see dimensional biasing \citep{burnston:2017_interface} as a self-standing proposal that competes with the others. Probably everyone should agree that intentions bias rather than fully determine. The question is how they bias.
##}


These are live alternatives, rather than theories that the current speech experiments already discriminate. A learner's improved control would be expected on several of them. What could be informative is the pattern of **perceptual change, conceptual change, schema learning, contextual flexibility and deliberate parameter control**, especially when those achievements dissociate.

A related result offers some encouragement but less than the stronger hypothesis requires. \citet{lametti:2014_plasticity} found that adaptation in producing speech can alter subsequent speech perception. This supports the possibility that motor learning changes perceptual processing. It does not by itself show that motor representations introduce an event-based *structure* into experience, or that this structure is responsible for the learner's newly available action concepts. Those further steps are exactly what makes the philosophical proposal worth testing.

## How far could the case generalise?

Speech is a superb source of experimental leverage partly because it may be **unusually special**. Its production is scaffolded by culturally learned phonological categories, familiar words and highly practised mappings between auditory goals and articulatory movements. If those structures make it relatively easy for a propositional intention to find its way into motor control, success in speech may reveal a special solution rather than a general one.

It is also important to ask what sort of explanation has been achieved. Showing that a phonological plan activates the right speech-motor schema is valuable; the interface problem then asks how an intention recruits that phonological plan. Showing that sensory prediction supports rapid correction tells us about online control; it does not settle why the controlled outcome matches what the speaker intended in the first place. And showing that speaking changes hearing does not establish that concepts of speech actions depend on motor-structured experience.

Yet these limitations are intellectually useful. They stop several questions from collapsing into one another: **content versus format; matching versus selection; acquiring a capacity versus exercising it; recognising a speech action versus being able intentionally to perform it; motor influence on experience versus motor representation as the object of experience.** Speech is a particularly good setting in which to make those distinctions experimentally consequential.

## {==Research directions and feasibility==}{##983631ac-eeab-4e8b-8dde-b52cdb693505##}

{##983631ac-eeab-4e8b-8dde-b52cdb693505:
^do I don't think this is remotely feasible. Unless I'm missing something (and it would be great if I am!), please cut this section.
##}


The first investigation should be **a worked account of how an intention to produce a particular speech expression connects to a phonological plan and then to a motorically specified outcome**. Select one well-studied articulatory contrast and examine what is fixed by the speech intention, what is fixed by phonological encoding, what is left open for motor control, and how auditory feedback revises the plan. The crucial question is where the model provides a mechanism for content-sensitive coordination rather than merely receiving a target from elsewhere.

The more original project would ask whether **learning to make a new speech distinction changes the kinds of speech action one can intentionally think about and control**, and whether motor-structured experience plays a causal role in that change. This connects a tractable developmental or training paradigm to the positive proposal in *Motor in Thought*. It also has a clear potential negative result: flexible intentional control might emerge without the predicted transformation in experience, leaving schema-based or associative solutions better supported.

The prospect is therefore real, though not yet a demonstrated payoff. Research on speech production may locate specific bridges between levels of action representation. Research on speech perception and learning may help explain how some of the *concepts* involved in those bridges become available. The second possibility is the more ambitious philosophical one; the first offers a concrete way to get started.
