# README

## TODO

- reversed phase images are fmaps and not func
- define trial types levels in the task.json
- missing participants.tsv

## Missing data

- Wave files in code folder can be found in the source repo.

## Overview

- Project name: CAUSAL ROLE OF HMT+/V5 IN VISUAL AND AUDITORY MOTION PROCESSING
- Year: 2021

- [ ] Brief overview of the tasks in the experiment

A paragraph giving an overview of the experiment. This should include the goals
or purpose and a discussion about how the experiment tries to achieve these
goals.

- Description of the contents of the dataset

        Summary:                 Available Tasks:          Available Modalities:
        386 Files, 4.11GB        auditory Localizer        MRI
        17 - Subjects            visual Localizer
        3 - Sessions

<!-- missing from bids validator description:
behavioral data
-->

- [ ] Independent variables

A brief discussion of condition variables (sometimes called contrasts or
independent variables) that were varied across the experiment.

- [ ] Dependent variables

A brief discussion of the response variables (sometimes called the dependent
variables) that were measured and or calculated to assess the effects of varying
the condition variables. This might also include questionnaires administered to
assess behavioral aspects of the experiment.

- [ ] Control variables

A brief discussion of the control variables --- that is what aspects were
explicitly controlled in this experiment. The control variables might include
subject pool, environmental conditions, set up, or other things that were
explicitly controlled.

- [ ] Quality assessment of the data

Provide a short summary of the quality of the data ideally with descriptive
statistics if relevant and with a link to more comprehensive description (like
with MRIQC) if possible.

## Methods

### Subjects

- [ ] Information about the recruitment procedure
- [ ] Subject inclusion criteria (if relevant)
- [ ] Subject exclusion criteria (if relevant)

## Experimental design

The experiment was divided into a 30-min long fMRI session and two 1-hour long
TMS sessions. During the fMRI session an anatomical scan and two functional
localisers were run. The purpose of the visual motion localiser was to identify
subjects’ individual peak hMT+/V5 coordinates. This allowed individual hMT+/V5
to be targeted accurately in the subsequent TMS sessions with the help of
neuronavigation. An auditory motion localiser was run to determine in which of
the subjects auditory motion activity could be located not only within the PT
but also within hMT+/V5. Real stimulation was applied during one TMS session,
and sham stimulation during the other. Subjects were blind to the different
stimulation conditions. The TMS session order was counterbalanced across
subjects. An online application of rTMS, i.e. during task performance, was
decided against, due to the confounding auditory co-stimulation effects that the
loud TMS-coil clicks unavoidably induce. Employment of a single-pulse protocol
was also disregarded, given the large number of trials that would have been
required to cover the potential temporal processing window. After the fMRI
session, subjects familiarised themselves with all four visual and auditory
motion and non-motion (static) tasks and completed at least one run of each. The
goal was to catch any task comprehension errors and substantial initial learning
effects in this practise phase in order to ensure stable performance during both
subsequent TMS sessions. For the same purpose, subjects also performed 30
reminder-trials of each task at the start of each TMS session. Following TMS,
subjects performed two adaptive staircases of each of the four tasks, the data
of which was compared across sessions.

## Functional Localisers

