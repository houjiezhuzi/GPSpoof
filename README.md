# GPSpoof
Python wrapper for gps-sdr-sim

## What it is
GPSPOOF is a python script with the purpose of helping set up the environment for gps-sdr-sim and hackrf_transfer tools.

## Why
At first, when working with gps-sdr-sim I found it really difficult to understand what files where needed and why it did not work sometimes (NASA FTP is pretty messy actually) so I had to write my own script to aid in the process. Talking with some pals of mine it seemed like I was not the only one having troubles with the tools, so I decided to release this wrapper.

## What's needed
* Python 3
* Internet connection

## Usage
```
git clone https://github.com/last-byte/GPSpoof.git
cd ./GPSpoof
./gpspoof
```
From there on follow the instructions in the script.

## What it does
* Download and compile gps-sdr-sim if not present in the same directory
* Download the updated brdc file from NASA's FTP
* Compile gpssim.bin based on user's settings
* Run hackrf_transfer using the compiled gpssim.bin
* Make you happy using colors :)

## TO-DO
* [ ] Add support for movement
