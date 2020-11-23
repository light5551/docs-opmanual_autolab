# Watchtower Initialization {#watchtower-initialization status=ready}

<div class='requirements' markdown="1">

Requires: An SD card of size at least 32 GB.

Requires: A computer with a **Ubuntu OS** (for flashing the SD card), an internet connection, an SD card reader, and 16 GB of free space.

Requires: Duckietown Shell, Docker, etc, as configured in [](+opmanual_duckiebot#laptop-setup).

Requires: Duckietown Token set up as in [](+opmanual_duckiebot#dt-account).


Results: A ready watchtower

Next Steps: [Place the Watchtower in the city](#localization-watchtower-placement).
</div>


## Flashing the SD card

The image setup procedure for Watchtowers is the same as for Duckiebots. In the Autolab, you should use the naming convention:

* hostname: **watchtowerXX** (where XX specify the number of the Watchtower)

Note: Do **not** change the linux-username and password, the flashing procedure using `dts` will give it the default login credentials found [here](+opmanual_duckiebot#setup-duckiebot). Also make sure you are using the `daffy` version of the shell.

Note: Please add `--type watchtower` to the flashing procedure

A complete command will look like:

    laptop $ dts init_sd_card --hostname watchtower![XX] --country ![COUNTRY] --type watchtower

Using the above naming conventions, you can flash your SD cards as is described in [Duckiebot Initialization](+opmanual_duckiebot#setup-duckiebot).


## Calibrating the camera

Using the instruction in [](+opmanual_duckiebot#camera-calib), you should do only the intrinsic calibration for the Watchtowers.

Note: Be sure to check the quality of the image. It should be (1296x972) and not (480*640) like on the Autobots. If it is not, this means you didnt flash the Watchtower with the `--type watchtower` argument. To solve this, reflash it.
