# MULTILANE

Placeholder repo for the paper MultiLane: Lane Intention Prediction and Sensible Lane-Oriented Trajectory Forecasting on Centerline Graphs
by David Sierra-Gonzalez, Anshul Paigwar, Ozgur Erkent and Christian Laugier.

Performance visualizations and source code will be released here.

### Examples of lane intent prediction

We show here some animations that illustrate how the lane intent prediction of our model changes over the course of a sequence.
We use a jet (heatmap) color scale to indicate the probability of a potential centerline; red and orange tones indicate high relative probability, yellow and green intermediate probability, and finally blueish tones indicate low probability. Additionally, the higher the probability, the more opaque the coloring of the centerline (low probability centerlines are completely transparent). The exact probability value given to a lane is also indicated near the end of the centerline, but it may fall outside of the picture in some frames.
Note that the length of the candidate lanes changes randomly between samples (time steps in this case); this is done by design. 

**Yielding to do a left-turn**

<img src="/gifs/lane_0001.gif" width="507" height="460"/>

**Straight at an intesection**

<img src="/gifs/lane_0014.gif" width="507" height="460"/>

**Uncertain at an intersection**

<img src="/gifs/lane_0088.gif" width="507" height="460"/>

**Lane change to overtake a stopped obstacle**

<img src="/gifs/lane_0126.gif" width="507" height="460"/>

**Right lane at a junction**

<img src="/gifs/lane_0147.gif" width="507" height="460"/>
