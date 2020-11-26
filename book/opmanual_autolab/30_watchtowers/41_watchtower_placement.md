# BUILD - Placing Watchtowers in a city {#localization-watchtower-placement status=ready}

<div class='requirements' markdown="1">

Requires: Assembled [Watchtowers](#watchtower-hardware).

Results: A Watchtower system ready to be used.
</div>

<minitoc/>


## Placement of the watchtowers

There are only two general rules of putting Watchtowers in a city:

1. the field of views of Watchtowers should cover the whole city (i.e. the ground Apriltags)
2. there should be sufficient overlap between the field of views of neighboring Watchtowers.

Below you find a picture of a former Autolab at ETH Zurich. It will give you a quick approximate of how to place your watchtowers and how many you should put.

<div figure-id="fig:autolab_picture">
<img src="opmanual_autolab/images/watchtower_placement/autolab_image.jpg" style="width: 80%"/>
<figcaption>
Picture of the ETH Zurich Autolab.
</figcaption>
</div>

Below is a more synthetic view of the watchtower placement in ETHZ. The ratio of watchtower to road tiles is around 2/3.

<div figure-id="fig:watchtower_placement">
<img src="opmanual_autolab/images/watchtower_placement/autolab_wt_placement.png" style="width: 60%"/>
<figcaption>
Overview of the autolab and of the watchtower placement. Each number shows the position of a watchtower. Watchtowers number 01 to 16 are on the left loop, while watchtower 21 to 35 are on the right loop.
</figcaption>
</div>

Below is the field of view of watchtowers. Please keep in mind that they cover approximately 3 tiles each (even more in some cases), but that on the edge of the image, despite rectification, the image is distorted and thus the Apriltag detection might give inaccurate results. This is why overlapping field of view are important. The more the better.

<div figure-id="fig:watchtower_view_corner">
<img src="opmanual_autolab/images/watchtower_placement/wt_view_corner.png" style="width: 80%"/>
<figcaption>
View from a watchtower in a corner. It covers approximately 3 tiles.
</figcaption>
</div>

<div figure-id="fig:watchtower_view_straight_line">
<img src="opmanual_autolab/images/watchtower_placement/wt_view_straight.png" style="width: 90%"/>
<figcaption>
View from a watchtower on a straight line. It covers approximately 3 tiles.
</figcaption>
</div>

## Connection of the watchtowers

Beside the placement of Watchtowers, they should be connected via Ethernet cables, using a Power over Ethernet (PoE) approach. To use this, make use of the watchtower19-B version and a suitable switch connection.

At ETH Zurich, the Watchtowers are connected to a main switch, which is connected to the main router. Also, all of the Autolab is on a stage, and we pull the cables directly from underneath it, to keep the track clean from cables. Then we have one PC connected via Ethernet to the router, for faster and more reliable communication with the Watchtowers.

Note: if you do not use PoE, prepare your USB chargers and cables that support 2.4A output.

### Recommended network setup (nonumber notoc)

Since all Watchtowers might send data at the same time, we recommend you have a strong network setup. The best, and currently used in the ETHZ Autolab, is a switch with 1 Gb/s ports for each watchtower, with 2 ports at 10 Gb/s, that are connected to a central computer (which in turn needs a 10 Gb/s network card).

Todo: explain the router requirements.
