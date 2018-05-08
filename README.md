# article-confidence-matching

This repository contains anonymised behavioural data supporting the following paper:

<a href="https://www.nature.com/articles/s41562-017-0117"> Bang et al. (2018) "Confidence matching in group decision-making" Nature Human Behaviour<a/>

The data set comprises 6 experiments:

**Experiment 1**

Subjects performed the isolated task (160 trials) and the social task (160 trials) in counterbalanced order.

**Experiment 2**

Subjects performed the social task (384 trials).

**Experiment 3**

Subjects performed the social task (384 trials) with a continuous confidence scale.

**Experiment 4**

Subjects first performed the isolated task (200 trials) and then four runs of the social task (2 x 240 trials) with virtual partners of varying expertise and confidence.

**Experiment 5**

Subjects first performed the isolated task (160 trials) and then the social task (160 trials) with responses submitted to a strictly proper scoring rule.

**Experiment 6**

Subjects first performed the isolated task (160 trials) and then the social task (160 trials) and the observe task (160 trials) in counterbalanced order. Note that there are two data files for the isolated task as subjects were re-paired for the social and the observe tasks.

**The data files contain the following information**

*group*: group identifier

*sbjID*: subject identifier

*trial*: trial number

*stimInterval*: target interval

*stimContrast*: target contrast

*sbjConfidence*: subject confidence

*sbjChoice*: subject choice 

*sbjAcc*: subject accuracy

*otherConfidence*: partner confidence if applicable

*otherChoice*: partner choice if applicable

*otherAcc*: partner accuracy if applicable

*dyadChoice*: group choice if applicable

*dyadAcc*: group accuracy if applicable

*order*: only for EXP1, order of isolated and social tasks [1: isolated first, 2: social first]

*noise*: only for EXP4, fitted subject noise

*bias*: only for EXP4, fitted subject bias

*condition*: only for EXP4, partner condition [1: AL-CL; 2: AL-CH; 3: AH-CL; 4: AH-CH]

*session*: only for EXP4, social run

This data is being released with a permissive open-source license. You should feel free to use or adapt the code as long as you follow the terms of the license. If you make use of the data, we would appreciate that you cite the paper.