Stimuli Subjects attended a ~25min-long MRI session for two purposes. Firstly,
an fMRI visual motion localiser was run. Given the high variability in HMT+/V5
coordinates across individuals it was important to obtain each subject’s
individual hMT+/V5 coordinates in order to increase the TMS targeting accuracy
(Dumoulin et al., 2000; Orban et al., 2004). Secondly, an auditory motion
localiser was run to determine whether subjects also show increased activity in
MT+/V5 in response to auditory motion stimuli, and if so, how far the activity
peak was from the subjects’ visual motion peak. The presence/absence, or extent,
of such activity was hypothesised to potentially mediate a TMS effect on the
auditory motion task. The fMRI session was therefore divided into a ~5min
anatomical T1-weighted scan, followed by a ~5min visual localiser and a ~10min
auditory localiser. For each localiser, moving and static stimuli were presented
in alternating blocks, so that the BOLD activity during the motion task could be
contrasted with the activity during the static control task of the same
modality. Per block, a total of 12 1.2s-long events were presented. Events were
separated by ISIs of 0.1s. In the visual motion localiser the whole hMT+/V5
complex was defined, which includes both MT and MST (middle (superior) temporal)
areas, as visual stimuli were presented at fixation (Huk et al., 2002). Through
a mirror mounted on the MRI coil subjects viewed full-screen random dot
kinematograms (RDKs) with white dots (diameter = 0.2°) presented on a black
screen (32-inch NordicNeuroLab LCD Monitor) behind the scanner (distance = 170
cm). On average one dot was present per visual angle square. In the motion
condition, dots moved right- or leftward at a speed of 15°/s with 100% motion
coherence, whilst they remained static at random locations on screen during the
static condition. Dots had a lifetime of 400 ms to ensure global and not local
motion perception was induced. The 2 motion directions were repeated 6 times per
motion block in a randomised order that was counterbalanced across blocks. There
was a total of 6 blocks, which were separated by an interval of 8 s to allow the
BOLD signal to return to baseline. The localiser began and ended with 5 s and 14
s respectively of black screen. To ensure participants paid visual attention and
fixated on the central fixation cross, they were asked to press an
MRI-compatible button with the index finger of their dominant hand whenever the
fixation cross briefly (150 ms) changed colour from white to red. These targets
were presented on average once per block, at a random timepoint within the
block. In the auditory motion localiser the same static, right- and left-ward
moving pink noise sounds as in Rezk et al (2020) were presented. These stimuli
were recordings from binaural in-ear microphones attached to a dummy sat in a
semi-anechoic room in front of a semi- circular sound-bar through which static,
right- or a leftward travelling sounds were presented at 65 dB. To induce
realistic motion perception, the 1.2 s long stimuli were divided into 31 equal
segments which were played sequentially through the 31 individual speakers of
the sound bar. Motion speed was 2 m/s. These stimuli are convolved with the
dummy’s head- related transfer function so that they do not feel as if they are
“passing through” one’s head, as artificially created stimuli would. Stationary
sounds were recorded from the central speaker. The localiser started with 5 s of
silence and ended with another 12 s of silence. Each motion direction was
presented 6 times per block, and there were 13 blocks in total, which were
separated from one another by an interval of 6 s. In addition to pressing the
button when the fixation cross changed colour, subjects were also instructed to
press the same button whenever they heard an easily detectable shorter/quicker
sound, to ensure they were attending to the auditory stimuli. These target
sounds were recorded in the same setup, but had a duration of 0.6 s, which
resulted in a faster speed of 4°/s for the moving stimuli. Target appearance was
randomised as in the visual localiser. Prior to scanning, subjects were briefly
familiarised with both tasks outside of the scanner. Individual loudness and
balance were set, and adjusted again in the scanner if necessary due to the loud
scanner noise. Sound was delivered through MRI-compatible in-ear headphones that
simultaneously pose as earplugs for reduction of scanner noise (Sensimetrics S14
insert earphones) and hearing protection. Ear defenders were worn on top for
additional safety. The MATLAB-task scripts were run on an external laptop
(MacBook Pro 2018).

## TMS Protocol

Using a butterfly-coil (MagVenture MCF-B65) one standard train of 600 biphasic
pulses of cTBS (i.e. 41s) was delivered to hMT+/V5 in each hemisphere in turn at
an intensity of 100% of subjects hemisphere-specific individual active motor
threshold (AMT) (stimulator: MagPro X100). The stimulation intensity was matched
to the one used in a previous study, which applied cTBS to hMT+/V5 and
successfully affected visual motion performance (Cai et al., 2014). The AMT for
each hemisphere was determined at the start of each TMS session to account for
interhemispheric differences and daily fluctuations. It was defined as the
lowest stimulation intensity at which a single TMS pulse over the subjects’
motor hot spot evoked a small visible response in the contralateral first dorsal
interosseous (FDI) muscle in 5 out of 10 consecutive trials when the subject
activated the FDI muscles. In the given subject pool the AMT lay at an average
intensity of 42% (SD = 6%, range = [32% 58%]) of the maximum stimulator output
(MSO). The order in which the hemispheres were stimulated was counterbalanced
across subjects. Frameless, ultrasound-based, stereotactic neuronavigation was
performed using the Localite TMS Navigator system and the Visor2 software with
the goal of increasing the TMS targeting accuracy of area hMT+/V5. Before the
subject’s first TMS session, their individual anatomical MRI scan was loaded
into the software, normalised and co-registered with the individual right and
left hemispheric target coordinates in MNI space. At the start of the TMS
sessions, the subject’s head shape was co-registered with their anatomical image
following standard procedures. Ensuing the application of this cTBS protocol, at
least 30 min of after-effects (up to 60 min) were expected, during which
subjects performed the same four experimental tasks per session lasting a total
of ~25 min (Kaderali et al., 2015). To control for auditory co- stimulation
effects, that typically accompany TMS, and for potential expectation biases/
placebo effects, a 90°-tilt sham stimulation condition was used as a
within-subjects control condition during one of the two TMS sessions. The same
neuronavigated sequential bilateral protocol was applied as during real
stimulation, but with the coil angled away from the subject’s scalp, directing
the magnetic field into space (Duecker & Sack, 2015).

