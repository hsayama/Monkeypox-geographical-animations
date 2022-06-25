# Monkeypox Geographical Animation Generator

This Mathematica file will read monkeypox time series data from Global.health's 
GitHub page (https://github.com/globaldothealth/monkeypox/)
and generate an mp4 movie file that animates how the numbers of positive cases of monkeypox developed over space and time.

An example can be seen in the following:
* Worldwide animation: https://twitter.com/HirokiSayama/status/1540497919148789760

In the visualization, the size of each disc represents the number of daily new positive cases (scaled). The 
color of the disc is determined by (# of daily new cases) / (max # of daily new cases observed up to that point),
which ranges from 0 (end of epidemic; blue) to 1 (growing or peak of epidemic; red).

Data was smoothed using seven-day moving averages.
