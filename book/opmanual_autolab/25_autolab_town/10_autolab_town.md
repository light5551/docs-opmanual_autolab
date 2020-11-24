# BUILD - The Autolab town {#autolab-town-init status=ready}

<div class='requirements' markdown="1">

Requires: An SD card of size at least 32 GB.

Requires: A computer with a **Ubuntu OS** (for flashing the SD card), an internet connection, an SD card reader, and 16 GB of free space.

Requires: Duckietown Shell, Docker, etc, as configured in [](+opmanual_duckiebot#laptop-setup).

Requires: Duckietown Token set up as in [](+opmanual_duckiebot#dt-account).

Results: The ready to use town device.

</div>


Warning: this part is under development, ignore for now


## Flashing the town device

The Duckietown or town used in the Autolab is a Raspberry Pi 4 without any actuators or sensors. The image setup procedure for Duckietowns is similar as for Duckiebots. Please add `--type duckietown` to the flashing procedure. In the Autolab, you should use the naming convention:

* hostname: **duckietownXX** (with XX starting from 01)

Note: Do **not** change the linux-username and password, the flashing procedure using `dts` will give it the default login credentials found [here](+opmanual_duckiebot#setup-duckiebot). Also make sure you are using the `daffy` version of the shell.

A complete command will look like:

    laptop $ dts init_sd_card --hostname duckietown![XX] --country ![COUNTRY] --type duckietown

Using the above naming conventions, you can flash your SD cards as is described in [Duckiebot Initialization](+opmanual_duckiebot#setup-duckiebot). Once the device is flashed, you can opt to either power it using Power over Ethernet (PoE) or directly plug it into a battery.
