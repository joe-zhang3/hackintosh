# EFI for Big Sur 

## Build Info

OpenCore: 0.6.4
CPU: AMD Ryzen 7 5800X
GPU: Sapphire RX 5700XT 8G
Motherboard: MSI B550M mortar (Bios version: 7C94v14)
RAM: GSkill TridentZ RGB DDR4-3200 16GB
OS: macOS Big Sur
Wifi/Bluetooth: Broadcom BCM943602CS combo

## Notes

1. Make sure the 'Above 4G XXX' in the bios is turned on, as I am not using the `npci=0x2000` in `boot-args`. Even I don't know the difference between these two options. 
2. Fill values under `Platform Info` with yours. 
3. `USBPorts.kext` is not mandatory, 


## Problems left.

1. Seems like the bluetooth signal is not very well, connection of my bluetooth keyboard sometimes get lost. Other device like Airpords is working well. 
2. Handoff is still not work. Aiddrops works. Still trying to figur it out. 



