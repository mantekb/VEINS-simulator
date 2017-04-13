# VEINS-simulator
1. Install Omnet++ and SUMO.
2. Download VEINS project files.
3. Import the VEINS project in Omnet++ IDE.
4. There will be a VEINS project under samples.
5. Make changes to the Omnetpp.ini file.
6. This simulation was run for 200s with a new node appearing after every 3 seconds. There was 1 accident simulated at the 50s mark and it lasted for 30s.
7. After making the changes, run the following command in mingwenv cmd which is present in your Omnet++ package:
/c/Users/user/src/veins-4.5/Sumo-launchd.py -vv -c /c/Users/user/src/sumo-0.29.0/bin/sumo.exe
8. Now the simulation can be run by right clicking on the omnetpp.ini file and running it as an omnet++ simulation.
