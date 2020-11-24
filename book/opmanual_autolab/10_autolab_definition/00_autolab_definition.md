# Autolab definition {#part:autolab-definition status=ready}

<div class='requirements' markdown="1">

Requires: A Duckietown up to specifications from [the Duckietown book](+opmanual_duckietown#book).

Results: Knowledge of the fundamental structures that make an Autolab.

Next Steps: Setting up the [watchtowers](#watchtower-hardware).

</div>

An Autolab is a Duckietown with a set of additional structures:

- A fleet of Autobots*
- A set of watchtowers
- A map
- A town device
- A localization system
- An Autolab control interface
- A maintenance area (optional)

\*The Duckiebots that are used inside an Autolab are called Autobots and rely on additional specifications.


### The fleet of Autobots
An Autolab is nothing without its fleet of Autobots. The [Autobots](#autobot-setup) are Duckiebots improved with different parts, mainly for localization (extensions for autocharging exist). As the Autobots are used to run benchmarking tests, submissions or other, they should follow a strict procedure of calibration. It is therefore advised to leep a log of all events that happen throughout the life of an Autobot, by storing a lab-specific log on Github (previously called *fleet-roster*) or on Confluence.


### The watchtowers
[Watchtowers](#watchtower-hardware) are devices in Duckietown with a single camera and no actuation. In the Autolab, they guarantee coverage of the city through the localization system.


### The Map
For an Autolab to work, a precise map of the city is needed including the placement of ground Apriltags as a reference for the localization system. This part is handled in [](#autolab-map-making)


### The Duckietown
The [Duckietown](#autolab-town) in the Autolab refers to a central Raspberry Pi (a device) without any actuators or sensors, that is able to connect to multiple devices within the Autolab. It can store the Autolab map, data logs, etc. It follows the principle of a town as a robot in the quest for a fully automated Autolab.


### The localization system

The [localization system](#autolab-localization) is comprised of a set of watchtowers distributed in the city and a central Duckietown device representing the city. If you have multiple cities in your Autolab, make sure to assign each city a different Duckietown device. The information stream from watchtowers and Autobots is processed to extract the poses over time from all Autobots, thereby generating a trajectory. The stream of images from watchtowers also finds use in many other projects than the localization system here described.


### The Autolab control interface

Warning: this part is under development and will be updated in due time.

<!--
The Autolab operation server, described in the [autolab operation manual](#autolab-operation-manual) and currently under development, is and will be the human interface to control the high level functions of the Autolab, to monitor its status and activity, and to launch experiments.

<div figure-id="fig:Autolab">
<img src="images/autolab.png" style="width: 50%"/>
<figcaption>
Sample map for an Autolab
</figcaption>
</div>
-->

### The maintenance area
The maintenance area is an area that is designed to include the activities of an Autolab which are not related to the self-driving goals of Duckietown. Currently it is only comprised of the [auto-charging area](#autolab-auto-charging), but could be extended to include, say:

- A parking lot
- An auto-calibration arena

All maintenance areas should be accessible via a single entry point. The current auto-charging area is interesting for the full automation of the Autolab, as it allows the Autobots to go around indefinitely and recharge themselves, without any human intervention.

TODO: add image of Autolab and maintenance area