## Behavioural Tasks and Stimuli

Besides the main task of interest, auditory motion processing, three control
tasks were performed, namely static auditory processing, visual motion and
static visual processing. The visual motion task assessed the effectiveness of
the cTBS protocol in altering functional processing in hMT+/V5, demonstrated by
its known function in visual motion processing. Both static control tasks
assessed the selectivity of hMT+/V5’s involvement in motion processing, as
compared to more general sensory processing functions. A binary forced choice
paradigm was implemented for each trial, meaning that subjects had to press one
of two keys with their right hand to enter their response following the
presentation of a 1s-long stimulus. Per task, one parameter was adapted to
modify task difficulty and therewith subjects’ performance level. This way,
subjects’ individual 75% accuracy threshold could be obtained for each task.
Using a Bayesian adaptation algorithm QUEST (QUaternion ESTimator toolbox) from
Psychtoolbox3 (Brainard, 1997) implemented in MATLAB (Mathworks, MA) the
adaptive parameter of each task was adjusted in a staircase design. Each correct
response led to an increase in the next trial’s task difficulty and each mistake
led to an easier subsequent trial (see Appendix A Figure A1 for a 60-trial
example staircase). This procedure allowed individual performance differences to
be accounted for and avoided ceiling or floor effects when comparing subjects
performance under real compared to sham stimulation. The task difficulty of the
first trial was always set to a value at 50% +/-3 SD task difficulty [100% being
the easiest, 0% the most difficult] based on the respective adapted parameter’s
range of values, so that the initial set of easy, uninformative trials (usually
with 100% accuracy) was skipped, and the algorithm could reliably find the
individual threshold for all four tasks within the limited time window of TMS
after-effects. If a mistake was made in the first four trials, e.g. due to an
accidentally reversed key assignment, the staircase was restarted, so as not to
set the adaptation algorithm off in the wrong direction. Based on a behavioural
pilot, which was run on six participants to determine the optimal stimulus
parameters and timings, the average threshold for the auditory motion task lay
at 17% (SD = 6%), at 14% (SD = 4%) for the auditory static task, at 14% (SD =
5%) for visual motion, and at 14% (SD = 5%) for the visual static task. The
following timings were found to compromise best between maximising the number of
trials that could be recorded in 30 min and not imposing time pressure on the
subjects. Previous studies using similar motion paradigms presented stimuli for
durations between 50 ms and 1500 ms, mainly for 500 ms (Jia & Li, 2017; Rezk et
al., 2020; Sack et al., 2006; Zhang & Yang, 2014), and found that responses were
made within 400-800 ms (Sack et al., 2006). In this experiment, all stimuli were
presented for a duration of 1000 ms, and subjects had up to 1500 ms of time to
enter their response. An inter-trial interval of 500 ms followed each response,
so that each trial amounted to maximally 3s duration (Figure 1a). Based on
previous research using the Bayesian algorithm for the adaptive staircase
procedure with similar stimuli, performance was expected to stabilise after ~30
trials at the latest (Rezk et al., 2020). Based on the behavioural pilot
performed on the stimuli used in this study, most staircases already plateaued
by trial 20. The estimated threshold, i.e. performance accuracy, was reasonably
stable for the remaining trials, usually fluctuating only slightly around the
final estimate (see example staircase in Appendix A Figure A1). To ensure stable
individual thresholds could be extracted from a sufficient number of trials at
near threshold difficulty each staircase consisted of 60 trials. Depending on
subjects’ reaction times each staircase therefore lasted up to 3 min. Within the
assumed 30min-window of cTBS after-effects, two staircases (2 x 60 = 180 trials)
of each task could be run (Figure 1b). The four tasks (i.e. 8 staircases total)
were blocked by sensory modality to minimise time lost transitioning between the
visual and auditory set-ups, i.e. putting on or removing the blindfold and
headphones. Within each visual and auditory modality block, the motion and
static tasks were performed in an ABBA order. The sensory modality block order
and the assignment of motion/static tasks to the ABBA scheme within each block
were counterbalanced across subjects. 1.5 min of transitioning and break time
were available between the two modality blocks. The four staircases within each
sensory modality block were separated by breaks of up to 30 s, depending on the
subjects’ preferences. Visual Tasks For both visual tasks, a distance of 60 cm
was maintained from the monitor (1680x1050 pixels). Subjects placed their heads
on a chin rest and were instructed to fixate on a green central fixation cross
that remained on screen throughout the run. Rezk and colleagues (2020)
previously included eye-tracking to control for eye movements, and found no
effect of auditory motion direction on eye-movements, nor a significant
difference in eye movement profiles across visual and auditory motion and static
task conditions. Random dot kinematograms (RDKs) with 300 randomly located white
dots per frame (0.1° diameter) were displayed on a grey screen within a circular
aperture (11° diameter) in the centre of the screen. Each dot had a limited
lifetime of 200 ms to ensure global motion was perceived, i.e. requiring the
integration of multiple local signals, and that the motion direction could not
be determined via local motion processing, e.g. by tracking a single dot (Bex et
al., 2003). During the motion task, all dots moved randomly at 6°/s, with a
subset of stimuli moving in the same rightward or leftward direction. Subjects
indicated whether global motion direction was right- or leftwards. For the
purpose of the adaptive staircase, task difficulty was increased by
incrementally reducing the motion coherence [%], resulting in a lower QUEST
threshold. These parameters were optimised based on the insights of previous
visual motion studies using RDKs (Sack et al., 2006; Cai et al., 2014; Kaderali
et al., 2015; Rezk et al., 2020). For the static visual task, all dots in the
aperture remained stationary and were either black or white. On each trial,
participants determined the majority colour of the dots. The colour ratio was
made incrementally more equal across staircase trials (i.e. lower QUEST
threshold) to increase task difficulty, so that individual thresholds for
non-motion visual processing could be determined. Auditory Tasks For both
auditory tasks subjects wore a blindfold and on-ear headphones (Sennheiser HD-
201), through which the auditory stimuli were delivered, and were instructed to
minimise eye movements behind closed lids. For the motion task, the same right-
and leftward moving pink-noise stimuli as in the auditory localiser were used as
the two baseline stimuli. Pink noise was used as it sounds more gentle than
white noise. Unlike real-world sounds, these are less likely to induce visual
imagery, which could pose as a confound when drawing conclusions with regard to
hMT+/V5’s role in auditory motion processing. Subjects discriminated the
direction of motion as being either left- or rightward. For the staircase
procedure, task difficulty was increased by mixing the two moving sounds to
different extents, i.e. decreasing the signal-to-noise ratio. The larger, i.e.
more equal, this mixing ratio was, the more difficult it got to distinguish the
dominant motion direction from the increasing, seemingly stationary background
pink noise. The better subjects performed, the smaller was the difference
between the dominant and opposing direction within the motion stimuli they could
still reliably discriminate, i.e. the lower their QUEST threshold. For the
static control task, pink noise or pure tone stimuli to minimise the influence
of visual imagery could not be used, given that most human beings are not able
to discriminate absolute pitch. Neither temporally or pitch-changing stimuli nor
sounds presented in varying locations could be used for fear of involving areas
required for spatial orientation or motion processing. Instead, morphed stimuli
of clarinet and piano sounds were used, and subjects had to categorise the
stimulus presented on a trial as resembling more a sound as produced by a
clarinet or by a piano. The same tone was played by the clarinet and piano in
the original unmorphed sound stimuli. The morphed stimuli were created using the
language-morphing toolbox STRAIGHT (Speech Transformation and Representation
based on Adaptive Interpolation of weiGHTed spectrogram, (Kawahara, 2006;
Kawahara & Matsui, 2003; Kawahara et al., 2013) in MATLAB (Mathworks, MA) which
allows the pseudo-automatic merging of sounds. Sounds of 21 different morphing
ratios were created, those with incrementally more equal ratios being more
difficult sounds to categorise (resulting in lower QUEST thresholds).

### Apparatus

A summary of the equipment and environment setup for the experiment. For
example, was the experiment performed in a shielded room with the subject seated
in a fixed position.

### Initial setup

A summary of what setup was performed when a subject arrived.

### Task organization

How the tasks were organized for a session. This is particularly important
because BIDS datasets usually have task data separated into different files.)

- [ ] Was task order counter-balanced?
- [ ] What other activities were interspersed between tasks?
- [ ] In what order were the tasks and other activities performed?

### Task details

As much detail as possible about the task and the events that were recorded.

### Experimental location

Hopital Saint-Luc, Brussels, Belgium
