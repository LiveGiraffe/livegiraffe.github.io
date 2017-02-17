---
title: Analysis of trumpet tone quality using machine learning and audio feature selection
description: The work of my master's thesis
image: /assets/projects/trumpet.jpg
ordering_weight: 2
---

## Masters'Thesis: Potential 

![A recording setup with two microphones and a music stand.](/assets/projects/trumpet.jpg)

Broadly, this research sought to answer the question, "Can computers give feedback on a musician's tone quality?" This work was first presented at [ISMIR 2011](https://trevorknight.squarespace.com/s/Knight-PotentialForAutomaticAssessmentOfTrumpetToneQuality.pdf) then formed the basis of [my master's thesis](http://digitool.library.mcgill.ca/R/?func=dbin-jump-full&object_id=110681).

The abstract from my thesis: 

> This work examines which audio features, the components of recorded sound, are most relevant to trumpet tone quality by using classification and feature selection. A total of 10 trumpet players with a variety of experience levels were recorded playing the same notes under the same conditions. Twelve musical instrumentalists listened to the notes and provided subjective ratings of the tone quality on a seven-point Likert scale to provide training data for classification. The initial experiment verified that there is statistical agreement between human raters on tone quality and that it was possible to train a support vector machine (SVM) classifier to identify different levels of tone quality with success of 72% classification accuracy with the notes split into two classes and 46% when using seven classes. In the main experiment, different types of feature selection algorithms were applied to the 164 possible audio features to select high-performing subsets. The baseline set of all 164 audio features obtained a classification accuracy of 58.9% with seven classes tested with cross-validation. Ranking, sequential floating forward selection, and genetic search produced accuracies of 43.8%, 53.6%, and 59.6% with 20, 21, and 74 features, respectively. Future work in this field could focus on more nuanced interpretations of tone quality or on the applicability to other instruments.