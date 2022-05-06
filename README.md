## Visualization of axonal rebounds

To visualize the axons, replace the original `make_fig.m` located in the kilosort main folder (`KS-master/mainLoop`) with this Matlab script.

Our modified version of this script will organize the plotting of the waveforms according to the peak value of their rebound:
- In the first subplot of KS (`Temporal Components`), different waveforms are organized from the biggest (left) to the smallest (right) rebounds.
- In the second plot from the top right (unnamed), only the 10 waveforms with the largest rebounds, i.e. the first 10 waveforms on the left of the `Temporal Components` subplot, are illustrated.
