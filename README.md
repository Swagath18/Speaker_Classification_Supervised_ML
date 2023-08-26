# Speaker_Classification
A Speaker identification system that predicts the city of origin of the speaker

Implementing a speaker identification system that predicts the city of origin of the speaker of a given utterance.

Dataset: The Corpus of Regional African American Language (CORAAL)[1] contains speakers each
belonging to one of five different US cities: 1) Rochester, NY (ROC), 2) Lower East Side,
Manhattan, NY (LES), 3) Washington DC (DCB), 4) Princeville, NC (PRV), or 5) Valdosta, GA
(VLD). We selected only the utterances in the corpus with length greater than 10 seconds. In
addition, a few utterances have been corrupted by a 10dB babble noise masker

Objectives : To derive a set of features and implement them to predict the city of origin of the speaker
of every utterance. Will train on clean data and test with 1) clean data, and 2) noisy data.

CORAAL dataset : http://oraal.uoregon.edu/coraal
