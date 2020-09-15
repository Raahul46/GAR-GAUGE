# Gone Garbage(A smart-garbage-disposal-and-monitoring-system)

A project that primarily focuses to eliminate the hazards of garbage overflow.The system is primarily based on IoT that can alert the responsible officials to collect the garbage from the locations where overflowing dumpsters need immediate concern.

## General Public Application

This application holds the feature of reporting complaints about the overflow of garbage dumpsters in the user's surroundings.The user can choose a specific type of complaint and can even send in pictures regarding it and the application also captures the user's location and sends these dadta to a central base.


## TruckDriver Application

This application uses Google Maps API to locate all the points where the truck driver has to collect the garbage and it priortizes the location based on the dumpster's overflow ratio.The data for this application comes in from the central base which has records for both public's complaint also the data from IoT kits attached with the dumpsters. 

## Trash detecter
A Pi-cam attached to a raspberry pi is placed behind the trash can inorder to monitor any overfill in and around the trash can. If any trash is detected lying on the road around the can, a notification will be sent to the respective official in order to get it cleaned. We trained a convolution neural network with 5 class labels related to trash. We have achieved an accuracy over 80% on the validation data. 

## IoT sensors
We have used the following sensors:
1. Ultra sound          : To calculate the straight depth into the trash

2. Light sensor         : To detect any breakage in the trash can

3. Air quality sensor   : To detect any decomposed materials in the can, avoiding this might lead to malodour in the locality.

4. Infrared light sensor: To determine whether any objects are placed in slanting positions inside the can
(For instance, When you place a wood in the main diagonal of the box, the ultra sound notifies as the trash can is full, so in order to make it robust this feature is added.)

## Co-Creators

<p>Barath Gopinath - <span><a href="https://github.com/barath83"/>barath83</span></a></p>
<p>Janani VI - <span><a href="https://github.com/Janani216"/>Janani216</span></a></p>


