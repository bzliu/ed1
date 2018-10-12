# Chapter 5: Learning, Motivation, and Emotion

Learning is the single most important process taking place in the brain.  Without learning, nothing else is possible.  All of our focus on the three-C's of compression, contrast, and control presumes a brain with sensible patterns of synaptic connectivity, that produce *useful* forms of each of these phenomena.  Without learning, neurons would randomly compress incoming sensory information, detecting irrelevant, bizzarre features that don't have any behavioral relevance.  Contrast would compare these random things against each other, producing equally meaningless relative comparisons.  Control would drive us toward random goals, and our behavior would be just a jumble of strange impulses.

Learning is essential because there are *way* (way, way, way...) too many synapses for any kind of genetic process to shape in a detailed way.  There are only about 20,000 different protein-coding genes in the human genome, which is only 2 times the number of synaptic inputs on a *single* neuron.  It is inconceivable that genes could code for any sensible fraction of the 100 *billion* times that amount of information that would be required to configure the full human brain.  This genetic argument accords with the obvious fact that we learn the vast majority of our abilities over an extremely protracted developmental window, in a way that depends critically on the experiences and education that we are exposed to.

Thus, the brain (specifically the neocortex) is fundamentally a *self-organizing* system, which somehow magically transforms raw sensory inputs into *knowledge* encoded in its billions of synaptic connections.  The mystery of this process has long perplexed philosophers, who have explored the opposing ideas of *empiricism* vs. *rationalism* and positions in between.  Empiricists embrace the idea that learning proceeds directly from sensory experience, while rationalists argue that there is no way that raw experience by itself is sufficient to create the sophisticated level of knowledge an adult human (philosopher) has.  Modern scientific approaches to this question retain much of this ancient debate, with some favoring a generous amount of innate knowledge, and others arguing that almost everything is learned.

We'll return to these issues in the Development chapter, but the quick summary is that neither extreme view is likely to be correct, with genetic and experiential factors each playing critical roles.  In particular, there is ample evidence that genes establish broad patterns of initial connectivity and orchestrate developmental transitions, such as synaptic pruning, which in turn strongly influence an experience-driven learning process operating at synapses throughout the neocortex.

Our objective in this chapter is to first understand the nature of these synaptic learning processes, which have been figured out in spectacular detail at this point, and explore some broader ideas about how they might result in this magical self-organization of knowledge over development.  Then, we turn to the forms of learning that were the focus of behaviorism: *classical and operant conditioning*.  These both depend on similar dopamine-driven learning mechanisms operating in the basal ganglia, amygdala, and related areas, which are now very well understood.  These forms of learning shape our core decision-making process to select actions that are likely to be rewarding, and not punishing.

Finally, we broaden our perspective beyond the limited world-view of the behaviorists, and consider the possibility that *internal* factors such as *goals*, *drives*, and, ultimately, *emotions*, might play a central role in driving both our learning and decision-making behavior.  This perspective, long embraced by social psychologists, is only recently beginning to be explored from the neuroscientific angle, which has been perhaps overly-enamored with the remarkable alignment between the classic externally-driven behaviorist conditioning processes and the function of dopamine in the basal ganglia.

## Synaptic Plasticity

If learning is the most important thing in the brain, then the most important thing about learning is that it takes place in the synapses interconnecting neurons.  This idea goes back at least to **Santiago Ramon y Cajal** in the late 1800's, the pioneering Spanish neuroscientist who advanced the idea that interconnected networks of neurons are doing most of the work in the brain.  Logically, the strength of the connections between neurons should alter the patterns of information flow through these networks, and thus makes sense as the primary locus of learning, and knowledge.  **Donald Hebb** cemented this idea with a compelling, well-specified proposal that memories are formed when neurons that are active at the same time increase the strength of their synaptic connections, so that they are then more likely to co-activate each other in the future [@Hebb49].  In effect, learning is "gluing together" the different elements of a memory.  This idea has been captured with the pithy statement that "neurons that fire together, wire together".

However, it was not until 1966 that this *Hebbian* form of learning was actually demonstrated in the brain, by Bliss and Lomo [@BlissLomo73].  They described a form of *Long Term Potentiation* (LTP) of the synaptic strengths between well-defined groups of neurons, where potentiation means "getting stronger" and the "long-term" aspect of it was critical to distinguish from earlier discoveries of synaptic potentiation that only lasted for a few minutes.  If synaptic changes are really the basis for learning and knowledge in the brain, they had better last for more than a few minutes, because clearly our memories and knowlege can last a very long time.

