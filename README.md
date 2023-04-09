# Explainable AI (XAI) on Machine Learning for Task Load Classification

## xai-2023-supplemental
Supplemental materials, images, datasets and notebooks for XAI 2023. This dataset consists of raw EEG data from 48 subjects who participated in a multitasking workload experiment utilizing the SIMKAP multitasking test. The subjects’ brain activity at rest was also recorded before the test and is included as well. The Emotiv EPOC device, with sampling frequency of 128Hz and 14 channels was used to obtain the data, with 2.5 minutes of EEG recording for each case. Subjects were also asked to rate their perceived mental workload after each stage on a rating scale of 1 to 9 and the ratings are provided in a separate file.

## Instructions: 
The data for each subject follows the naming convention: subno_task.txt. For example, sub01_lo.txt would be raw EEG data for subject 1 at rest, while sub23_hi.txt would be raw EEG data for subject 23 during the multitasking test. The rows of each datafile corresponds to the samples in the recording and the columns corresponds to the 14 channels of the EEG device: AF3, F7, F3, FC5, T7, P7, O1, O2, P8, T8, FC6, F4, F8, AF4, respectively.

The ratings for each subject is given in a separate file ratings.txt. They are given in a comma separated value format: subject number, rating at rest, rating for test. For example: 1, 2, 8 would be subject 1, rating of 2 for “at rest”, rating of 8 for “test”. Note that ratings for subjects 5, 24 and 42 are unavailable.

Produce an excel file for one run accross all test instances for all 7 features. 
