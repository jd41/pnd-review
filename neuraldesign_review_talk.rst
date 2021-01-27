Book review: Principles of Neural Design
========================================
.. note::
   The idea of the talk was to present a PDF viewer showing the annotated book and enter
   appropriate pages during the talk/discussion. I am working with page numbers
   from the PDF viewer, where
   
   page number in the PDF view = page number in the book + 25.
   
   Get in contact to get my annotated/highlighted PDF (not in the GitHub repository for copyright reasons, different versions may count pages differently).

Motivation for the book
-----------------------
- **Idea**: Wade through the mountains of data to understand how nervous systems are optimized to process information at all scales

- **More details**: summary, to be found on `Goodreads <https://www.goodreads.com/book/show/23582015-principles-of-neural-design>`_. (*open link, talk about 50k neuroscientists, "this is the first number, there are a lot"*)

- **Take a physics approach to neuroscience**
(Rutherford quote: "All science is either physics or stamp-collecting")

.. not done here: discuss sociological differences between neuroscience and physics
.. e.g. for neuroscientists, doing experiments is apparently higher-status, while for physicists, explaining them is

What are the design principles?
-------------------------------
*open, discuss page 470, 471*

How is the brain optimal?/My view on this
-----------------------------------------
- Example of principle "Adapt, match, learn and forget"
- **Page 286/figure 9.11:** One highlighted piece of "evidence for optimality": Time response of LMC - large monopolar cell - in fly's visual system maximizes the transmitted information, if one models the natural scenes as randomly picking intensities of certain frequencies according to predefined power density
- This is quite impressive, as it shows functional optimization (i.e. optimization of a function) in the brain
- But it also displays the book's weaknesses:

  - They say the LMC coding scheme is "optimal", but it's optimal only when modelling natural scenes as "videos whose Fourier transforms are drawn randomly"; videos randomly generated like that would not look like natural scenes
  - JPEG (or more recent HEIF) would presumably compress better
  - TODO: It would be interesting to generate "natural scenes" by a power distribution as in the book;

- **Page 284/figure 9.11** is a different illustration of LMC's "optimality"; same discussion possible here; highlighted text in page 285 explains biological mechanism

Structure and content of the book
---------------------------------
*open page 8*

- **Before chapter 1:** Some preceding text (Preface/Acknowledgements/Introduction)

- **Chapter 1:** Introduction, presentation of the book and the design principles (which are also denoted on page 470)

- **Chapters 2-4** discusses information processing from simple to complex organisms (starting with E. Coli, via more complicated bacterium Paramecium, C. Elegans, up to insects/mammals)

- **Chapters 5-7** discusses information processing from small to big scales

  - **Chapter 5:** Basic Shannon theory+general ideas of information processing with molecular circuits
  - **Chapter 6:** Protein circuits and how they implement computational primitives
  - **Chapter 7:** Whole neurons
  - **Chapter 10** would fit in this succession as well: discusses how analogue signals are recoded to pulsatile for transmission over distances bigger than 1 mm

- **Chapters 8-12:** Trace flow of optical information through a nervous system, from the environment to the brain, also brief excursions to other senses (TODO link to the example for auditory receptors)

- **Chapters 13, 14, 15** stand for themselves: wiring principles, learning, summary

- **After chapter 15:**

  - Page 470f: Brief recap of the design principles
  - Notes, References, Index

