# Predicting fingers flexion

In this notebook we will work with a subset of the dataset from the BCI (for Brain Computer Interface) competition IV. The objective of this data is to predict the finger flexion of a subject using only ElectroCorticoGram (ECoG) signals recorded simultaneously on the brain of the subject. In this session you will use the data from subject 3 and predict the flexion of its thumb along time. The subjects from the dataset were epileptic patients with ECoG sensors in place for medical reasons. The subjects were equipped with gloves measuring the flexion of each of their fingers simultaneously with the ECoG signals. The subjects were asked to move their fingers with visual cue. The signal is a 10 minutes recording at 1000Hz of 64 electrodes. 

For more information about the dataset here is the related link (http://www.bbci.de/competition/iv/).

In this notebook we will apply multiple machine learning algorithms (supervised learning) to this dataset, and we will try to find the best one to predict a finger flexion.
