# GPSpoof
Python wrapper for gps-sdr-sim

## What is it
GPSPOOF is a python script with the purpose of helping set up the environment for gps-sdr-sim and hackrf_transfer tools.

## What it does
* Download and compile gps-sdr-sim if not present in the same directory
* Download the updated brdc file from NASA's FTP
* Compile gpssim.bin based on user's settings
* Run hackrf_transfer using the compiled gpssim.bin
* Make you happy using colors :)

## TO-DO
* [ ] Add support for movement
