# Hiveos Common Errors

**0% FAN SPEEDS / FAN ERRORS IN GENERAL**
- The fans don't really spinning
- GPU RPM sensor is offline / disconnected
- GPU overclocking is too aggressive (usually the case), try a lower OC and test
 
**AMD SETTINGS APPLIED WITH ERRORS**
- Check the OC of the gpu that is giving the error
- The Riser's USB cable may be faulty or poorly adjusted
- Check the integrity of the Riser, try to replace with another

**AUTOFAN: UNABLE TO SET FAN SPEED, REBOOTING**
- Do a test, putting the FAN at 100% directly in the Overclock tab and lower your OC a little, if the problem does not occur, the gpu is overheating
- Change the riser slot of the motherboard to see if the problem goes away

**GPU DEAD / GPU HUNG**
- AMD: gradually increase gpu core voltage
- Nvidia: Increase the PL of the board a bit if you are limiting the gpu power with the PL
- Nvidia: Check Core Clock OC

**GPU DRIVER ERRORS, NO TEMPS**
A very common problem that can occur and can be caused by:
- The Riser USB cable may be faulty or poorly adjusted.
- Poor contact of the gpu in the video card seated in the front of riser (it rises in front of the slot making poor contact)
- Check your GPU/Riser/Power Cable connections
- Incorrect overclocking OC.

**GPU HAS FALLEN OFF THE BUS**
- Check gpu energy power supply
- Check if the power cables are intact, if none are brittle, with a bent terminal
- Correctly dimension the power supply

**GPU TEMPERATURE 511 IS UNREAL, DRIVER ERROR**
A very common problem that can occur and can be caused by:
- Check the overclocking of the GPU(s) that have the error
- Faulty or poorly adjusted USB riser cable
- Video card poorly seated on the front (it rises in front of the slot making poor contact)
- Check your GPU/Riser/Power Cable connections

**NVIDIA SETTINGS APPLIED WITH ERRORS**
- Check the OC of the gpus if they are with acceptable values for the gpu model
- Change the miner to test, if it works, try to go back to the error miner and use a different version than the current one
 
**NVML CAN GET GPU …… ERROR CODE 15**
- Try reducing the Core Clock of the card and if the card is limited by PL, reduce the PL of the card a bit
- Check if the power cables are intact, if none are brittle, with a bent terminal

**ERROR: CONNECTION TO API SERVER FAILED**
- Use the 'net-test' command to test your connection
- Try to ping "ping 8.8.8.8" (Google server), if not responding, network problem (No connection)
- Try to ping the hive server hiveos.farm to verify that the hive server is reachable

**ILLEGAL MEMORY ACCESS ERRORS**
- Typically caused by overly aggressive memory clock settings.

**STALE/INVALID SHARES**
- Check your internet network, restart the router, try a public DNS;
- Avoid WiFi, which is not as stable or reliable as a wired network connection;
- Invalid shares can also be caused by bad OCs. Check if the OC is correct;
- In some cases, switching to another miner can solve

**FILE-SYSTEM IS READ-ONLY**
- Reboot the system, if it continues, remake the boot disk. If the error persists, change the flash drive/hd/ssd.

**[DRM:AMDGPU_IB_RING_TESTS] ERROR AMDGPU**\
If you get messages like this when starting your Hive OS, check your riser (the part that fits on the motherboard).\
An malfunction causes this message.\
[drm:amdgpu_ib_ring_tests] *ERROR* amdgpu: failed IB test on ring 1 (-110)\
[drm:amdgpu_vce_ring_test_ib] *ERROR* amdgpu: IB test timed out.
