Implementing your experiment
============================

Purpose
-------

This section provides information to help you out designing your MEG experiment.
What is meant by experiment, is the stimuli involving usually visual and auditory or other perception-type stimulus.
The experiment defines the timing of display of the stimuli, tracks responses from the participants and controls the different settings related
to the content being presented to the participant.
This section also provides the requirements that should be met to run your experiment in the NYUAD MEG Lab.

There are three tools primarily used for designing the experiment

- Psychotoolbox
- Presentation
- Psychopy


Definning the hardware needs for your experiment
------------------------------------------------

Depending on your study you might need different require different hardware, the following use cases can be identified:

- Show visual stimuli to participants for a certain amount of time
- Allow participant to send their input via buttons
- Get eyetracking information from the eyetracker device
- Provide audio to the user
- Record audio from the user's voice

Hardware involved in experiment
-------------------------------

- Propixx
- Datapixx
- Eyetracker

Datapixx pixel mode `Pixel mode <https://docs.vpixx.com/vocal/defining-triggers-using-pixel-mode>`_.

The eyetracker sends three different signals to the MEG/EEG channels:

- The X-coordinates of the eye as function of time
- The Y-coordinates of the eye as function of time
- The Area of the pupil of the eye as function of time


Files produced by the experiment design
---------------------------------------


- An experiment in PsychToolBox is a `.m` MATLAB script.
- Presentation provides a `.exp` file, an experiment file.
- PsychoPy is a `.py` experiment file.

If using python library PsychoPy:

* Open the file with .psyexp extension
* you can run from within the psycopy builder the experiment file with .psyexp extension c




