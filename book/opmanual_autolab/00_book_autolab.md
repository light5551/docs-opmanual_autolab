# The Autolab {#book:book status=ready}

<div class='requirements' markdown="1">

Requires: A fully operational [Duckietown](+opmanual_duckietown#book).

Results: A working Autolab.

</div>

Warning: this book is under complete review, only use if you are currently involved with Autolab development or AIDO.

<minitoc/>


### Prerequisite recommendation {#dt-env-developer nonumber notoc}

If you are building an Autolab, you are a committed developer of Duckietown. We strongly recommend using **Ubuntu 20.04**. To set up the computer, follow the instructions [here](+opmanual_duckiebot#laptop-setup).

We suggest that your workflow for software should follow the standard one, using [ `dt-env-developer` ](https://github.com/duckietown/dt-env-developer). This is a meta repository that aggregates, with the myrepos tool, the different repositories of code that developers use daily. To set it up, follow the [README instructions](https://github.com/duckietown/dt-env-developer). The rest of this book will assume that you set it up this way, but you could also clone each individual repository on its own and use it as usual.

### The Big Picture {nonumber notoc}

The goal of an Autolab is to create a human free, automated environment for Duckiebots. This requires a bit more than just a standard [Duckietown](+opmanual_duckietown#book) to work. An Autolab can serve different purposes. It is used for research on the Duckietown platform, and is also being used to organize the embodied challenges of [AIDO]((+AIDO#book)).

The aim of this book is to present:

- a set of instructions (labeled **BUILD**) on how to build an Autolab to current specifications
- a set of instructions (labeled **DEMO**) on how to run the Autolab functions or demos
- a set of guides (labeled **SW**) to the different pieces of software that are used and are under development

### Section overview {nonumber notoc}

In each of the following sections you will find the BUILD, the DEMO and the SW pages. You can find the up-to-date status of each page of the book at the top-right of the page, that will change as we write them down. Please only refer to those marked as either BETA or READY.

- [](#autolab-definition) : The precise definition of an Autolab
- [](#autobot-specs) : The set of instructions to setup your fleet of dedicated Duckiebots
- [](#apriltag-specs) : The set of instructions to upgrade your city layout to that of an Autolab
- [](#autolab-map) : The set of instructions to create a precise virtual map of your Autolab
- [](#autolab-town) : The set of instructions to set up your central Duckietown device
- [](#watchtower-hardware) : The set of instructions explaining the set-up of the watchtower devices
- [](#autolab-localization) : The set of instructions to set up and operate the localization system
- [](#autolab-operation-manual) : The control interface for operating the Autolab and AIDO submissions
