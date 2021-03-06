Book review: Principles of Neural Design
========================================
Taking a physics approach to neuroscience
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Principles of Neural design <https://www.goodreads.com/book/show/23582015-principles-of-neural-design>`_ tries to do just that:

Very roughly, the book can be divided into three main parts:
- various introductions of the design principles, epilogues 

So what are those design principles?

Highlights: Evidence for optimality
-----------------------------------
Further evidence of design principles
-------------------------------------
Criticism: Pro-brain bias
-------------------------
Principles of biological constraints
------------------------------------
Other comments on the book
--------------------------

Text comments for the talk:
Talk/Book review: Principles of neural design
=============================================

idea: Wade through the mountains of data to understand how brain is optimized to process information at all scales


Introduction: 50k neuroscientists
Chapter

page 470: design principles, "what fires together, locates together" (p. 95)
LMC: Large monopolar cell

brief bursts: don't know if "bursts" are meant to be multiple spikes

Organization
concentrate on vision/higher levels only in chapter 12/13
lots of numbers

not that much about higher brain functions

NOW first go through chapters schematically 

Criticism:
pro brain bias, brain optimal under constraint of computing with proteins in water...
which is terrible idea in the first place (milliseconds instead of nanoseconds, high noise, low reliability of structures...), like travelling to china on pogo sticks

computers being compared with are outdated

sometimes don't know where numbers come from

sometimes the physics seemed inaccurate/incorrect to me where I could check it

can still contain details, sometimes a bit verbose for my taste/too much rambling about life/philosophy?

joke: they could have "sent only what is needed"

doesn't clearly distinguish between qualitative and quantitative evidence for optimization
a   
not clear if reducing spike rate is really the point, after all, we also want to do the computations some time, and maybe that's the point!

(often talks about maximizing information, but actual thing to maximize is value-of-information...)

Chapter 2: E coli saves information about environment by lactose, (img p 39/fig 2.2): only synthesizes lactase if no glucose, but lactase


40: 1 second memory of receptors for chemotaxis (biased random walk)

Paramecium: much faster, electrical (membrane potential) signalling (which would be too complex for e coli), can move backwards when ramming obstacle, diffusion is not enough due to larger size (img 44)

next: C Elegans (p. 48)))

