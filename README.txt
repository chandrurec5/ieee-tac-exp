The file contains the experiments for the paper titled ``A Linearly Relaxed Approximate Linear Program
for Markov Decision Processes"
runall.m - master file which runs the lookahead.m and plts.m
lookahead.m- compares the two types of lookahead policies i) computed using reduced linear program generated via the cone condition (conepol.m) and ii) computed using reduced linear program using constraint sampling (rlppol.m)
generateW.m - generates the W matrix given the 
lot.m - sample from a discrete distribution
mdp_LP.m - runs the (approximate/projected) linear program; is a modified version of mdp_LP.m from the MDPtoolbox
mdp_policy_iteration.m - part of the MDPtoolbox
MDPtoolbox - http://www7.inra.fr/mia/T/MDPtoolbox/

