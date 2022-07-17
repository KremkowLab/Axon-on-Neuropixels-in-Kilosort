## Visualization of axonal rebounds

To visualize the axons, replace the original `make_fig.m` located in the kilosort main folder (`KS-master/mainLoop`) with this Matlab script.

Our modified version of this script will organize the plotting of the waveforms according to the size of the post-synaptic negative peak response (if any):
- In the first subplot of Kilosort -`Temporal Components`-, the different waveforms are now organized from the biggest (left) to the smallest (right) post-synaptic peak value. Consequently, the presence of possible axons in the recording will be indicated by the a blue region in the bottom left part of this subplot (red arrow). 
- In the second plot at the top right (unnamed), only the 10 first waveforms having the largest post-synaptic values (red arrow) are illustrated; they correspond to the first 10 waveforms on the lefter side of the `Temporal Components` subplot.
![alt text](https://github.com/KremkowLab/Axon-on-Neuropixels-in-Kilosort/blob/main/KS%20adapted.png)

A test recording is available under the following link: https://zenodo.org/record/6850116#.YtQNq4RBzQM
