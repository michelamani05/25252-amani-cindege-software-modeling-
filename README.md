Detailed Steps
Vehicle Traffic Lights
Red Light State:
----------------
Description: Vehicles must stop.
Duration: 30 seconds.
Transition: After 30 seconds, the light changes to green.

Green Light State:
------------------
Description: Vehicles can proceed through the intersection.
Duration: 60 seconds.
Transition: After 60 seconds, the light changes to yellow.

Yellow Light State:
------------------
Description: Warning light for vehicles to prepare to stop.
Duration: 5 seconds.
Transition: After 5 seconds, the light changes to red.

Pedestrian Traffic Lights
Don't Walk State:
---------------
Description: Pedestrians must not cross.
Duration: 90 seconds.
Transition: After 90 seconds, the light changes to Walk.

Walk State:
-----------
Description: Pedestrians can cross the road.
Duration: 25 seconds.
Transition: After 25 seconds, the light changes to Flashing Don't Walk.

Flashing Don't Walk State:
-------------------------
Description: Warning light indicating that pedestrians should not start crossing, but those in the crosswalk can continue.
Duration: 5 seconds.
Transition: After 5 seconds, the light changes to Don't Walk.

