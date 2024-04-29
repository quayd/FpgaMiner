# FPGA Miner Gram
Latest is v2.0.11

## Troubeshooting
### Device/Bitstream not found/recognized on Linux
```
sudo rmmod ftdi_sio
sudo rmmod usbserial
sudo ./FPGAMinerGram...
```
### sqrl_bridge
If your device uses sqrl_bridge, currently there is only support on Linux.

### Watchdog Timeout and Disconnects
Use the ```-w``` option to set a longer timeout 

### Exits when pool disconnects
Use the ```-r``` option to set how many retries or -1 for infinite