How cyclical behaviour generated? C Elegans no central pattern generator, but uses body in feedback loop for oscillation/movement, embodied computation, also used in robots (claims 'revolution' for robots, but haven't looked into extent to which it is really that important today) p. 50

circuit for avoidance: p. 53
1 peptide determines degree of sociality p. 56 up

For example, NaCl (salt) normally attracts worms, but when a worm has
been starved in the presence of salt for only 10 minutes, it later avoids salt. (p. 57)

chemical computing (e.g. strength of chemotaxis by odorant is learned depending on whether odorant is associated with food)

60 low/61 up, design principle: to save energy per accuracy, send as slowly as possible

minimize wiring costs predicts position of 90 % of neurons (61 down/img 62)

small size: no spikes needed (62 down)

ch 3: larger brains
67/68 up: similarities between mouse+fly brain

then lots of stuff about how brain anticipates demands/changing circumstances in body and world and acts upon it

set up terms of trade: bits/spike, ATP/spike, bits/ATP (76 down/77 up calculation, img 78/ img 79 up diagrams). law of diminishing returns,  ax diameter prop spike rate, axon volume rises as spike rate ^2, axon diamater prop firing rate - but I didn't understand why (maybe most important figure of book, used over and over again to explain stuff)

didn't understand "measured bits per spike"

 send only what is needed ; send at the lowest acceptable rate; minimize wire, that is, length and diameter of all neural processes. see chapter 13: entire chapter on efficient wiring!
 
83 anabolism vs catabolism

fig 85 wired vs wireless communication (SCN suprachiasmatic nucleus includes master clock, 8.6k neurons in humans)

86 hypothalamus sends simple instructions, can be said to be driver of ultimate decision making

clear enough that a cat can be made to behave in particular ways by stimulating regions of hypothalamus

(joke: ultimage decision-making comes from the hypothalamus and not the prefrontal cortex!)

hypothalamus: low energy consumption

121: central complex in insects, also stimulating 1 neuron induces fighting behaviour etc

fig 91/92 up wired/wireless communication

fig 94: rat brain, where is hippocampus?
  superior colliculus (orient head and eyes toward key information sources)

95: pattern generators in spinal column
neurons that fire together should locate together. explained by example of motor neurons vs fire together wire together (fig 97)

98: investment into certain senses/frequencies/wavelength depends on important stimuli for animals, of course (bat ultrasound up to 180 kHz, DON'T know how does that work?)

100: diameter/quantity of axons by sense, vestibular: hearing nerve
 (during talk: also link to auditory brain areas higher power density)

(fig 102: mormyrid has much bigger cerebellum because of high-frequency electrical signalling)

 
 also speech low frequency
 
101: structure of music is similar to universal structure of speech, but I didn't learn how exactly
 The Statistical Structure of Human Speech Sounds Predicts Musical Universals
https://www.jneurosci.org/content/23/18/7160

 Dissonance sensation is a result of brain's response to unusual or rare sound perceptions (Pankovski and Pankovska 2017). The brain is remembering and ranking the sound patterns that usually enters the ears, and if an unusual (rare occurring) sound is listened to, a well known EEG pattern emerges (P300/P3b) indicating an oddball event. This causes slight stress in the listener, which is causing the sensation of dissonance. In the same paper, Pankovski and Pankovska show by a software simulated neural network that the brain is capable of such remembering and ranking of the sound patterns, thus perfectly reproducing the well known Helmholtz's list of two-tone intervals ordered by consonance/dissonance, for the first time in the history of studying these phenomena. As a consequence, Pankovski and Pankovska suggest that the consonance and dissonance are biologically dependent for the more consonant sounds, and culturally dependent for the more dissonant sounds.

 104: sample densely with one part of the sense, not densely with the rest (fovea, homunculus etc), 
 
 106: superior colliculus connects retinal map with motor map directly to drive eye to location of interest,
 generally: filter out stuff, similarly: locusts shut of ear when they are chirping
 
 107: corollary discharge: colliculus tells eye has been moved, so that rest of brain can compensate, compensation occurs "frontal eye field" in the front of the brain (after low-level eye processing has occured), this is done even though wire is very long (107 seems to imply that command where to look also comes from there? TODO seems unclear)
 also insects
 
 109: thalamus recodes messages to get more bits per energy/fewer spikes per second (more in chapter 12 "beyond the retina"
 exception: olfactory sensors which are already slow enough, just olfactory bulb
 
 109 down, 110: cortex
 mouse cortex divides into about 20 areas, whereas human cortex has about 200 (Kaas, 2008).

organization of cortex from behind to front towards higher-level processing

areas close to where they are needed (face areas in front, object-grasp areas behind with coarser processing)

112: learning, motor learning (within intention learning) vs reward-prediction learning

conclusions: mammalian brain uses principles send only what is needed,
at lowest acceptable rate
minimize wire

113ff: insect brain
neuromodulators+hormones: over 50 neuropeptides, autonomic neurons, apparently common evolutionary origin

fly brain: img p 115
116: octopamine is insect's adrenaline, clocks by light

drosophila sing to each other for courtship (up to 500 Hz), mechanosensors gain approaches limit set by Brownian noise

moth detects bat ultrasound, dives to ground
male housefly fovea: lovespot

118, img 119: insect visual processing resembles mammalian, retinotopic organization abandoned in last stage (optic glomeruli) similar to ventral stream

img 119: sparse code, TODO is this Bloom filter?

#121: central complex: decision-making, img 122, homologous to basal ganglia, ~600 neurons (counted) TODO but basal ganglia never mentioned before

#123 complex behaviours can be evoked by stimulating single neurons like in cat

124 corollary discharge like in mammals (e.g cricket disables ears when chirping, img p 126)

125 flies do motor learning, improve motor performance with practise, fly in flight simulator adapts within 24 hours like students with inverted glasses
RPE using dopamine and octopamine (said fig 14.11, but it doesn't exist :-( )

127: bee can navigate a maze via symbolic cues
(blue, turn left; yellow, turn right)
associate a flower with the time of day during which that particular species produces nectar.

perform delayed match-to-sample and symbolic match-to-sample tasks 
that were thought, until recently, to be confined to monkeys, human, dol-
phin, and pigeon (Srinivasan, 2010; Menzel, 2012), but I don't know what this is

insect's small size of brain can apparently be much more efficient per neuron, capacity grows sublinearly

(JOKE: just as we know in academia and HPC)

128 embodied computation: 10 Hz spikes enable 200 Hz wing-beat of drosophilia thanks to resonance, legs are yanked straight by same muscle that starts the wings -> fly jumps+

129 up: heuristic of wrong bearing of bee, depending on time of day, but didn't really understand it

Chapter 5: Shannon coding theory
basics of information transfer in neural networks
basics of information theory
138: information rate of analog signal in dependence of S/N by frequency

img 141: allostery, how proteins process information
(img 143 up: AND gate in proteins TODO understand)
img 144 up: example, motion requires several hundred microseconds! TODO practise explaining
more stuff on how it stops
147f: Landauers principle, 1 ATP = 25 kB T, 3 ATP molecules, less than 1 covalent bond

summary: principle "compute with chemistry"

Chapter 6: Protein circuits
img 151 cascade amplifier in electronics vs photoreceptor
152 diffusion time prop d^2 m^2 e^(-lambda c)
->large distances, short times need electrical signalling

151 6.1 output, below/ img 152 up: various functions in var regimes

154 tradeoff high vs low affinity receptors: sensitivity vs frequency
154/img 130 up: cooperative binding yields steeper functions
img 157: various computing chemical circuits, but didn't yet learn how they work
158 against noise: complexes, compartments, switches, higher thresholds, last resort: redundancy

160, img 161 up: energy signalling efficiency by array size/redundancy
consider optimum redundancy including building cost, but no quantitative confirmation as I understand, also value of information a bit fuzzy

162 pros and cons of chemical circuits (cheap vs long-distance)

163 down, img 164 ion channels, 60 % of power in brain used for sodium-potassium pumps

167 channels open/close within 10s of microseconds, near limit of allostery

power gain ×1,000/millisecond open

chemical->electrical energy conversion efficiency of pump: 50 %! channel uses 2000x more ATP than G protein cycle when operating for 1 ms

169/170: describing I/O function of channel
171 computing various thing with I O like chemical img 157
img 173 spike and channel activation plot

176f constraints on infoproc performance with channels: (1) the high electrical resistance of single channels, (2)
membrane capacitance, and (3) channel noise from thermal fluctuations in
single proteins.

177 number of channels is limited by number of pumps, which is limited by area of neurons

178 numbers on ATP power and channeldensity

178 space requirements of mitochondria make it suboptimal, this is example of optimization constrained by basic cell biology

Design of neurons
181 overall, the mammalian brain
transcribes 5,000 to 8,000 genes and uses alternative splicing to produce
50,000 to 80,000 distinct proteins.

182 dendrites conduct passive electrical signals about 50-fold faster than chemical diffusion, and axons conduct active electrical signals at least 20-fold faster than dendrites.

185 cleft width appears to optimally balance transmitter concentration at the
postsynaptic receptors and electrical resistance 

186 SNAREs for vesicle release

186 chemical signal peaks within 600 microseconds, lasts <1.5 ms
cooperativity -> steeper response curves->sharper timing

188 design ovf vesicles
presynaptic quantum costs 23k ATP, postsynaptic response ~10 times as much

img 190: receptor clusters much smaller for fast auditory cells didn't understand but why smaller not bigger?

192/193 various receptors and timescales
192 AMPA fast, marked text: NMDA coincidence detection 100 ms, because gluatamate unbinds slowly, mGLuR even slower (tens of seconds)

197 dendrites complicate their design

analogue dendrites, spiking axons, 198: tree may send spikes backwards for e.g. learning

199 spikes useful for long-distance, but analogue->pulse loses as much as 90% of information
initial segment: conversion analogue->spike

200 microtubule: ferry cargo, finest axon are limited in smallness by having to contain one microtubule

202 dendrodendritic/axoaxonic synapses/gap junctions compute locally, save energy

204f strange synapses: starburst, polyaxonal amacrine (img 205)
206 glial cells: 70 % of mitochondria in optic nerves!, don't know what they need that energy for, img 207
208 glial can express transporter proteins

213 spillover to maintain S/N

209ff explain motivations for different neuron variants by cerebellum/Purkinje cells

chapter 8
mammalian vision: channels close after photon, fly vision: channels open after vision img 221 up

img 223 baboon in starlight photon capturing , img 233 baboon in daylight
tradeoff thermal false positives vs false negatives opsin flabby

225 stack of rhodopsin

fly is faster than mammalian
244 contrast coding vs local mean intensity

fly photoreceptor reduces transduction proteins when it gets brighter (img 246)

247ff space/energy efficiency of fly photoreceptors: fly is faster but consumes more energy because it opens channels when light influx, BUT didn't yet understand why

A blowfly
resting in sunlight uses 8% of its energy to power electrical currents in pho-
toreceptors.

250 Three factors reduce a fly photoreceptor’ s efficiency. First, transduction
has intrinsically low quantum efficiency, because cylindrical microvilli
pack rhodopsin less efficiently than the rod’ s flat discs and the cone’ s folded
membranes. Second, signals amplified by positive feedback are noisier.
Therefore, to achieve a given sensitivity and S/N, a fly photoreceptor must
be larger. A larger neuron draws more current, and this increases energy
cost. Third, and most significant, the fly’ s one-type-fits-all design is inher-
ently inefficient.

img 257 different insects with different speeds have different photoreceptor reaction, but I don't understand why blowfly has greater bandwidth with sustained photoreceptor reaction

261 lamina amplifies signals of photoreceptors, costly because bandwidth and S/N costly

264 wire minimized

img 265 look, img 267 schematics of schematics, but didn't understand it in detail

273 down what they call "predictive coding" reduces need for energy by removing temporal+spatial correlations (img 275 illustration)

273 predictive coding more efficient because implemented presynaptically

279 extracellular space is involved, but I didn't learn how, img 281 shows it

282 LMC axons, which I didn't learn what it is

img 284 LMC coding is optimized for probability distributions of natural scenes ("figure 5.2" would be img 134), implementation: on page 285

img 286 also for temporal statistics! theoretical optimum and observed data match pretty well, but didn't learn how calculated, also slower=better, more accurate, but less temporally resolved in starlight, (287) this is optimal, also indermediate at intermediate light levels

img 286: OFF response grows in amplitude, narrows in duration
287 low: echanisms also explained in that chapter
288 tetradic synapses

NOTTODO LMC changes membrane potential during movement 9.5 right

Chapter 10
analogue for mammals, here signals have to travel more than about 1mm and can't stay analogue as in lamina
1 mm is limit

290, img 291: Photosensors use two synaptic stages: first, they recode to synaptic vesicles that modulate a graded voltage in a second-order neuron, staying largely in analogue mode; then they recode to spikes in a third-order neuron.

291 analog voltages: more than 100 bits per second

img-292: stage for recoding depends on magnitude of init information rate, vestibular (balance) axon the thickest, baseline 100 Hz, but I didn't learn why??

(img-294) olfactory/skin sensor response
img-296 auditory hair cells, input: channel is opened by stretch-sensitive protein

273 up one auditory hair cell connects to 20-30 axons to carry the info
298 highest sensitivity in mice/humans to cries of babies

img-300 vestibular cells, vestibular cells aim for high precision, so several hair cells->one axon, REMARK here we see a problem of having to encode by amplitude (which can only enclode log #amount bytes), rather than more sophisticated recoding like in digits

301 retina has two stages because no chemical/mechanical filters to reduce information, so neurally reduced

img-307 cone electrical coupling: low-pass filter, reduces noise

img-313 optimal convolution is Gaussian, this is done

img-330 receptive field overlap maximizes information
img-332 ganglion cell arbors match contrast distribution

335 sparser array structure for high temporal frequencies cells, denser for low freq cells (img-337)

img-339 natural scenes freq distribution
340 nonstringent vs quasi-stringent filters

img-343 starburst amacrine cells from before ("design of neurons")
Wikipedia: The six types of retinal neurons are bipolar cells, ganglion cells, horizontal cells, retina amacrine cells, and rod and cone photoreceptors. 

img-349 beyond the retina overview
img-351 retinotopic connections

img-355 design of quasi-secure synapse, but didn't yet learn it
img-358 resource/active zone investment along processing pathway

359 six reasons for thalamic relay
gating from brainstem
spike timing
expansion
lagged signals
project type as bundle
feedback/selective gating from cortex...

361 V1 leaves separate lines separate
363f/ img 365: Gabor filter in V1 are optimal coding
364: Recall that the two-dimensional Gabor function optimally encodes space
and spatial frequency, extracting the maximum mutual information given
the statistical properties of natural images

didn't understand: what is difference-of-Gaussians vs Gabor? why 1 in one place, Gabor in another?

TODO until 379

377 V2 can detect contours, separate figures from ground, not proven to be optimal in any sense

TODO what are "first-order"/n-th order image statistics as in 377 down/378 up?

378 V2 is the limit of what is understood on millimeter scale

378 similarities of auditory cortex to V2

379 V2 is the last area where a lesion causes blindness

381 special areas for scenes (register viewpoint change/navigation)
381 ventral vs dorsal stream

382 face cells etc
383 down specialized areas with quite clearly understood functions -> specialized disorders
384 parallels in auditory: ventral/dorsal stream

chapter 14: Learning as design
img-440 early/late LTP


chapter 5:

energy consumption for infoproc: 25kB T (vs 0.7kB T Landauer limit)

chapter 6
diffusion time prop d^2, concentration prop exp (-d)

Conclusion (chapter 15)
fly + human brain have evolved in parallel, evolved same efficiency, so it seems that the brain already achieved an optimum of some sort

chapter 12:
noise when discriminating dark spot entirely at retinal output

page 284: exact degreeof coupling appears to maximize total information from the array (Design of a Trichromatic Cone Array)

302: Could a cell then continue to improve its S/N by extending its dendrites
ever farther to collect more synapses? No. Spatial correlations decline expo-
nentially across natural scenes whereas S/N improves only as the square
root of added synapses.

don't like the lack of quantitative results, it's not made clear if something is qualitative or quantitative


60 % of human brain energy cost in restoring ions