The field of LTP research expanded rapidly from that point onward, and progressively more detailed questions were addressed about the exact nature of what is changing in the synapses, and what specific factors in the activity of the sending and receiving neurons on either side of the synapse were critical for causing it to change.  After many controversies and twists and turns in this amazing story of scientific discovery, we now have a very solid and detailed understanding of how this process works, at least in terms of all the underlying biochemical mechanisms.  It is a fabulous success story for the power of the scientific method, to drill down and figure out exactly how some complex system actually works.  Perhaps most remarkably, Hebb's original idea seems to have been nicely supported, by a remarkable interaction of different moving parts: changing the strength of the synapse requires *both* the sending and receiving neurons to be active.

![Fig 5-1: Mechanisms of synaptic plasticity, resulting in changes in the overall strength of the synaptic connection between the sending axon and the receiving dendrite.  1. The receiving neuron must be active, so that its elevated membrane potential (Vm) kicks out the positively-charged Mg+ ions from the NMDA receptors (2).  3. The sending neuron must fire and release glutamate, which then binds to the NNDA receptors, causing them to open and Ca++ ions to enter (4).  Ca++ then triggers complex chemical pathways that ultimately result in changes in the numbers of AMPA receptors poking out across the membrane, which thus changes the overall amount of Na+ that can enter for any given firing of the sending neuron.](figures/fig_ltpd_synapse.png){ width=50% }

Figure 5-1 shows the major steps in the process of synaptic change.  The receiving neuron must be active enough so that its elevated membrane potential pushes out positively-charged magnesium ions (*Mg+*), which are otherwise blocking the opening of the *NMDA* receptors.  And the sending neuron must be actively releasing glutamate neurotransmitter, as a result of spiking, because glutamate binding to the NMDA receptors (in addition to the AMPA receptors) is necessary to cause them to open.  Whereas AMPA receptors allow Na+ ions to flow into the cell, NMDA allows *calcium* (*Ca++*) ions to enter, and these Ca++ ions then trigger a cascade of chemical reactions that ultimately leads to the change in synaptic plasticity.  This critical role for Ca++ is consistent with many other similar such biochemical processes throughout the body -- again, evolution often reuses existing mechanisms.

The main consequence of Ca++ entry is a change in the number of AMPA receptors in the synapse, which then changes the overall amount of Na+ that can enter when the sending neuron spikes.  Much more can be said about the details of these Ca++ driven chemical pathways [@Rudy13], and the other associated changes that take place in the synapse, but the core logic remains the same as Hebb envisioned it: both neurons must be active for the synapse to change.

![Fig 5-2: Direction of synaptic change as a function of the amount of calcium entering the dendritic spine.  Lower amounts of Ca++ result in LTD = long-term *depression* or decrease in synaptic strength, whereas higher amounts result in LTP = potentiation or increase in synaptic strength.](figures/fig_ltp_ltd_ca2+.png){ width=50% }

However, Hebb overlooked one *essential* aspect of learning, which was also neglected in the early days of research on LTP.  This is the fact that you can't always only increase the strength of synapses.  Eventually, all the synapses would get ever-stronger, and the brain would blow up in a huge epileptic seizure.  Instead, it is equally if not more important that synapses also *decrease* in synaptic strength, which has been named *long-term-depression* or *LTD*.  Decreases may be more important than increases, from the perspective of the *compression* function of neurons: each neuron has to essentially throw away a huge amount of information in order to compress its 10,000 inputs into a single output signal, and LTD makes synapses weaker and thus facilitates this information filtering process.  In any case, Figure 5-2 shows that the balance between LTP and LTD is a function of the overall amount of calcium entering the dendrite -- lower amounts result in LTD, while higher amounts result in LTP.  This behavior emerges from a competition between two different chemical pathways, one which drives LTP and the other LTD, and their relative dependence on Ca++ levels.  This is yet another tug-of-war taking place within neurons -- this competitive dynamic is a very commonly-used mechanism at all levels of the brain.

One intriguing finding that makes sense in terms of this balance between LTP and LTD, is that weak activation of perceptual inputs seems to make those things harder to see, while strong activation makes them easier to see [@NewmanNorman10].  Thus, the weak activation leads to the lower levels of Ca++, and causes LTD, whereas the stronger activation drives higher levels and LTP.

