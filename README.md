## Linux-ARM-embedded-tackle, the meta-etackle
####Tackle for embedded Linux on ARM, targetting card size embedded SBCc and different add-on boards with an unitary image build.

The project is using the Yocto build system and very recent versions of the Linux kernel and integrates so far the Raspberry Pi and the BeagleBone Black  single board computers.

The add-on boards are ranging from A/D and D/A converters to RTCs and integrated sensors for temperature, acceleration and IR.

The initial setup was optimized for user friendliness and speed with the goal to produce an useful booting image for the targetted board from the beginning, then allowing the integration of custom hardware easily. Because of Yocto, adding support for other peripherals is very much simplified, using already defined recipes or generating new recipes using existing ones as a template.
