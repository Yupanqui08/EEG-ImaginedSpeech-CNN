# EEG-ImaginedSpeech-CNN

Dataset Used: https://zenodo.org/record/3554128#.Ye85WC-cby8 </br>

Data_Visualizations.ipynb: Uses MNE libraries to create graphs and other visualizations of the dataset. </br> </br>

PrepareDataset.ipynb: Seperates each csv file into testing and training data. It also seperates the EEG data from the imagined phonem. </br>

Creates sub_data_test, sub_events_test, sub_data_train, sub_events_train csv files for each subject. </br> </br>

v1-cnn-eeg.ipynb: Processes data using CNN. Results were not above chance. </br> </br>

v2-cnn-eeg.ipynb: Preprocesses data using wavelet denoising, then processes it using CNN. Results were not above chance.

GroupingData.ipynb: Groups the EEG data into trials so that the data can be processed as trials instead of partial seconds (individual rows). This is part of a different attempt that is currently still in the works. 

EEG_ML-TimeFix.ipnb: Adds a "Time" column with numbers 1-1280 for each trial. This gives each trial an independent time sequence.
