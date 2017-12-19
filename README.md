# Statistical Analyses of Impact of Stressors in Driving Simulation Data

Language Used- R
Problem Statement:
The dataset is acquired by carrying out a controlled experiment on a driv-
ing simulator where n=68 volunteers drove under four different conditions:
No distraction, cognitive distraction, emotional distraction, and sensorimo-
tor distraction. Different response variables were recorded including speed,
acceleration, brake force, steering, and lane position signals, and different ex-
planatory variables including perinasal EDA, palm EDA, heart rate, breath-
ing rate, and facial expression signals; biographical and psychometric covari-
ates were also obtained.
The dataset is organized into various folders T001, T002 and so on which
indicate the different volunteers on which the experiment was carried. Each
of those folders include sub-folders (Sessions) like, BL for the Baseline, PD
for the Practice Drive, RD for the Relaxing Drive, ND for the Normal Drive,
CD for the Cognitive Drive, ED for the Emotional Drive, MD for the Sen-
sorimotor Drive, and FDL or FDN for the Failure Drive. Each of the sub-
folder includes various data channels like Heart Rate(HR), Breathing Rate
(BR), Perinasal Perspiration (pp), Performance Response (res) and Palm
EDA(peda) signal, FACS Signals, thermal data, stm, facial (avi), ROI and
OT.
The fundamental assumption of the experiment that produced the dataset
is that the distracting stressors used, did indeed create stress. If this is not
the case, then the experiment is invalid, as it failed to generate what its
design purported. Stress is assessed through a number of peripheral physio-
logical measures in such cases. In this simulation, the physiological measures
recorded for this purpose include: perinasal perspiration, palm EDA, breath-
ing rate, and heart rate.
The purpose of the project is to ensure the validity of the dataset. Using sta-
tistical tests we need to determine which of these measures signify signicant
elevation of stress and which are not, and comment on the results.
This project is divided in two parts:

Part 1
•	Dissected driver data under cognitive, emotional, sensorimotor, and mixed stressors.
•	Preprocessed this raw data by eliminating out of range data. Data here refers to heart rate, breath rate, and various other similar attributes while driving and then visualized these.

Part 2:
Performed paired t-test/ANOVA to find if these stresses are actually impacting the driver.

These sub-divisions have a pdf file Report.pdf which mentions why and how things are done along with output.


