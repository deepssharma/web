---
abbrev: pad_chambers
layout: newbase
category: central
---
{% include layouts/find_detector_title.md abbrev=page.abbrev %}
# {{ title }}

### Detector Overview
A detailed description about PHENIX Pad Chambers (PC) can be found at the following links. The PCs consist of three layers of multiwire proportional chambers, with a cathode pad readout. They provide space points along the trajectory of charged particles to determine the polar angle &theta; , used to calculate the p<sub>z</sub> component of the momentum vector.
PC1 is essential for the 3D momentum determination by providing the z-coordinate at the exit of the DC. The DC and PC1 information are combined to determine the straight line trajectories outside the magnetic field. PC2 and PC3 are needed to resolve ambiguities in the outer detectors where about 30% of the particles striking the EMCal are produced by either secondary interaction or decays outside the aperture of DC and PC1.

##### Theses
/direct/phenix+WWW/talk/archive/theses/2002/Milov_Alexander-thesis.pdf

#### Variables and Accessors under PHCentralTrack Node
{% include layouts/variables.md rows=site.data.pc.vars %}