## Neocortical Learning

Now that we know in detail how learning operates at the synaptic level, you might think that all of the mysteries of brain function should be solved, given what we said about the essential role of learning.  Unfortunately, this is not the case.  There are a number of challenges here, but chief among them is that there are so many synapses and neurons involved in learning any given bit of knowledge, that it is essentially impossible to go directly from behavior of the individual synapse up to this *emergent* behavior of learning in the larger neural network.  The major tool that can be used to bridge this gap are computer simulations of neural networks, with equations capturing things like the function shown in Figure 5-2, and the overall firing activity of neurons in response to stimulus inputs, etc.

Extensive work with such models has repeatedly shown that the known Hebbian-like learning mechanisms described above does *not* result in the kinds of larger-scale learning that people are clearly capable of.  The reasons for this are well understood, but beyond the scope of this discussion.  Furthermore, the kind of learning that *does* work reliably in these neural models, and is used in the recent powerful AI (artificial intelligence) models currently powering the speech recognition and other advanced capabilities in your cell phone and other gadgets, is called *error backpropagation* [@RumelhartHintonWilliams86], and it makes some additional demands on the biology that some influential people have argued are implausible [@Crick89].

This problem has been my specific area of research for over 20 years, and my colleagues and I have developed progressively more biologically plausible models of how this error-driven learning process could work within the neocortex [@OReilly96; @OReillyMunakataFrankEtAl12].  Our latest idea is that the brain is constantly making predictions about what will be seen next, at a rate of about 10 times per second (i.e., the *alpha* frequency), and very specific patterns of neural connectivity in the neocortex and thalamus provide a "ground truth" correct answer against which those predictions are compared.  Thus, the difference between these predictions and what actually happens provides the error signals driving learning, and we have shown how these error signals, which exist as differences in the activity states of neurons over time, could drive learning in synapses throughout the neocortex.  Furthermore, our computer models show that this form of learning can indeed acquire the kinds of sophisticated knowledge that people do, for example the ability to recognize different categories of objects.

There is just one problem with all this: while our proposed synaptic plasticity mechanisms are consistent with the existing body of detailed knowledge, they also make a few extra demands that have not been tested empirically.  So we do not yet know if this theory all goes through or not.  Furthermore, there are various other different theories about how all of this could work, which make different, testable predictions.  Thus, hopefully we'll get some answers in the not-too-distant future, and then we can potentially connect the dots all the way from the beautifully detailed biochemical level up to the high-level effects of these mechanisms in forming new knowlege representations within the neural networks of the neocortex.  For now, we have to live with a glaring hole in our overall understanding of this most important process of learning in the brain.


## Dopamine-modulated Learning

Most introductory textbooks do not address any of the above topics in learning, and focus exclusively on the relatively well-understood domain of conditioning, which has been studied since the days of Pavlov and the behaviorist school in the early 1900's.  This has become an area of renewed interest in neuroscience, since the discovery that dopamine activity almost perfectly accounts for the nature of these conditioning phenomena [@MontagueDayanSejnowski96; @SchultzDayanMontague97].

### Classical (Pavlovian) Conditioning

![Fig 5-3: The classical conditioning paradigm. ](figures/fig_classical_conditioning.png){ width=80% }

The classical conditioning paradigm (Figure 5-3) centers around learning the connection between a previously *neutral* stimulus (the **conditioned stimulus** or **CS**) and a biologically-established, affectively significant *outcome*, known as the **unconditioned stimulus** or **US**.  In the classic experiments by Pavlov, the ringing of a bell served as the CS, and food reward as the US, and the subjects were dogs, who learned over a few repetitions of the CS followed by the US to salivate after hearing the bell, in antipation of receiving the food. The salivation is somewhat confusingly labeled the **un/conditioned response** (U/CR), where it is *un*-conditioned (UCR) prior to learning in response to the food US, and *conditioned* (CR) after learning in response to the CS.  So, the same response has two different labels depending on what is driving it.  Ecologically, this simplified lab experiment is thought to capture the real-world learning about different stimuli that help us anticipate and prepare for important upcoming outcomes.  For example, when you are hungry and driving down the highway on a road trip, the sight of a McDonald's sign alerts you to the availability of food there.  Thus, the McDondald's sign is effectively a CS, and indeed this conditioning paradigm applies well to the goal of advertising, which is to establish a solid connection between a brand logo and desireable US outcomes.

