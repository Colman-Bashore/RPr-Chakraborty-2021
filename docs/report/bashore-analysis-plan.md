# Planned revisions to reproduction of ....

Author: Colman Bashore

## Analysis

My goal with my modification to the reproduction of the study is to improve the 
cartography of all of the maps produced in the study code. My aim is to familiarize
myself with the tmap package in r and adjust some of the parameters used when producing
map plots in order to make each map both more legible, and more understandable.

This goal is driven by my perception of many of the maps as difficult to read due
to over complicated line work and overemphasis of county and state borders instead of
letting the data shine through. My adjustment to each of the maps will involve adjusting
line weights and widths through the tmap package and also using the rmapshaper package
to simplify the state borders such that they cause less of a distraction.

## Results

Changes to the map production code will be visible in the maps themselves that are plotted.
For the first map I will leave the original code before my adjusted code to show the
difference in visibility and legibility. From this, the simplification of state borders
will be quite apparent.

## Discussion
If in the new maps, data is more visible then the adjustment will have been successful. 
Ideally, the state lines will not be over simplified but will no longer be a distraction.
This is a subjective analysis, but line simplification as well as other adjustments to the
tmap parameters for each map should result in cleaner, more accessible maps.

