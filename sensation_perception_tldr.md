# Princeton PSY345/NEU325: Sensation & Perception
### A TL;DR by Perry Cate '19

Disclaimer: I created this as my own study tool. I made aggressive, opinionated
(hopefully reasonable) choices about what to include.

(That said, suggestions, issues, and pull requests are always welcome!)


## General Terms
 * **Perception**: Process for extracting info via the senses, forming internal
   representations of the world
 * **Percept**: How your brain represents something

## Philosophical stuff
 * **Epistemology**: Theory of knowledge. ("where's knowledge come from?")
    * **Psychological Nativism**: Mind creates ideas not from external sources
    * **Empiricism**: All knowledge comes from senses
      * Hobbes, Locke, Hume
      * Newborn is "blank slate" ("tabula rasa")
      * We believe this
 * **Metaphysics**: Theory of reality. ("What stuff is there in the world?")
    * **Dualism**: 2 kinds of stuff. Mind and matter.
      * Modern idea: little person inside our head that "percieves" what we see
    * **Monism**; Only one kind of stuff
      * All stuff is physical matter + energy (aka **materialism**)
        * Question is, how is conciousness a thing?
        * We believe this
      * Alternatively: Idealism (see below)
 * **Radical Skepticism**:
    * Rene Descartes (also fan of dualism)
    * Discard anything that can be doubted
    * Senses can be fooled (like The Matrix)
    * Only certain thing is that he exists. "I think, therefore I am" 

### Philosopy of mind
 * What's the relationship between the world and what's in our head?
    * **Naive Realism** (aka common sense realism)
       * We see the world perfectly as is
       * Wrong because illusions are a thing
    * **Idealism**
       * Only reality is our mind
       * No evidence in external world
       * Not testable or provable
    * **Representative Realism**: We percieve the world imperfectly through
      "sense data"
       * **Functionalism**: Understanding the function of sensory systems is
         all we need to "understand" them (thinking about algorithms)
       * We believe this

### Methods of Study (aka scientific approaches)
 * Ecological (phenomenological, naturalistic)
    * "Look at stuff, draw conclustions"
    * Gives better appreciation of evolutionary constraints, sensory behaviors
    * Lack of scientific rigor (stimulus control, self-report data)
 * Psychophysical
    * Carefully controlled lab stimuli
    * Carefully measured quantitative data
    * Very rigorous but stimuli different from what actually happens in nature
 * Neuropsysiological
    * Like psychophysics, but measuring neurological response to stuff
 * Modeling/Reverse Engineering
    * Use computers and robots to act like humans
    * Special models ("ideal observers") act as benchmarks


