# An aural representation of a participant's electroencephalography (EEG) recording.

EEG data will be acquired from a low-cost, brain-computer interface developed by OpenBCI. This electroencephalography signal will then be represented as frequencies (versus power), and then used as an 'input gain' into sound generation software. The sound generation will be conducted using SuperCollider, using a package that allows [communication between OpenBCI hardware and SuperCollider software](https://github.com/khofstadter/OpenBCI-SuperCollider).

## Requirements
This project uses a Python-based environment. In particular, it leans on the BrainFlow and MNE software packages for processing of data. For more information relating to these details check out the following, which is foundational to this project: [Acquiring & processing an electroencephalography signal](https://github.com/NicholasCHowlett/eegDataAnalysis).