- End of each chapter generally gives motivation for the next one (maybe always - didn't check)

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

- *go to page 470*: This is a compact representation of the design principles
- highlight: *go to page 95*: Large monopolar cell optimizes tempo

- *go to page 8, talk about organization*

Noteworthy things about the book
--------------------------------

- Focus on vision
- Focus on small scale/early stages of information processing
- not that much about higher brain functions
- I liked: lots of numbers everywhere

Criticism:
----------
- my main criticism: Pro-brain bias
- *Go to page 14, look at first paragraph of introduction*

  - They talk about how the brain is "optimal", and the resulting functionality is much better than that of computers, everywhere
  - But I'd say it's optimal under the very severe constraints of computing with proteins in water, which yield lots of drawbacks:
    
    - everything works in milliseconds instead of nanoseconds
    - high noise
    - structures are not very reliable compared to silicon...
    - at least doesn't really use sophisticated algorithms (e.g. 
    - ... (see also rest of the talk, examples: vestibular)
  
  - Downstream, there are absolutely things humans can't do as well as computers:
    
    - quickly remembering lots of data
    - multiplying numbers
    - estimating a distance or time/staying in the middle of the lane...
  
  - So computing with proteins in water is like travelling to China on Pogo sticks: Very impressive if someone can make it, but not a superior alternative to a plane

  - Don't clearly distinguish between qualitative and quantitative evidence for optimization
  

computers being compared with are outdated

sometimes don't know where numbers come from

sometimes the physics seemed inaccurate/incorrect to me where I could check it

can still contain details, sometimes a bit verbose for my taste/too much rambling about life/philosophy?

joke: they could have "sent only what is needed"

a   
not clear if reducing spike rate is really the point, after all, we also want to do the computations some time, and maybe that's the point!

(often talks about maximizing information, but actual thing to maximize is value-of-information...)

Highlights
Seeing
~~~~~~
The vestibular/auditory story
~~~~~~~~~~~~~~~~~~~~
100: diameter/quantity of axons by sense, vestibular: hearing nerve
 (during talk: also link to auditory brain areas higher power density)

Highlighted notes
-----------------
pictures that belong together: 296/300: auditory vs vestibular cells
292/100: size of axons, vestibular is biggest
437 early LTP, 438 example for late LTP, see also STDP in internet!

Chapter 2: Information processing in simple organisms
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- **Page 39/Figure 2.2:** Mechanism by which E. coli processes information about glucose/lactose concentration in environment; only synthesizes lactase if no glucose, but lactase

- *go to page 41/figure 2.3*
- **Page 40:** 1 second memory of receptors for chemotaxis (biased random walk) to find food

- **Page 44-48/Figure 2.4:** look at Paramecium (larger bacterium):

  - **Page 44:** volume 300,000 times higher, moves 50 times faster than E. coli (1400 µm/sec)
  - Retracts when ramming an obstacle
  - Mechanism for this: Electrical signalling/Polarization of the membrane, ion pumps
  - Diffusion of signalling molecules would be too slow for this retraction too work quickly enough
  - Conversely, E. Coli is too small to implement such a mechanism

- **Page 46-64:** C. elegans, small worm with nervous system
  
  - *Go to page 48/figure 2.5*: This is the worm
  - **page 50 in text, but described by figure 2.5:** Body plays a role in computing cyclical movement, "embodied computation"
    
    - claims 'revolution' for robots, but haven't looked into extent to which it is important today
  
  - **Page 53/Figure 2.7:** Circuit for avoidance
  - **Page 56/Figure 2.8:** Social behaviour; this is controlled by 1 neuron/1 peptide, TODO I didn't really understand what the neuron does
  - **Page 57:** Learning.

    - "For example, NaCl (salt) normally attracts worms, but when a worm has been starved in the presence of salt for only 10 minutes, it later avoids salt."

    - done by chemical computing (e.g. strength of chemotaxis by odorant is learned depending on whether odorant is associated with food)

  - **Page 60f, subsection "Conserves synapses":** Design principle: to save energy per accuracy, send as slowly as possible

  - **Page 61, subsection "Minimizes wiring costs/Page 62, figure 2.9:** the prerogative "minimize wiring costs" predicts position of "90 % of neurons", but I don't know how "position" is defined exactly (spatially vs. topologically etc.)

  - **Page 62, lower part, subsection "Favors analogue over pulsatile":** C. Elegans doesn't need spiking neurons because it's not bigger than 1 mm, more expensive spiking neurons not necessary

Chapter 3: Larger brains
~~~~~~~~~~~~~~~~~~~~~~~~
- **Page 67f/Figure 3.1:** Similarities between mouse+fly brain

- **Following pages in text:** Lots of writing about how brain anticipates demands/changing circumstances in body and world and acts upon it

- **Page 76, figure 3.5; also page 77, figure 3.6 - calculated in page 76f, subsection "A neuron's information capacity":** Sets up terms of trade for spiking neurons: bits/spike, ATP/spike, bits/ATP.
  
  - Maybe most important figures in the whole book
  - Referred to over and over again in the book to explain why something is set up in a certain way
  - Axon diameter proportional to average spike rate
  - Axon volume rises as spike rate^2
  - **Explanation in page 79:** This is due to constant energy per spike, constant mitochondrial volume
  - I didn't really understand "measured bits per spike" in figure 3.5, lower. Did they look at an optimal compression scheme? Is this even possible?
  - Design principles inspired by this:
  
    - Send only what is needed
    - Send at the lowest acceptable rate
    - Minimize wire, i.e. axons/dendrites (this refers to volume, not only length). Chapter 13 is an entire chapter on efficient wiring!
 
- **Writing page 83** anabolism (being asleep) vs catabolism (being awake)

- Wired vs. wireless communication:

  - **Page 85/Figure 4.1:** Brain part "SCN", "suprachiasmatic nucleus", has about 8.6k neurons in humans, includes "master clock" for whole body's sleep-wake cycle
  - **Page 91f/Figure 4.3:** Higher-level overview over communication between brain and body

- **Writing page 86:** Hypothalamus sends simple instructions, can be said to be driver of ultimate decision making
  
  - **Writing page 87:** Well-understood enough that a cat can be made to behave in particular ways by stimulating regions of Hypothalamus
  - Joke: ultimage decision-making comes from the hypothalamus and not the prefrontal cortex!
  - very fine fibers, slow signals, low energy consumption (still page 87)
  - **Compare page 121:** Analogue is central complex in insects, stimulating one neuron induces fighting behaviour as well etc.

- **Page 94/Figure 4.4:** Rat brain, TODO where is hippocampus?

- **Writing page 95:** pattern generators in spinal column demonstrates principle "What fires together, locates together" (part of "minimize wire")

- **Writing page 98:** Investment into certain senses/frequencies/wavelengths depends on important stimuli for animals

  - Example: Bat ultrasound works at up to 180 kHz - but I don't know how this is biologically possible or works

(fig 102: mormyrid has much bigger cerebellum because of high-frequency electrical signalling)

 also speech low frequency
 
101: structure of music is similar to universal structure of speech, but I didn't learn how exactly
 The Statistical Structure of Human Speech Sounds Predicts Musical Universals
https://www.jneurosci.org/content/23/18/7160
END NEXT CYCLE
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
that were thought, until recently, to be confined to monkeys, human, dolphin, and pigeon (Srinivasan, 2010; Menzel, 2012), but I don't know what this is

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

Chapter 7: Design of neurons
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- **Writing page 181:**

  - Mammalian brain transcribes 5,000 to 8,000 genes,
  - uses alternative splicing to produce 50,000 to 80,000 distinct proteins.

- **Writing page 182:**

  - Dendrites conduct passive electrical signals about 50-fold faster than chemical diffusion,
  - axons conduct active electrical signals at least 20-fold faster than dendrites.

- **Writing page 185:** Synaptic cleft width appears to optimally balance transmitter concentration at the postsynaptic receptors and electrical resistance

186 SNAREs (protein complexes) used in vesicle fusion

- **Writing page 186:** Chemical signal peaks within 600 microseconds, lasts <1.5 ms cooperativity -> steeper response curves->sharper timing

- **Writing page 188**

  - briefly talks about the design of vesicles
  - energy costs of building+processing 1 vesicle: 23k ATP presynaptic, ~10 times as much postsynaptic

- **Page 190/Figure 7.5:** receptor clusters much smaller for fast auditory cells didn't understand but why smaller not bigger?

- **Writing page 192/193:** various receptors and timescales

  - AMPA is fast
  - NMDA with glutamate unbinds on a timescale of 100 ms, works for coincidence detection
  - mGLuR is even slower (tens of seconds)
  
- **Writing page 197:** Dendrites complicate their design

- **Writing page 198:** Analogue dendrites, spiking axons, 198: tree may send spikes backwards for e.g. learning

- **Writing page 199:** spikes useful for long-distance, but analogue->pulse loses as much as 90% of information
initial segment: conversion analogue->spike

- **Writing page 200:** Microtubule: ferry cargo, finest axon are limited in smallness by having to contain one microtubule

- **Writing page 202:**  Dendrodendritic/axoaxonic synapses/gap junctions compute locally, save energy

- **Writing page 204f/Page 205, figure 7.12:** Strange synapses: starburst, polyaxonal amacrine (img 205)
206 glial cells: 70 % of mitochondria in optic nerves!, don't know what they need that energy for, img 207
208 glial can express transporter proteins

- **Writing pages 209ff:** Explain motivations for different neuron variants; example cerebellum/Purkinje cells

  - **Writing page 213:** Explain "spillover" to maintain S/N (signal/noise ratio)

Chapter 8: Photoreceptors
~~~~~~~~~~~~~~~~~~~~~~~~~
- **Page 221/Figure 8.1:** Channels in photoreceptors

  - close after photon in mammals,
  - open after photon in flies.

- TODO img 223 baboon in starlight photon capturing , img 233 baboon in daylight
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

page 284: exact degree of coupling appears to maximize total information from the array (Design of a Trichromatic Cone Array)

302: Could a cell then continue to improve its S/N by extending its dendrites
ever farther to collect more synapses? No. Spatial correlations decline expo-
nentially across natural scenes whereas S/N improves only as the square
root of added synapses.

don't like the lack of quantitative results, it's not made clear if something is qualitative or quantitative


60 % of human brain energy cost in restoring ions

