
### This code is associated with the paper from Shin et al., "The rate of transient beta frequency events predicts behavior across tasks and species". eLife, 2017. http://dx.doi.org/10.7554/eLife.29086


This code was written by Hyeyoung Shin, Department of Neuroscience, Brown University.
Please direct correspondence to shinehyeyoung@gmail.com

the code was written in MATLAB R2017a.

run master_rhythmevents.m : 
this will loop through prestimulus TFRs and detect local maxima and events in the frequency band of interest.
user must choose folder where prestimulus TFRs can be loaded from. .mat files containing calculations returned by this script will be saved in the same folder.
calls functions rhythm_localmax_analysis.m and rhythm_event_analysis.m

