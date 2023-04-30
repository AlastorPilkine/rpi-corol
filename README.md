# rpi-corol
rpi-corol is a shell script that will commit (clone using rsync) the current root partition, referred as 'active partition', to a second one, referred as 'inactive partition', on the same SD card of a running Raspberry Pi.
rpi-corol will rollback the entire root partition by changing the booting root partition in system files. So, after a reboot, the entire system is turned back to the previously commit state.

I used this script while testing software on a Raspberry Pi, with the ability to easily get back to a clean and running system.
.