![Fig 5-4: Dopamine neuron firing in a classical conditioning paradigm of CS followed by US (labeled R for reward -- it was actually a drop of juice).  Top: Unexpected rewards (at time point R) drive dopamine firing.  Middle: Trained CS followed by R shows dopamine firing at the CS, but *not* for the reward.  Bottom: Trained CS followed by *omission* of R shows reduction of firing at R. Each row of dots shows when a dopamine neuron fired a spike on a given recording trial, and the bars at the top show the accumulated histogram of all the spikes at that corresponding point in time across all such trials.  Dopamine does *not* respond to raw reward input, because it fails to fire in when the reward is accurately predicted by the CS, in the middle panel.  Furthermore, it directly signals "dissappointment" by reducing doapmine firing when an expected reward is not received.  These and many similar results show that dopamine responds to the *contrast* or difference between predicted and actual rewards.  From Schultz et al, 1997.](figures/fig_schultz97_vta_td.png){ width=40% }

Although Pavlov and the behaviorists where exclusively concerned with overt behavior such as salivation, we now know the internal biology that drives this form of learning.  Figure 5-4 shows how dopamine neurons in the *ventral tegmental area* (*VTA*) of the brainstem reticular activating system respond in a classical conditioning experiment [@Schultz86; @SchultzDayanMontague97].  When the US (labeled R = reward, a juice drop) is presented without any prior CS, dopamine responds with robust firing above its "tonic" steady base rate of firing.  This is consistent with the naive idea that dopamine encodes raw reward signals.  However, when the very same reward is presented after a CS (which has been reliably paired with the reward in prior conditioning trials), *dopamine no longer fires to the reward!*  Furthermore, when the CS is presented and the reward is *withheld*, dopamine neurons  show a suppression or *dip* in firing below their tonic baseline.  Psychologically, you would feel dissappointed if you didn't get the reward you expected, and indeed that is exactly what the dopamine neurons are signaling.

These results, from the pioneering work of *Wolfram Schultz* and colleagues, have profound, far-reaching implications, and represent one of the most exciting and important findings in neuroscience.  They are also one of the most important examples of the *contrast* principle, as we emphasized in the Introduction.  Specifically, these results show that dopamine neurons respond to the contrast or difference between an expectation or prediction of reward, and what is actually received, *not* to the raw reward input itself.  As we suggested in the Introduction, this contrast property of dopamine is what drives insatiable greed, dissatisfaction, and apathy, because once we learn to expect any given positive reward-like outcome, we no longer receive dopamine for it!  This property of dopamine is what causes kids to be so entitled and spoiled: they come to expect all that coddling from their overprotective parents, and all the excitement they get from playing video games, so that when they finally get out into the "real world", it is all so difficult and filled with dissappointing drudgery.  It is also why so many famous people, especially rock stars it seems, turn to dopamine-activating drugs of abuse -- once they adapt to their new amazing famous lifestyle, their dopamine system no longer gives them that amazing feeling of unexpected reward.  Drugs like cocaine artificially bypass the expectation-driven contrast mechanisms of the dopamine system, producing more reliable bursts.  However, even here the system slowly adapts and more and more drug is required to achieve the same effects, so really there is no escape from the evil maw of the dopamine contrast effect!

From a hard-nosed learning theory perspective, there is a very good reason why the dopamine system must work in this contrast-based way: *learning is most efficient when it is focused on what is not yet learned.*  Learning something you already know simply doesn't make much sense.  Thus, in the case of classical conditioning, continuing to learn about the fact that the CS predicts the reward after the system has already acquired this association doesn't make any sense.  And this logic shows that dopamine is fundamentally a *learning* signal, not a reward signal.  In particular, as we'll see in the next section, dopamine directly affects learning in the basal ganglia and other brain areas, including the areas that are learning about the CS -- US association in the first place.  Thus, as dopamine stops firing at the time of the US (R, reward), it stops the further learning of this association.

