# GM Vehicle Lane Managment System
As part of CSE 435: Software Engineering at Michigan State University (MSU) and in conjunction with General Motors (GM), Group 1 developed a Lane Management System (LMS) that included the following features: Lane Keeping Systems (LKS), Lane Departure Warning Systems (LDWS) and Lane Centering Systems (LCS) for a GM vehicle.

## Project Background
Automotive manufacturers are bringing in a variety of features that assist the future drivers as a means to enhance the convenience and ensure safety in driving. Some of these new features rely on the lane markings on the road in order to enable the driver to ensure that the car remains within the lane while driving. The objective of this project is to develop a Lane Management System (LMS) that will include the following features: Lane Keeping Systems (LKS), Lane Departure Warning Systems (LDWS) and Lane Centering Systems (LCS). LMS is a driver assistance system that can include a variety of functions starting with the simplest passive LMS that can detect the lanes and compute the relative position of the vehicle to the most complex active LMS, which can take over the control from the driver to position the vehicle within a lane.

## Project Description Summary
The simplest functionality of LMS is a lane sensing feature, which essentially identifies the lane in which the host vehicle is in and also the relative position of the vehicle within the identified lane. The position information could be accurate with respect to relative position vales or abstract values like, extreme left, in the middle, extreme right etc. Some of the issues that are specific to this feature that need to be taken into account include: what happens when there is no (or ambiguity in) lane markings, when the road is curving, initiation and resumption of this feature etc. You may assume a set of cameras for lane marker detection, appropriate road side units and possibly GPS information, etc.

LDWS would make use of the Lane sensing feature and issues warnings to the driver when the vehicle leaves a lane. Here some issues are: proper definition of lane departure, when and how often to give warnings, how do we deal with momentary/partial departure from a lane, distinguishing intentional departures, prediction of departure, etc. LKS would be an enhancement to LDWS, where the system could intervene and try to send commands to steer and adjust the position of the vehicle. This functionality is more critical as the control is taken away from the driver. The issues to be addressed include who is the master, when and how to override, period of control. . Many of these features are enabled only when the speed of the vehicle is between certain thresholds.

## Useful Links
- [Project Website hosted on the MSU CSE servers] (https://cse.msu.edu/~periala3/public.html)
- [CSE 435 Course Page] (https://www.cse.msu.edu/~cse435/) 
- [Professor Betty Cheng's Site] (https://www.cse.msu.edu/~chengb/)

### References
B.H.C. Cheng, “CSE 435 Software Engineering, in-lecture,” October 2021.
J. Perialas, “LMS,” LMS Team Page, 2021. [Online]. Available:
https://cse.msu.edu/~periala3/index.html/ . [Accessed: 16-Nov-2021].