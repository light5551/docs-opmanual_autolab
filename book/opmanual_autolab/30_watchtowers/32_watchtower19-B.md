# Assembling the watchtower (WT19-B) and TL extension {#watchtower-hardware-assembly-WT19-B status=ready}

<div class='requirements' markdown="1">

Requires: Material: Watchtower components. To obtain them contact info@duckietown.org.

Requires: An [initialized SD-card](#wt-sd-card-init) for traffic lights or Watchtowers.

Requires: Tools: (strong) wood glue or hot glue gun, tape, double-sided tape.

Results: An Assembled Watchtower system in WT19-B configuration.


</div>

This instructions are divided into 9 different sections:

- [Part 1: Preliminaries and part overview](#howto-bom-WT19B)
- [Part 2: Housing](#howto-housing-WT19B)
- [Part 3: Computation unit and ground plate](#howto-computation-WT19B)
- [Part 4: Vertical tube](#howto-vert-tube-WT19B)
- [Part 5: Fan](#howto-fan-WT19B)
- [Part 6: RGB sensor and top plate](#howto-rgb-WT19B)
- [Part 7: Camera unit](#howto-camera-WT19B)
- [Part 8: Result WT19-B](#howto-result-WT19B)
- [Part 9: Extension to a traffic light](#howto-traffic-light-WT19B)

## Preliminaries {#howto-bom-WT19B}

Welcome to the watchtower assembly page. The watchtowers make your city way more real and the duckies feel more at home like this:)

At some steps, you see a small glue icon on it. Those parts are not separated anymore no matter if you are building a watchtower or a traffic light (TL). If you arrive at such a step, make sure that the parts are really connecting rigidly. Maybe they are already stuck together without glue, but most of the time its wise to use at least some of it just for the security of our citizens!
If you only want to build a single watchtower, you find an overview of all needed components below:

<div figure-id="fig:WT19-B_all_components">
<img src="opmanual_autolab/images/watchtower/WT19-B assembly/WT19-B_all_components.png" style="width: 90%"/>
<figcaption>
Overview of all components needed to build a Watchtower in WT19-B configuration.
</figcaption>
</div>

However, if you want to extend your watchtower to a traffic light, you need some more parts than shown above and there are some additional steps to take. All those steps are indicated on the bottom right with a sign that tells you where you have to leave the standard watchtower instructions. If so, jump directly to the indicated step number and return to that place once there is a sign that tells you to do so. Please make sure to do those additional steps in the very order they are indicated and jump back to the standard watchtower instructions where it says "Continue with ..."

Note: If you have a WT-19A configuration, you can as well attach a traffic light extension to it including the horizontal tubes and the LED. However, the space within the box of the WT is probably not high enough for the additional board with the microcontroller you need. In this case you could e.g. just leave the ceiling of your WT open in order to fit everything in:)

<!-- NOTE: PoE version:
<div figure-id="fig:WT19-B_all_components_PoE">
<img src="opmanual_autolab/images/watchtower/WT19-B assembly/WT19-B_all_components_PoE.png" style="width: 90%"/>
<figcaption>
Overview of all components needed to build a Watchtower in WT19-B configuration using Power over Ethernet.
</figcaption>
</div>
-->

## Housing {#howto-housing-WT19B}

### Step 1
Take one round and one angled tube holder and make sure to mount them in the right order.

<div figure-id="fig:WT19-B_STEP_01">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_01.png" style="width: 70%"/>
<figcaption>
STEP_01
</figcaption>
</div>

### Step 2
<div figure-id="fig:WT19-B_STEP_02">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_02.png" style="width: 70%"/>
<figcaption>
STEP_02
</figcaption>
</div>

### Step 3
Make sure to take here the part that has the same structure on the top as the part that is already mounted (don't mix it up with the part that is used in step 4).

<div figure-id="fig:WT19-B_STEP_03">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_03.png" style="width: 70%"/>
<figcaption>
STEP_03
</figcaption>
</div>

### Step 4
<div figure-id="fig:WT19-B_STEP_04">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_04.png" style="width: 70%"/>
<figcaption>
STEP_04
</figcaption>
</div>

### Step 5
<div figure-id="fig:WT19-B_STEP_05">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_05.png" style="width: 70%"/>
<figcaption>
STEP_05
</figcaption>
</div>

### Step 6
<div figure-id="fig:WT19-B_STEP_06">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_06.png" style="width: 70%"/>
<figcaption>
STEP_06
</figcaption>
</div>

## Computation unit and ground plate {#howto-computation-WT19B}

### Step 7
Put now the assembled parts aside and take the Raspberry Pi (Model 4) together with two heat sinks and an SD card (Only insert the SD card, if it is already flashed, otherwise: do [this](#watchtower-initialization) first).

Note: Pay attention to the orientation of the ground plate to mount the Raspberry Pi on!

<div figure-id="fig:WT19-B_STEP_07">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_07.png" style="width: 70%"/>
<figcaption>
STEP_07
</figcaption>
</div>

### Step 8
<div figure-id="fig:WT19-B_STEP_08">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_08.png" style="width: 70%"/>
<figcaption>
STEP_08
</figcaption>
</div>

### Step 9
<div figure-id="fig:WT19-B_STEP_09">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_09.png" style="width: 70%"/>
<figcaption>
STEP_09
</figcaption>
</div>

### Step 10
<div figure-id="fig:WT19-B_STEP_10">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_10.png" style="width: 70%"/>
<figcaption>
STEP_10
</figcaption>
</div>

### Step 11
If the ethernet cable is not available yet, you can plug it in later as well.

<div figure-id="fig:WT19-B_STEP_11">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_11.png" style="width: 70%"/>
<figcaption>
STEP_11
</figcaption>
</div>

### Step 12
<div figure-id="fig:WT19-B_STEP_12">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_12.png" style="width: 70%"/>
<figcaption>
STEP_12
</figcaption>
</div>

## Vertical tube {#howto-vert-tube-WT19B}

### Step 13
Wire the long camera cable through the tube.

<div figure-id="fig:WT19-B_STEP_13">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_13.png" style="width: 70%"/>
<figcaption>
STEP_13
</figcaption>
</div>

### Step 14
Put the gray tube in the housing and wire the cable through.

Note: If you consider to build a traffic light later, make sure that the tube has an additional hole which must be in the bottom half of the tube (otherwise, turn it around).

<div figure-id="fig:WT19-B_STEP_14">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_14.png" style="width: 40%"/>
<figcaption>
STEP_14
</figcaption>
</div>

### Step 15 {#step_15_WT19B}
Open the cable plug on the Raspberry Pi and insert the cable.

Note: Make sure that the metallic contacts on the cable match the ones in the plug (The text cannot be taken as an indicator)!

<div figure-id="fig:WT19-B_STEP_15A">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_15A.png" style="width: 70%"/>
<figcaption>
STEP_15A
</figcaption>
</div>

Close the plug with a strong press similar to what you have done on the Duckiebot.

<div figure-id="fig:WT19-B_STEP_15B">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_15B.png" style="width: 70%"/>
<figcaption>
STEP_15B
</figcaption>
</div>

### Step 16

<div figure-id="fig:WT19-B_STEP_16">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_16.png" style="width: 70%"/>
<figcaption>
STEP_16
</figcaption>
</div>

## Fan {#howto-fan-WT19B}

### Step 17
Mount the fan to the last remaining fan plate of the housing. Note the orientation of the fan cable!

<div figure-id="fig:WT19-B_STEP_17">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_17.png" style="width: 70%"/>
<figcaption>
STEP_17
</figcaption>
</div>

### Step 18
Slide in the plate with the fan according to the arrows in the figure [](#fig:WT19-B_STEP_18). Don't glue this part to the rest of the housing as you probably have to remove it quite often.

<div figure-id="fig:WT19-B_STEP_18">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_18.png" style="width: 70%"/>
<figcaption>
STEP_18
</figcaption></div>

### Step 19
Connect the cables of the fan to those exact pins on the Raspberry Pi.

<div figure-id="fig:WT19-B_STEP_19">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_19.png" style="width: 70%"/>
<figcaption>
STEP_19
</figcaption>
</div>

## RGB sensor and top plate {#howto-rgb-WT19B}

### Step 20
Now put the housing away for a second and take the RGB sensor and the top plate. Pay attention to the orientation of the top plate not to mount the RGB sensor to the wrong side.

<div figure-id="fig:WT19-B_STEP_20">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_20.png" style="width: 70%"/>
<figcaption>
STEP_20
</figcaption>
</div>

### Step 21A
Connect five jumper cables to the RGB sensor in this exact order (the colors do not matter and are just for indicating the different cables more clearly).

<div figure-id="fig:WT19-B_STEP_21A">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_21A.png" style="width: 70%"/>
<figcaption>
STEP_21A
</figcaption>
</div>

### Step 21B
Connect the other ends of the jumper cables to this exact pins on the Raspberry Pi.

<div figure-id="fig:WT19-B_STEP_21B">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_21B.png" style="width: 70%"/>
<figcaption>
STEP_21B
</figcaption>
</div>

### Step 22
Put the top plate on the rest of the watchtower housing. Don't glue this part as you probably have to remove it quite often in the future.

<div figure-id="fig:WT19-B_STEP_22">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_22.png" style="width: 70%"/>
<figcaption>
STEP_22
</figcaption>
</div>

Congratulation, you have finished the bottom part of the watchtower WT19-B!

## Camera unit {#howto-camera-WT19B}

### Step 23
Take one round and one angled camera holder (with one flat side each) and pay attention which one is on top.

<div figure-id="fig:WT19-B_STEP_23">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_23.png" style="width: 70%"/>
<figcaption>
STEP_23
</figcaption>
</div>

### Step 24
<div figure-id="fig:WT19-B_STEP_24">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_24.png" style="width: 70%"/>
<figcaption>
STEP_24
</figcaption>
</div>

### Step 25
<div figure-id="fig:WT19-B_STEP_25">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_25.png" style="width: 70%"/>
<figcaption>
STEP_25
</figcaption>
</div>

### Step 26
<div figure-id="fig:WT19-B_STEP_26">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_26.png" style="width: 70%"/>
<figcaption>
STEP_26
</figcaption>
</div>

### Step 27
Wire the long camera cable from the tube through the camera housing you have asssembled recently. Then put the camera housing on the top of the vertical tube.

<div figure-id="fig:WT19-B_STEP_27A">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_27A.png" style="width: 40%"/>
<figcaption>
STEP_27A
</figcaption>
</div>

Plug in the camera cable in a similar way to what you have done in [step 15](#step_15_WT19B) on the Raspberry Pi. Again make sure to have the metallic connectors on the right side (facing the board and not the lens)!

<div figure-id="fig:WT19-B_STEP_27B">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_27B.png" style="width: 40%"/>
<figcaption>
STEP_27B
</figcaption>
</div>

Then close the plug with a strong press.

<div figure-id="fig:WT19-B_STEP_27C">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_27C.png" style="width: 40%"/>
<figcaption>
STEP_27C
</figcaption>
</div>

### Step 28
Slide the camera in the camera housing using the narrow slit in the front. The camera must face downwards!

<div figure-id="fig:WT19-B_STEP_28">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_28.png" style="width: 40%"/>
<figcaption>
STEP_28
</figcaption>
</div>

### Step 29
Assemble the top lid on the camera housing for protection of the camera.

<div figure-id="fig:WT19-B_STEP_29A">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_29A.png" style="width: 70%"/>
<figcaption>
STEP_29A
</figcaption>
</div>

<div figure-id="fig:WT19-B_STEP_29B">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_29B.png" style="width: 70%"/>
<figcaption>
STEP_29B
</figcaption>
</div>

### Step 30
Finally, connect your watchtower to power using the micro USB plug on the side of the Raspberry Pi. The fan should start running immediately. If not, make sure all the cables of the fan and the RGB sensor are connected correctly!

<div figure-id="fig:WT19-B_STEP_30">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_30.png" style="width: 70%"/>
<figcaption>
STEP_30
</figcaption>
</div>

## Results WT19-B and WT19-B_TL {#howto-result-WT19B}
If you have built a standard watchtower, the final result should look like on the pictures below.

<div figure-id="fig:WT19-B_complete">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/WT19-B_complete_assembly.png" style="width: 30%"/>
<figcaption>
CAD model of the WT19-B configuration
</figcaption>
</div>

<div figure-id="fig:WT19-B_final">
<img src="opmanual_autolab/images/watchtower/WT19-B.png" style="width: 30%"/>
<figcaption>
Assembled Watchtower in WT19-B configuration.
</figcaption>
</div>

If you have done all additional steps for the traffic light extension as well, you should have arrived at the result shown in figure [](#fig:WT19-B_TL_complete):

<div figure-id="fig:WT19-B_TL_complete">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/WT19-B_TL_complete.png" style="width: 80%"/>
<figcaption>
CAD model of the WT19-B_TL configuration
</figcaption>
</div>

Congratulations, you finished this instruction page!


## Extension to a traffic light {#howto-traffic-light-WT19B}
Those steps are not meant to be done in a series, so pay attention to the signs on where to return to the standard instructions of the watchtower. Make sure to build the assemblies as many times as they are indicated in the black box (either once or twice).


### Step 31
Mount the HUT on the four stand-offs on the Raspberry Pi with four M2.5 nuts. Your HUT may be another version than the one on the picture and hence look a bit differently. Don't worry: you most probably still got the right one!

<div figure-id="fig:WT19-B_STEP_31">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_31.png" style="width: 70%"/>
<figcaption>
STEP_31
</figcaption>
</div>

### Step 32
For the traffic light, make sure to connect the two cables of the fan to the pins on the HUT and not on the Raspberry Pi (as shown in figure [](#fig:WT19-B_STEP_32)):

<div figure-id="fig:WT19-B_STEP_32">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_32.png" style="width: 70%"/>
<figcaption>
STEP_32
</figcaption>
</div>

### Step 33
Connect the other ends of the jumper cables to this exact pins on the HUT.

<div figure-id="fig:WT19-B_STEP_33">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_33.png" style="width: 70%"/>
<figcaption>
STEP_33
</figcaption>
</div>

### Step 34
We are now going to start building the other side of the traffic light stand, shown in the small picture in the top left of figure [](#fig:WT19-B_STEP_34). Again, make sure to take one round and one angled tube holder.

<div figure-id="fig:WT19-B_STEP_34">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_34.png" style="width: 70%"/>
<figcaption>
STEP_34
</figcaption>
</div>

### Step 35
<div figure-id="fig:WT19-B_STEP_35">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_35.png" style="width: 70%"/>
<figcaption>
STEP_35
</figcaption>
</div>

### Step 36
<div figure-id="fig:WT19-B_STEP_36">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_36.png" style="width: 70%"/>
<figcaption>
STEP_36
</figcaption>
</div>

### Step 37
<div figure-id="fig:WT19-B_STEP_37">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_37.png" style="width: 70%"/>
<figcaption>
STEP_37
</figcaption>
</div>

### Step 38
<div figure-id="fig:WT19-B_STEP_38">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_38.png" style="width: 70%"/>
<figcaption>
STEP_38
</figcaption>
</div>

### Step 39
<div figure-id="fig:WT19-B_STEP_39">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_39.png" style="width: 70%"/>
<figcaption>
STEP_39
</figcaption>
</div>

### Step 40
<div figure-id="fig:WT19-B_STEP_40">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_40.png" style="width: 70%"/>
<figcaption>
STEP_40
</figcaption>
</div>

### Step 41
Make sure the tube is at least 230mm long. Here you don't need to have a hole on the side as in the vertical tube on the watchtower as there are no cables running through.

<div figure-id="fig:WT19-B_STEP_41">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_41.png" style="width: 70%"/>
<figcaption>
STEP_41
</figcaption>
</div>

### Step 42
The following 6 steps have to be done *twice* in order to achieve the result shown in the top left corner of the figure [](#fig:WT19-B_STEP_42) two times!

<div figure-id="fig:WT19-B_STEP_42">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_42.png" style="width: 70%"/>
<figcaption>
STEP_42
</figcaption>
</div>

### Step 43
<div figure-id="fig:WT19-B_STEP_43">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_43.png" style="width: 70%"/>
<figcaption>
STEP_43
</figcaption>
</div>

### Step 44
<div figure-id="fig:WT19-B_STEP_44">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_44.png" style="width: 70%"/>
<figcaption>
STEP_44
</figcaption>
</div>

### Step 45
<div figure-id="fig:WT19-B_STEP_45">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_45.png" style="width: 70%"/>
<figcaption>
STEP_45
</figcaption>
</div>

### Step 46
<div figure-id="fig:WT19-B_STEP_46">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_46.png" style="width: 70%"/>
<figcaption>
STEP_46
</figcaption>
</div>

### Step 47
<div figure-id="fig:WT19-B_STEP_47">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_47.png" style="width: 70%"/>
<figcaption>
STEP_47
</figcaption>
</div>

### Step 48
Now we are going to assemble the core of the traffic light: the unit holding the LED! Again make sure to use the round and the angled tube holders at the right place.

<div figure-id="fig:WT19-B_STEP_48">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_48.png" style="width: 70%"/>
<figcaption>
STEP_48
</figcaption>
</div>

### Step 49
<div figure-id="fig:WT19-B_STEP_49">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_49.png" style="width: 70%"/>
<figcaption>
STEP_49
</figcaption>
</div>

### Step 50
<div figure-id="fig:WT19-B_STEP_50">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_50.png" style="width: 70%"/>
<figcaption>
STEP_50
</figcaption>
</div>

### Step 51
<div figure-id="fig:WT19-B_STEP_51">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_51.png" style="width: 70%"/>
<figcaption>
STEP_51
</figcaption>
</div>

### Step 52
Put the part you have assembled so far away and connect the four small parts for the LED stripe to its corresponding plate.

<div figure-id="fig:WT19-B_STEP_52">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_52.png" style="width: 70%"/>
<figcaption>
STEP_52
</figcaption>
</div>

### Step 53
Now mount this structure to the other housing from step 51.

<div figure-id="fig:WT19-B_STEP_53">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_53.png" style="width: 70%"/>
<figcaption>
STEP_53
</figcaption>
</div>

### Step 54
Finish this assembly with one round tube holder on each side.

<div figure-id="fig:WT19-B_STEP_54">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_54.png" style="width: 70%"/>
<figcaption>
STEP_54
</figcaption>
</div>

### Step 55
Now take the stripe with the four LED and wire the three cables from the bottom through the traffic light assembly from the previous steps. Make sure to fold the stripe in a way that you can put it in the small square and that each diode has its own small 'window' to look through. Maybe you need some glue here to make the LED stripe stick in it's place.

<div figure-id="fig:WT19-B_STEP_55A">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_55A.png" style="width: 70%"/>
<figcaption>
STEP_55A
</figcaption>
</div>

Then take one of the gray horizontal tubes (approximately 430mm long) and wire all cables through this tube as shown in the picture below:

<div figure-id="fig:WT19-B_STEP_55B">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_55B.png" style="width: 70%"/>
<figcaption>
STEP_55B
</figcaption>
</div>

Take one of the two corner parts you have built in the steps 42 to 47 and wire the cable through it as shown:

<div figure-id="fig:WT19-B_STEP_55C">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_55C.png" style="width: 70%"/>
<figcaption>
STEP_55C
</figcaption>
</div>

At this point, take the long vertical tube from the step 13 where you have wired through the camera cable. Put the cables of the LED stripe in the small hole on the side. Make sure to pull out the cables on that end of the tube which is nearer to the small hole (on the bottom side).

<div figure-id="fig:WT19-B_STEP_55D">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_55D.png" style="width: 70%"/>
<figcaption>
STEP_55D
</figcaption>
</div>

Take now the whole bottom part of the watchtower (from step 12). Wire the cables of the LED stripe through the mounting hole of the tube and connect it to the HUT. Make sure to use the exact same pins as shown in figure [](#fig:WT19-B_STEP_55E). Don't forget to wire the camera cable through the bottom parts from step 12 as well.

<div figure-id="fig:WT19-B_STEP_55E">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_55E.png" style="width: 70%"/>
<figcaption>
STEP_55E
</figcaption>
</div>

### Step 56
As the cable is now connected, make sure to put all tubes in their corresponding connection parts as indicated by the red circles in figure [](#fig:WT19-B_STEP_56). Don't use glue here!

<div figure-id="fig:WT19-B_STEP_56">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_56.png" style="width: 70%"/>
<figcaption>
STEP_56
</figcaption>
</div>

### Step 57
Turn around the assembly with the LED stripe and make sure again that the diodes are placed correctly behind their corresponding holes. Maybe adjust the with some more glue.

<div figure-id="fig:WT19-B_STEP_57">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_57.png" style="width: 70%"/>
<figcaption>
STEP_57
</figcaption>
</div>

### Step 58
Turn the part from step 57 back and connect the second horizontal tube (same length) and the second corner part from steps 42 to 47.

<div figure-id="fig:WT19-B_STEP_58">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_58.png" style="width: 70%"/>
<figcaption>
STEP_58
</figcaption>
</div>

### Step 59
Now take the other side of the traffic light stand built in steps 34 to 41 and mount the tube to the corner part.

<div figure-id="fig:WT19-B_STEP_59">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_59.png" style="width: 70%"/>
<figcaption>
STEP_59
</figcaption>
</div>

### Step 60
Figure [](#fig:WT19-B_STEP_60) shows the complete traffic light extension with the watchtower you have assembled so far.

<div figure-id="fig:WT19-B_STEP_60">
<img src="opmanual_autolab/images/watchtower/WT19-B_assembly/STEP_60.png" style="width: 70%"/>
<figcaption>
STEP_60
</figcaption>
</div>

Congratulations, at this point you have completed all the additional parts for the traffic light and you can continue with [step 15](#step_15_WT19B) of the watchtower instructions.
