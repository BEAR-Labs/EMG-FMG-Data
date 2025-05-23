# EMG-FMG-Data
The data found using this repository is electromyography (EMG) and force myography (FMG) data collected from 27 able-bodied participants at different limb positions and loading conditions while they performed 4 different hand gestures. The following Zenodo link will lead you to where the data can be downloaded.

**Zenodo Link:** https://zenodo.org/records/15420178

For more information about the data collection process, experimental procedures, and data analysis pipelines, please feel free to use the reference below which will lead you to the study.  

**Citation:** Young PR, Hong K, Winslow EJ, Sagastume GK, Battraw MA, Whittle RS, Schofield JS. (2025) The effects of limb position and grasped load on hand gesture classification using electromyography, force myography, and their combination. PLoS ONE 20(4): e0321319. https://doi.org/10.1371/journal.pone.0321319

The organization of the data is as follows: Inside of the folder labeled “Data”, there are 27 folders labeled “Par” followed by a number, denoting each participant’s dataset. Inside each of these folders are 4 sub-folders with the following names: Key, Pinch, Power, and Tripod. Each of these folders represent data collected when the participant was performing each of these hand gestures. 

Inside each of the hand gesture folders, there are 5 sub-folders with the following names: 0, 250, 500, 750, and 1000. These folders represent the different loading conditions the participant was given, ranging from 0 grams to 1000 grams. 

In each of the loading condition folders, there are 8 .csv files. This is the raw EMG and FMG data collected at the different limb positions during the experiment, reported in volts. The 8 .csv files represent each of the 8 limb positions. Each of the files has the naming scheme as follows: "Hand Gesture" "Loading Condition" "Limb Position". For example, the file for the hand gesture of Key with the loading condition of 500 at a limb position of 7 is named “Key 500 7”. A figure is provided to illustrate the folder organization while further information on what these hand gestures, loading conditions, and limb positions look like can be found in the paper.

![image](https://github.com/user-attachments/assets/ab373f9b-390a-4424-9392-daaf173cc3dc)

In each .csv file, there are 16 columns and 36001 rows. The first row is a header which labels the data collected by each channel. Each row is a sample of data collected by the EMG and FMG sensors reported in volts. Channels 1-8 are FMG channels and channels 9-16 are EMG channels. Data was collected at a sampling rate of 2000 Hz over 18 seconds, resulting in 36000 samples of data for each hand gesture, loading condition, and limb position. For each participant, there are 160 .csv files for all combinations of hand gesture, loading condition, and limb position. Again, while this README file provides a basic understanding of the data, a more in-depth explanation can be found by reading the paper provided in the citation above.