## Psychophysical Methods
 * Psychophysics = mind + matter
    * Founded by Gustav Fechner, father of experimental psychology
 * **Fechner's Law**: Sensation intensity is k\*log of stimulus intensity
 * **Weber's Law**: As stimulus increases, magnitude of change changes
   proportionately 
    * 1 lbs change in 20 lbs weight is as noticeable as .2 lbs change in 4 lbs
       weight
    * Derived from Fechner's Law
 * **Weber Fraction**: Ratio of change magnitude / stimulus magnitude
   required to detect change 
    * Is the same regardless of stimulus size
 * **Steven's Power Law**: `Sensation intensity = k * (magnitude of physical
   stimulus)^(constant that depends on stimulus)`
    * Prof thinks this is less important than Weber-Fechner law
 * **Just-Noticeable Difference** (aka JND): Smallest magnitude change that can
   be detected
 * Measures of internal mental state
    * Detection (yes/no)
       * **Psychometric Function**: Relates physical quantity to probability of
         detecting something
    * Discrimination (x bigger than y)
    * Estimation (report stimulus exactly)
 * **Signal detection theory**: Quantifies response of observer to
   presentation of a signal when noise present
    * (signal=relevant, noise=irrelevant)
    * ie, Measures how good an observer is at observing
    * _hit_: Stimulus presented, observer thinks it was
    * _miss_: Stimulus presented, observer thinks it wasn't
    * _false alarm_: Stimulus not presented, observer thinks it was
    * _correct rejection_: Stimulus not presented, observer thinks it wasn't
    * **Noise distribution**: Values arising when stimulus not present
    * **Signal distribution**: Values arising when signal + noise present
    * **Type I Error**: Rate of false alarms or false positives
    * **Type II Error**: Rate of misses or false negatives
    * **D-prime** aka d': measure of sensitivity of observer
       * Higher d' -> more accurate observer 
    * **Psychometric Function**: Probability of observer _thinking_ they
    recognize stimulus as function of stimulus intensity as function of
    stimulus intensity


## Basic Neuroscience Stuff
 * **Frontal Lobe**: Attention, planning, short term memory, motivation
 * **Parietal Lobe**: Spatial sense, navigation, touch
    * Above temporal, behind frontal
 * **Occipital Lobe**: Vision (contains V1)
    * In the back of cerebellum
 * **Temporal Lobe**: Visual Memory, language comprehension, emotion
   association
    * At the bottom of cerebellum
 * **Neurons**: Make up nervous system
    * Axons connect to dendrites
    * Polarized membrane 
    * Sends spikes of current as signal through synapses by releasing
      neurotransmitters


## Vision
 * **Light**: EM radiation within narrow energy range, is both a wave and
   a particle
 * Optics (lenses) in eye force light from a single point in space to hit a
   single spot on the retina
    * Lets us form an image back there
 * Pinhole Camera: Small hole lets light through to make an image
    * Smaller hole=fewer rays -> sharper but dimmer image
 * **Cornea**: "Window" into eyeball, has 2/3 of eye's refractive power
 * **Aqueous humor**: Fluid behind cornea
 * **Lens**: Can change focus
 * **Pupil**: Opening at center of iris, light enters here
 * **Vitreous humor**: Gel fluid fills main eye cavity
 * **Retina**: Membrane on back of eye the detects light, has rods+cones
 * **Accommodation**: Lens changes shape to alter refractive power
 * **Emmetropia** No refractive power, looking at something in the distance so
   requires little effor to focus
 * **Myopia** aka Near-sightedness:
    * Lens too thicc/powerful
    * Eye too long
    * Image focuses before reaching retina
 * **Hyperopia** aka far-sightedness:
    * Lens too thin/not enough accomodation
    * Eye too short
    * Image would focus behind retina
 * **Astigmatism**: Vision defect due to unequal curving of refractive surfaces
 * **Visual Angle**: Size object takes up on retina (in degrees)

### How The Retina Works
 1. **Transduction**: Conversion of energy from one form to another 
    * This is important
    * **Phototransduction**: light into electricity (in retina)
       * **Rods**: Respond in low light (_"scotopic"_), don't process color 
       * **Cones**: 3 kinds, respond in daylight (_"photopic"_), process color
       * Not evenly distributed - cones mostly in center
       * We have way more rods than cones (90M vs 4-5M)
       * Rods and cones contain disks with **opsins**
          * Proteins that change shape when light absorbed
          * Different opsins respond to different wavelengths
             * **Rhodopsin**: opsin in rods (get it?)
       * Any molecule that is photosensitive is a _photopigment_
       * Rods+cones transmit signal constantly, stop when absorbing light (aka
         dark current)
 2. Processing
    * Amplification of weak signals
    * Compression of image so info can be sent to brain 
       * Optic Nerve is a bottleneck
 * Retina Layers: _(back to front)_
    1. Photoreceptors - detect light
    2. Bipolar Cells - transmits light data from photoreceptors to ganglions
    3. Ganglion Cells - recieves visual info via bipolar cells and amacrins,
       sends info to brain
       * On-center, off-surround - Responds to light in center, dark outside
       * Off-center, on-surround - Responds to dark center, light outside
       * ^Both emphasize edges and outlines in vision
       * **Receptive Field**: "what makes a neuron fire"
          * Function neuron uses to add up inputs
          * `light level * center weight + light level * surround weight =
            spike`
       * Both ON and OFF ganglions have 2 types:
          * **Parvocellular**: "small", processes shape, color
          * **Magnocellular**: "big", processes motion
 * Weird thing: Light has to pass through a bunch of stuff to reach
   photoreceptors (unlike cephalopods)
 * **Luminance Adaptation**: Adapting to different light levels
    * Humans can adapt to 6 orders of magnitude light difference (!!!)
    * 2 Mechanisms:
       * Pupil dialation
          * Pupil gets bigger or smaller (2mm vs 8mm, 16x more light)
       * Photoreceptor pigment levels
          * More light -> photopigment gets "used up"
             * less available phtopigment=retina is less sensitive
    * Don't need to estimate light level, just need to see objects
       * Rely on _contrast_, differences in light
       * `C = difference in light level / overall light level`
       * Better for retina to send info about local differences in light

### Eye-Brain Things
 1. Signals go from eyes to brain through optic nerve
 2. Nerves cross at optic _chiasm_
 3. **Lateral Geniculate Nucleus (LGN)** (in the thalamus)
    * One on each side of brain
    * Represents vis. field
    * Has eye-specific layers
    * has M and P layers
    * **Ipsilateral**: Same side of body
    * **Contralateral**: Opposite side of body
    * Responds to one eye or the other, _never both_
 4. **Primary Visual Cortex (V1)** (aka Striate cortex)
    * Everything else: "pre-cortical"
    * First place in cortex where vis. info actually processed
    * Responds to _both eyes_
        * But neurons prefer one eye or the other (aka okular dominance)
    * Circular receptive fields (like Ganglions) replaced by stripe receptive
      fields
        * Respond to bars in specific orientations or moving lines
        * **Simple Cells**: Prefer light or dark bars
        * **Complex Cells**: Respond to light or dark
    * Vertical arrangements of neurons (aka columns)
        * Columns in cortex have same:
           * Preferred dominant eye
           * Preferred Orientation
        * **Hypercolumn**: 1mm block, has everything needed to see certain
          small part of world
           * Every possible orientation
           * Left and right eyes
 * **Acuity**: Finest Visual detail that can be registered
    * _Snelen E test_: uses grating of strokes on capital E.
    * Eye doctors: use letters to measure your distance/avg person's distance
      (20/20, etc.)
    * Vision scientists: visual angle of 1 cycle (light/dark pattern) of finest
      grating you can see
    * **Spacial Frequency**: # bars per unit length
    * **Fourier Decomposition**:
       * V1 breaks images into sum of sine waves
       * Strongest response from ganglion cells when peaks/troughs line up with
         on-center, off-surround (or vice versa)
 * **Topography**: Mapping of objects in space onto V1 
    * Is contralateral, so each field repped in opposite hemisphere
 * **Cortical Magnification**: V1 gives more attention to center of field
   (fovea)
    * Misnomer because magnification already happens in retina
 * **Adaptation**: Response diminishes to sustained stimulus
    * Can "knock-out" groups of neurons by activating strongly
    * Can adapt to spatial frequency

### Beyond V1: Object Vision
 * Identifying objects
 * No one knows how this works
 * **View-dependent model**: Only recognizes particular views of an object
   (house from the front, etc.)
    * Not enough neurons for every possible view
    * Doesn't work
 * **Middle Vision**: After basic features extracted, before object
   recognition
    * Edges and surfaces
    * Determines grouping of regions into objects
    * "Edge detection" (and Fourier Analysis) are FAILING theories of what V1
      does.  Sad!
    * **Illusory contour**: Contour percieved even though no edge present
    * **Structuralism**: Perception built up from "atoms" of sensation (color,
      orientation, etc.) - doesn't fit because of things like illusory contours
    * **Gestalt psychology**: Whole is greater than sum of parts
       * **Gestalt Grouping**: Set of rules for when elements in image appear
         to group together
          * Based on _similarity_ and _proximity_
          * _Good continuation_: Elements group if they're on the same contour
          * Dynamic grouping
             * _Common fate_: Elements group if moving in same direction
             * _Synchrony_: Elements group if changing at the same time
          * Ground assignment
             * _Surroundedness_: Surrounded region likely to be ground
             * _Size_: Smaller region likely to be figure
             * _Symmetry_: Symmetrical region likely figure
             * _Parallelism_: Regions with || contours likely figure
             * _Extremal Edges_: If edges are shaded such that they seem to
               recede, likely figure.
       * Accidental viewpoint: Regularty in visual image not present in real
         world
          * Visual System _doesn't_ accept interpretations that assume
            accidental viewpoints
          * Opposite (non-accidental viewpoint): Interpretation doesn't change
            if you move the camera a bit
 * Object recognition not entirely viewpoint invariant
    * Faces harder to recognize when inverted
    * The more something is rotated, the harder it is to recognize
 * Facts contstraining object recognition models:
    1. Visual processing happens in 2 streams (after V1)
       * What vs Where info
    2. Object recognition is _fast_
       * Suggests **Feed-forward process**
          * Computation carried out 1 step after another
          * No need for feedback from later stage
 * Object Recognition Models
    * **Pandemonium model**
       * Perceptual "committee" of "demons" (neurons)
       * Each level a different brain area
          * Decision demon, cognitive demons, feature demons
          * Each demon is a possible letter, edge, etc.
    * **Hierarchical "constructive" models**
       * Explicit structure of how parts are combined to form image as whole
       * Committees with specialized members

### Color Vision
 * Lack of color vision != black+white
 * Psychophysical property, not physical
 * **Spectral**: Referring to wavelength
 * **Illuminant**: Light source
 * **Power Spectrum**: Curve of energy at each frequency of light
    * Red things have high energy values at longer (red) wavelengths, etc.
 * **Absorbtion Spectrum**: Response (aka light absorbtion) of photoreceptor as
   function of wavelength
 * 3 Cone classes
    * _S_ - Short (blue)
    * _M_ - Medium (green)
    * _L_ - Long (Red)
 * **Univariance**: Infinite set of wavelength+intensity combinations can get
   same responce from S, M, and L cones
    * **Metamers**: Illuminants physically distinct, perceptually the same
    * This is how display LEDs work
 * **Color Space**: 3D space describing all color percepts
    * RGB: Outputs of Long, Medium, Short wavelengths
    * HSB: Hue, Saturation, and Brightness
 * **Newton's Spectrum**:
    * ROY G BIV
    * He thought 7 kinds of light -> 7 kinds of receptors
 * **Opponent color theory**:
    * Perception based on output of 3 channels
    * Each channel based on opponency between 2 colors
       * Some Ganglion Cells have fields with color opponency (instead of rod
         black vs white)
          * Red-Green (L-M) (L center, M surround)
          * Red-Green (M-L) (M center, L surround
          * Blue-Yellow (S-(M+L)) (S center, L and M surround)
 * **Afterimage** (aka negative): Image seen after stimulus removed
    * Opposite of original stimulus (complementary)
 * **Color Constancy**: Tendency of surface to appear same color despite wide
   range of illuminants
    * Keeps daylight vs candles, types of lightbulbs, etc. from changing color
      of surroundings too much
    * Caused "the dress" incident
       * From precept: white+black vs blue+gold depended on what time of day
         viewer thought it was
 * **Color mixing**
    * _Additive_: Mixing of lights
       * 2 lights arrive at eye -> effects are added
    * _subtractive_: Mixing of paints
       * 2 pigments mix, light shining on surface subtracted by both A and B,
         so only the difference is reflected
       * Alt. Example: Light through multiple filters
 * **Color blindness**
    * **Dichromat**: Can only see 2 colors
       * 3 types:
          * **Protanopia**: Absence of L-cones
          * **Deuteranopia**: Absence of M-cones (most common)
          * **Tritanopia**: Absence of S-cones (least common)
    * **Monochromat**: True color blindness, world is black and white
    * **Cone Monochromat**: Only have one cone type (true b/w)
    * **Rod Monochromat**: World is black/white AND impaired in bright light
 * **Light Sensitivity**
    * _Photopic_: Cones active, rods "saturated"
       * Sunlight, brihgt indoor lighting
    * _Scotopic_: Rod vision, too dim for cones
       * Moonlight, extremely dim indoor lighting
       * No colors because cones not active

### Space + Depth Perception
 * **Depth Perception**: How far away stuff is
    * Distance vs size is ambiguous
 * Having 2 eyes is nice
    * Binocular Summation: Pool 2x light
    * Better field of view
    * Compare images for depth perception
 * Monocular Depth Cue: Cue that works with just one eye
    * **Occlusion**: One object obstructs view of part of the other
    * **Metrical Depth Cue**: Gives quantitative info about 3D distance
       * e.g. relative sizes of objects that are really the same size
    * Shadows
    * Texture gradients
    * Height in plane (makes size+texture more influential as well)
    * Linear perspective
       * Parallel lines converging (perspective projection)
    * Motion Parallax
       * Nearby objects move by faster than far away objects
    * Accomodation blur (aka "depth from focus")
       * Something is blurry = in different depth plane from what eye is
         focusing on.
 * Binocular Depth Cue: Relies in info from both eyes
    * **Vergence Angle**: Angle between eyes (object is vertex)
    * **Binocular Disparity**: Difference between 2 retinal images
    * **Stereopsis**: Depth perception from binocular disparity info (3D
      movies)
       * Potential defects:
          * **Strabismus**: Eyes not aligned -> different images on fovea
          * **Stereoblindness**: Inability to use binocular disparity as depth
            cue
    * **Disparity**: Difference between points in L and R eye images
    * **Horopter**: Circle at points at 0 disparity (corresponding parts of 2
      retinas)
    * **Correspondence Problem**: Which points in left eye go to which points in
      right eye?
       * Happens with multiple identical looking objects
       * Brain has disparity-tuned neurons
          * **Panum's fusional area**: Only certain range of disparities that
            brain can fuse

### Motion Perception
 * Motion = Orientation in space-time
 * **Apparent Motion**: Motion percept from rapid display of stationary images
   in different locations
    * Like movies
    * Triggered by Reichardt detector
       * 2 neurons, receptive field spatially separated (different locations),
         one with a time delay
          * Triggered by something passing one neuron, then the other
    * **(motion) Correspondence Problem**: "Which points in frame 1 are the
      same objects in frame 2?"
       * Causes wheels in movies appearing to spin backwards
    * **Aperture problem**: When moving object viewed through aperture,
      direction is ambiguous
 * **Motion effereffect** (aka MAE but not the major): Illusion of motion after
   prolonged exposure to moving stimulus
    * Motion always _opposite_ direction of stimulus
    * aka "waterfall illusion" - stare at waterfall, afterwards things appear
      to move upwards
 * **Interocular transfer**: Transfer of effect (like adaptation) from one eye
   to other
    * MAE exhibits it
    * Happens because input from both eyes is combined in V1
 * Area MT: Medial Temporal (V5)
    * Detects motion
    * When stimulated with shock, monkeys percieved motion
 * Eye movements
    * Can also cause object motion, important to distinguish
    * **Comparator**: Compensates for eye movement in vision
       1. Recieves copy of order from motor system
       2. Subtracts _expected motion_
    * Types of movement
       * **Smooth pursuit**: Eyes smoothly follow moving target
       * **Saccade**: Rapid movement, changes fixation from one locatoin to
         another
          * Saccadic suppression: Visual sensitivity reduced during saccade
       * **Vergence**: 2 eyes move opposite directions (such as towards nose)
       * **Reflexive**: Involuntary


## Hearing
 * Sound caused by sine waves of pressure from vibrating things
 * Physical qualities of sound (and corresponding psychological properties)
    * **Frequency**: # times / second that pressure pattern repeats
       * **Pitch**: How high or low sound is
       * Measured in Hz: 1Hz=1 cycle/second
    * **Amplitude**: Magnitude of displacement of pressure waves
       * **Loudness**: Percieved intensity
       * Measured in Decibel (dB)
          * Ratio of sound pressure level (SPL) to "barely detectable" sound
          * 0dB = barely detectable
          * Each increment of +20dB = increase in SPL by 10x
             * +40dB -> SPL increases by 100
 * **Sine Wave**: Simplest kind of sound - pressure/time is sine function
    * **Period**: Time for 1 cycle of repeating wave (frequency = 1 / period)
    * **Phase**: Relative position of 2+ sine waves
       * 360 degrees of phase in 1 period
    * Unnatural kind of sound though
       * Complex, natural sounds = sum of many sine waves
    * **Fourier analysis**: Can be used to divide any sound into sum of sine
      waves
    * **Fourier spectrum**: Shows amplitude for each fequency present in a
      sound

### The Auditory System
 * Outer Ear: Collects, transforms sound
    * **Pinnae** First collects sound, funnels into **ear canal**.
    * Length, shape of canal enhances certain frequencies
 * Middle Ear: 3 bones, amplifies sound
    * **Tympanic membrane** (aka eardrum): border between outer and middle ear,
      large surface area pushes on ossicles to make sound louder
    * **Ossicles**: Smallest bones in body, hinged joints act as levers,
      amplify sound
       * **Malleus**: recieves vibrations from eardrum
       * **Incus**: In the middle
       * **Stapes**: Connects incus to oval window of cochlea
    * **Oval Window**: Border between middle and inner ear
    * Tiny muscles tighten to reduce amplification of loud sounds
       * 200ms delay, not fast enough to protect against gunshots etc
 * Inner Ear: Transduces sound (mechanical energy to neural responses)
    * **Cochlea**: Spiral structure filled with fluids
       * **Place code**: Tuning of different parts of cochlea to different
         frequencies
       * Breaks down sound by frequency
       * Transduction (mechanical -> neural)
       * 3 canals (in order reached by sound)
          * **Vestibular canal**: Extends from oval window at base of cochlea
            to _helicotrema_ at apex
          * **Tympanic canal**: From round window at base to helicotrema at
            apex
          * **Helicotrema**: Cochlear apex
          * **Basilar membrane**: Separates middle and tympanic canals
          * **Middle canal**: Between tympanic and vestibular
       * **Organ of Corti**: Hairs+dendrite nerves on basilar membrane of
         cochlea
          * **Translate basilar membrane movements into neural signals
          * Hair cells in 4 rows
          * **Stereocillia**: Hairlike extensions on tips of hair cells,
            trigger neurotransmitters when flexed
             * Connects to neighbor by filament called **tip link**
          * Moved by **Tectorial membrane**, which extends into middle canal
            * Floats above inner hair cells, touching outer hair cells
            * **Inner hair cells**: Conveys almost all sound info to brain
            * **Outer hair cells**: Conveys info _from_ brain
               * Elaborate feedback system
               * Amplifies sounds by increasing deflections of basilar membrane
    * Mechanical energy flow:
       1. Vibrations cause stapes to push/pull oval window
       1. Go through vestibular canal
       2. Pressure transmitted through helicotrema
       3. Back to cochlear base through tympanic canal
       4. Absorbed by round window
    * Auditory transduction:
       1. Standing wave in basilar membrane
       2. Movement of organ of corti + tectoral membrane (amplified by outer
          hair cells)
       3. Inner hair cell displacement -> tip links -> channel opening
 * **Frequency selectivity**: Clearest when sounds are very faint
 * Auditory nerve: Fibers stimulated by inner hair cells
 * Info flow:
    1. **Cochlear nucleus**: First brain stem nucleus auditory nerves synapse to
    2. **Superior olive**: Brainstem region where inputs from both ears converge
    3. **Inferior colliculus**: Midbrain nucleus
    4. **Medial geniculate nucleus** (aka MGN): relays auditory signals to
      cortex
    5. **Primary auditory cortex** (aka A1): First cortical area for processing
      sound
    6. **Belt & parabelt areas**: Beyond A1, neurons respond to more complex
       sound characteristics
    * Side note: Auditory system has lots of processing _before_ A1, Visual
      system has lots of processing _after_ V1
  * **Tonotopic organization**: Neurons ordered (spatially) in order of
    preferred frequency
     * Starts in cochlea
     * Maintained all through to A1
  * **Phase locking**: Neuron firing locked to period of sound wave
     * Example of **temporal code**
  * **Psychoacoustics**: Study of the psychological correlates to physical
    dimensions of acoustics
  * **Masking**: Using second sound to make detection of another sound hard
  * **Critical Bandwidth**: Range of frequencies conveyed within a channel in
    auditory system
     * How to measure bandwidth of frequency channels
        1. Present tone on top of noise background
        2. Start with narrow band of noise
        3. Increase noise bandwidth, measure threshold for tone detection
        4. Keep increasing noise bandwidth until it doesn't cause decrease in
           sensitivity (increase in threshold)

### Detecting sound location
 * 3 planes:
    * Horizontal (aka azimuth)
    * Vertical (aka elevation)
    * Distance
 * Timing differences
    * **Interaural time differences** (aka ITD): Difference in time between
      sound arriving at one ear vs the other
    * **Medial superior olive** (MSO): Place where ITDs are processed
    * Good for low frequencies
 * Loudness differences
    * **Interaural loudness differences** (aka ILD): Difference in level
      (intensity) between sound arriving at one ear vs the other
    * For frequencies >1000Hz, head blocks some energy
    * Correlates with angle of source, not as reliable as ITDs
    * **Lateral superior olive**: Station in brain stem where both ears
      detect ILDs
    * Good for high frequencies
 * **Cone of confusion**: Region of space where all sounds produce same ITDs
   and ILDs
 * **Head-related transfer function**: (HRTF) How pinnae, ear canals, etc
   change intensities of different frequencies
    * Unique to individual
    * Helps locate sounds
    * Hofman 1998: Inserted molds into pinnae, screwed up sound localization
 * **Auditory distance perception**:
    * **Loudness**: Decreases with distance (inverse square law)
    * **Spectral composition**: Higher frequencies lose energy faster than loer
      frequencies
       * Only works for long distances

### Properties of Complex Sounds
 * **Harmonics**: Objects vibrate and "resonant frequencies"
    * Most die down, some persist
    * Auditory system sensitive to harmonics (eg guitar string, voices)
    * If fundamental (strongest, original) of harmonic removed, listeners still
      hear its pitch
       * Only 3 harmonics needed for this
 * **Timbre**: Psychological sensation, listener can use to judge 2 sounds with
   same loudness and pitch are dissimilar
    * Harmonics and other high frequencies
    * Perception depends on context
 * **Source segregation**: Processing auditory scene of multiple sounds into
   separate sources
    * "Cocktail party effect": Can "select" conversation even when many are
      present
       * Same voice speaking to both ears -> very difficult
       * Same voice to separate ears -> easy
       * However, subjects didn't/couldn't:
          * identify single phrase from non-attended ear
          * identify language
          * identify backwards recording
       * DID notice change from male to female speaker
       * Implies we can separate sounds streams, but can't attend to multiple
         at same time
 * Principle of _good continuation_: Can hear sound despite interruptions
   - brain "smoothes out" encoded signals
    * Adding noise can make speech easier to understand than silence in gaps

### Bayesian Perception
 * Based on probabilities
 * Perception is _ill-posed_ problem
    * No unique solution (What's going on is ambiguous)
    * Infinite 3D objects can make the same 2D retinal image
    * Need more info to make it _well-posed_
       * Probability based on past results helps
 * **Bayes' rule**: `P(B | A)` is proportional to `P(A | B) * P(B)`
    * Applies to perception:
       * _Posterior_: Resulting beliefs about the world -
         P(What's in the world | Sense data)
       * _Likelihood_: Determined by laws of physics, many are possible -
         P(Sense Data | What's in the world)
       * _Prior_: Past experience of what's in the world - P(world)
       * Posterior = Likelihood * Prior
 * Past experience causes our brain to assume things
    * Example: Hollow Face illusion - brains are well trained to assume objects
      (like faces) are convex


### Olfaction
 * Chemical Senses
    * **Olfaction**: Smell
    * **Gustation**: Taste
 * **Odor**: Smell sensation of a particular quality
 * **Odorants**: Chemical compounds (not all compounds is odorant)
 * Our sense of smell not as good as other animals (dogs have 100x more
   receptors)
 * Bi-nostril sniffing gives us left-right info
    * Airflow better on one side than the other due to slight swelling
       * Switches off several times per hour
       * Odorants sorb accross mucous at different rates
          * "High-sorbtion": Small response with low airflow, large with high
            airflow
          * "Low-sorbtion": Large response with low airflow, small with high
            airflow
          * Implication: Odorants smell different in each nostril!

 * **Olfactory cleft**: Space at back of nose air flows into
 * **Olfactory epithelium**: Mucous that detects odorants, is inside olf. cleft
    * "Retina of the nose"
    * 3 cell types
       * **Supporting Cells**: Metabolic + physical support to OSNs
       * **Basal cells**: Precursors to OSNs
       * **Olfactory sensory neurons** (aka OSNs): Main cell type in olfactory
         epithelium
          * Only sensory receptors that make direct contact with physical
            stimulus
          * Slow response, thinnest and slowest axons in body
    * **Cilia**: Hairlike protrusions on OSN dendrites
       * Have receptors for odorant molecules
       * Do signal transduction
    * **Olfactory receptor**: Region on cilia where molecules bind
       * 7 or 8 molecules binding required to initiate action
 * **Cribiform plate**: Bony structure, separates nose from brain
    * OSN axons pass through tiny holes
 * **Mitral cells**: Main output neurons from olfactory bulb
 * **Glomeruli**: Conglomerates containing incoming axons of OSNs
    * Each OSN goes to 2 glomeruli
 * **Olfactory bulb**: Bluebberry-sized extension of brain above the nose
    * First processes olfactory info
    * 2 bulbs, one for each nostril
 * **Primary olfactory cortex**: First cortical area to process olfactory info
 * **Limbic system**: Involved in emotion + memory
    * Olfaction (uniquely) is _directly_ connected
    * Many subsiquent conncetions to midbrain
 * Olfaction doesn't have topography like other senses
 * Genetic stuff
    * All mamals have same 1000 genes for smell detection
    * **Pseudogenes**: Smell gene is non-functional
    * Dogs+Mice: ~20% pseudogenes
    * Humans: ~60-70% pseudogenes
    * Individuals have different numbers of pseudogenes, causes differences in
      smell sensitivity
 * Perception Theories
    * **Vibration theory** (defunct): Every smell has vibration frequency,
      molecules with same frequency smell the same
    * **Shape-pattern theory** (dominant): Odorants binding in epithelium
      causes specific neuron firing pattern
 * **Stereoisomers**: Molecules are mirror image rotations
    * Contain the same atoms
    * Smell completely different
    * Can't be explained by vibration theory
 * **Anosmia**: Inability to smell
    * **Specific anosmia**: Inability to smell a specific compound
       * 50% has anosmia to androstenone
       * _Can_ be explained by shape-pattern theory
 * Patterns are important
    * Look at pattern of activity across many receptor types
    * Intensity of odorant changes which receptors are activiated
    * Time order matters as well
 * **Odor hedonics**: "liking" of odor perception
    * Scales of _pleasantness_, _familiarity_, _intensity_
    * Familiarity and intensity:
       * Pleasantness: duh
       * Familiarity: Smells like odors we've smelled before
       * Intensity: More complicated
    * Nature vs Nurture
       * Consensus; Nurture
       * Infants not annoyed by sweat, feces, doesn't discriminate banana from
         rotten food
       * Americans like wintergreen, english hate it
       * US Army tried to make stinkbomb, couldn't find universally disgusting
       * Japanese hate cheese, Americans dislike Natto
       * Evolution argument: _Generalists_ (us and roaches) don't need smell
         aversion to predators
       * **Learned taste aversion**: Avoidance of flavor after it makes you ill
          * From smell, not taste
 * Memory
    * Memories triggered by odors more distinctive
    * _Not_ more accurate


## Taste
 * **Taste**: Sensations from receptors on tongue and roof of mouth
 * **Flavor**: Combination of taste and smell
 * **Retronasal olfactory sensatoin**: Sensation of odor when eating
    * Chewing/swallowing force odorant in mouth behind nose palate
    * Percieved as originating in mouth
    * Brain blocks olfactory contribution to taste unless taste receptors also
      report something
 * Tongue is "retina" of gustation
    * **Papillae**: bumps on tongue
       * **Fungiform**: Taste buds within
       * **Filliform**: In front of tongue, no taste, spoon-like in cats
       * Contian _taste buds_ and _taste receptor cells_
    * **Microvilli**: Projections on tips of taste buds, extend into taste pore
       * Sites that bind to taste substances
       * Not hairs, are extensions of cell membrane
 * \# of taste buds varies a lot (4x difference)
    * High variation unique among senses
 * _Supertaster_: High density of Fungiform papillae
    * Most intense taste sensations
 * **Tastant**: Any stimulus that can be tasted
 * 4 tastes:
    * Ions enter cell
       * Salty
          * Made of charged particles (cation, anion)
          * Sensitivity varies (low salt diet -> more sensitive to salt)
       * Sour
          * Acidic substances
          * High concentrations can damage you
    * Tastant binds to cell receptor
       * Sweet
          * From sugars (*crose)
          * Single receptor for all sweet perception
       * Bitter
          * Quinine is typical substances
          * Often poisonous
    * Each taste bud can detect multiple tastants (what you learned in middle
      school is wrong)
    * Umami: 5th taste?
       * From MSG
       * Not super perceptable
       * Not everyone reacts in same way
       * May bind to gut instead of tongue
 * Unlike smell, infants have innate preference for certain tastes
    * Could be evolutionary - need salt+sugar, sour+bitter can harm
 * Spiciness: Nothing in nature likes it
    * Detected by pain receptors as capsacin burns mouth, not taste