This basic theory of how learning should function was systematized by *Robert Rescorla* and *Allan Wagner* in a seminal paper [@RescorlaWagner72], where they proposed a very simple mathematical "learning rule" that says that the amount of new learning should be proportional to this contrast or difference between what you already expect the reward should be, and the actual reward you receive.  Roughly a decade later, *Rich Sutton* and *Andy Barto* published an important extension to this idea [@SuttonBarto81], known as the *temporal differences* (*TD*) learning rule, which can also account for the fact that dopamine learns to fire at the onset of the CS, even as it stops firing for the expected US.  Furthermore, this work led to the development of many advanced mathematical techniques in a field collectively known as *reinforcement learning* (*RL*), which is a branch of *machine learning* that deals specifically with learning from overall reward / punishment signals.  These RL techniques have been used in many different AI technologies, and play a central role in the recent advances from the Google DeepMind group, in their models that learn to play Go and challenging video games [@SilverSchrittwieserSimonyanEtAl17; @MnihKavukcuogluSilverEtAl15].

![Fig 5-5: Biological systems involved in classical conditioning.  The vertical organization reflects the separable contributions of the amygdala to forming CS -- US associations (labeled "LV" for "learned value"), and the ventral striatum in driving contrast-with-expectation firing in the dopamine system (VTA / SNc) (labeled PV for "primary value" -- together these constitute the PVLV system named in honor of Pavlov).  Horizontally, the BLA (basolateral amygdala) within the LV system learns to associate CS's with corresponding US's, while the CEA (central amygdala) reduces these higher-level associations down to specific go / nogo signals in a basal-ganglia-like fashion, and directly drives dopamine firing and core behavioral responses (*conditioned responses*) appropriate for different US's.  The PV system likewise has a cortical component in the ventral and medial areas of the prefrontal cortex (vmPFC), and a basal-ganglia component in the ventral striatum (VS).  Dopamine firing in the VTA / SNc drives learning throughout all of these areas.](figures/fig_bvpvlv_functional_org_simpler.png){ width=40% }

Although the TD learning rule provides an elegant and powerful mathematical description of classical conditioning, the brain networks actually involved in this form of learning are considerably more complex.  Figure 5-5 [@MollickHazyKruegerEtAlsubmitted; @HazyFrankOReilly10] shows a summary diagram of these networks.  Conditioning learning involves interactions between two "vertically" organized sub-systems, one involved in forming associations between CS's and US's, which depends on different areas in the *amygdala*, and another that drives the contrast-with-expectations differences in the dopamine system, which depends on the ventral (bottom) areas of the striatum in the basal ganglia.  Furthermore, within each of these systems, there are separable contributions from cortex and cortex-like processing in the amygdala, versus the go vs. nogo kind of decision-making that the basal ganglia is specialized for (which we'll learn more about in the operant conditioning section below).  This framework can account for a wide range of data about the biology and function of dopamine-driven learning in the brain, and, given the overall complexity of the system, the ability to simulate it all in a computer model is essential for understanding how it all works.

#### Extinction and Context in Conditioning

As was the case with LTD (long-term-depression), figuring out how the associations between CS and US are *unlearned* is just as important as figuring out how they are learned.  This involves the phenomenon of *extinction*, where the CS is repeatedly presented while withholding the US.  From Figure 5-4, this should produce repeated *dips* in dopamine levels, which in turn should drive LTD in synaptic connections, causing the association between the CS and US to be unlearned.  While this all does occur, the situation turns out to be considerably more complicated, in ways that make sense ecologically.  To make a long story short, the brain actually learns *new associations* during these extinction events, in addition to weakening (somewhat) the existing ones.  These new associations effectively encode *context-specific exceptions* to the original association -- e.g., "in this particular situation, you're not going to get the food, but you might still get it in other situations".  Furthermore, the nature of this new learning is under top-down control from the ventral / medial frontal cortex, which can play a critical role in interpreting the nature of what is going on: has the world really changed, or is it just kind of random? [@QuirkMueller08; @GershmanBleiNiv10]

The advantage of all this is that the initial CS -- US association is relatively preserved, and expecially if this was something learned through a painful, dangerous experience, it is probably a good idea to keep these memories around.  Better safe than sorry.  The disadvantage is evident in the phenomenon of PTSD (post-traumatic stress disorder), where traumatic memories cannot be extinguished, and keep intruding into normal life.  There are significant individual differences in the extent of PTSD, and a major factor reflects the ability to exert top-down control and establish a strong new context to override the traumatic situation.

In the lab, these extinction phenomena are observed in the phenomena of *spontaneous recovery*, *reinstatement*, and *renewal*, which are typically observed in aversive conditioning situations (i.e., when the US is a negative outcome, like getting shocked).  Spontaneous recovery refers to the re-emergence of the CS -- US association after extinction, without any further training, clearly showing that extinction learning did not erase this original memory.  Reinstatement occurs after a single US presentation without the prior CS, after which the CS -- US association is reinstated.  The US reactivates the associated memories and this is enough to overcome the extinction learning.  Renewal is particularly revealing of the important role of context.  In this case, the subject is conditioned in one environment (A) and extinguished in a second, novel context (B).  When put back into the original context (A), the original CS -- US association is *immediately* effective without any further learning.  In other words, the subject learned a context-specific exception ("when in context B, I won't get shocked") instead of unlearning the original association.

### Operant / Instrumental Conditioning

Classical conditioning is the sensory front-end to the other major form of learning studied by the behaviorists: *operant* or *instrumental* conditioning.  This form of learning occurs through the reinforcement or punishment of *actions*, instead of stimuli.  The central idea is captured in **Thorndike's law of effect**: *actions that lead to good outcomes are more likely to be taken, while those that lead to bad outcomes are less likely*.  This is so intuitive that it is difficult to imagine it being otherwise, but nevertheless, it captures a considerable amount of behavior in humans and animals.

![Fig 5-6: How increases in dopamine (bursts) and decreases in dopamine (dips) drive learning in opposing Go vs. NoGo pathways in the basal ganglia.  Through the complicated basal ganglia circuitry, the firing of Go (aka direct pathway) neurons leads to a net excitation of motor plans in the frontal cortex.  The NoGo pathway has the opposite effect, preventing the frontal activation that would otherwise occur from Go activation.  When an action leads to an unexpected positive outcome, the resulting dopamine burst activates a special type of dopamine receptor (the D1 receptor), which drives LTP learning in the input synapes to the Go neurons.  This makes those neurons more likely to fire again under similar circumstances, achieving Thorndike's law of effect.  The opposite happens when dopamine dips occur for unexpectedly bad outcomes, which interesingly has a net LTP effect on the NoGo neurons via D2 receptors, and an LTD effect on the Go neurons.](figures/fig_bg_frontal_da_burst_dip.png){ width=100% }

We now know how this type of learning works, in terms of dopamine's effect on the basal ganglia (Figure 5-6) [@Frank05; @GerfenSurmeier11].  Unexpected positive outcomes following a given action result in a burst of dopamine (as we saw in Figure 5-4), and this dopamine burst acts on D1 receptors located on the "Go" neurons of the basal ganglia to drive LTP of the synapses into the neurons that decided to trigger that action.  Thus, these stronger synaptic inputs make it more likely that the same action will be triggered again in the future, when similar inputs are driving the basal ganglia (i.e., in similar situations), thereby achieving Thorndike's law of effect.  The opposite pattern of changes occurs when unexpectedly bad outcomes arise, which drive dips in dopamine firing, and end up strengthening inputs to the "NoGo" neurons that compete against the Go pathway and prevent an action from being triggered.  Thus, actions that lead to bad outcomes are less likely to be triggered, consistent with the other half of Thorndike's law of effect.

#### Partial Reinforcement

Gambling etc

## Motivation

* key distinction is external (extrinsic) vs. internal (intrinsic).  Behaviorists emphasized external factors: reward / punishment.  internal factors seem much more important, given everything we subjectively know about ourselves.  Did behaviorists really think that everything *they* were doing was just the result of external reward and punishment?  Didn't they have any actual subjective insight into their own motivational systems?  Didn't they have *goals*, *desires*?

## Emotion and Arousal

* extensive interconnected networks of areas devoted to emotion and arousal, at all levels of the brain.  thus, from the modern perspective, emotion is as much of an emergent, interactive process as anything else in the brain.  However, historically, people took rather extreme and somewhat strange and hard-to-understand perspectives. James-lange / Cannon-Baird etc.

* is emotion really what makes humans unique?  hollywood clearly thinks so: evil robotic non-emotional beings...  part of this is that emotion is what keeps us from harming each other: psychopaths lack that basic emotional connection.  So, from a survival perspective, we really depend on everyone sharing these protective emotional responses, and anything that doesn't is immediately scary and foriegn.  

* circumplex model.
