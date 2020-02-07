Use a dvb-t tuner card to scan the configured rf frequencies and create a
summary of the avilable TV channels.

Example Usage:

    apt-get install -y dvb-tools dvbsnoop
    cd melbourne
    ../autoscan
    less *.summary
