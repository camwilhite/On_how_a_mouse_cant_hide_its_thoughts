# On_how_mice_cant_hide_their_thoughts
A project for analyzing behavioral trajectories based on hippocampal activity

- The brain generates an internal representaion of an animal's position through the spatially-tuned firing of hippocampal 'place cells'. While place cells typically signal the animal's current location, they can also express non-local activity patterns that sweep ahead of the animal toward possible left or right future paths.
- Goal: analyze the trajectories of mice navigating a Y-maze based on hippocampal sweep dynamics. Compare left turn trials with left sweeps with a left turn trials with right sweeps and discuss how to analyze the differences between them.
- Data: previously generated position decodes from the spiking of hippocampal CA1 place cells using Frank Lab algorithm (https://github.com/Eden-Kramer-Lab/replay_trajectory_classification/tree/master), and position information extracted from an overhead camera using DeepLabCut (https://github.com/DeepLabCut/DeepLabCut).
