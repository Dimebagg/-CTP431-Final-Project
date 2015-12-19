# -CTP431-Final-Project
tempo &amp; loudness visualizer

idea : to express tempo real-time

implementation :

  1. low-pass filtering to extract bass-ish sounds
  2. find outstanding peaks from the time domain-filtered temporary signal
  3. make a ball moves with velocity proportional to the number of counted peaks

future works :

  1. more knit and good looking visualization, using some libraries
  2. the ball moves fast given the white noise, so it's necessary to add sound/noise recognition algorithm using energy terms
  3. more accurate tempo extraction, using other features...
