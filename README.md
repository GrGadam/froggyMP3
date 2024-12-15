# froggyMP3

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# How to build (SF2000)

## I. Set up your development environment
### Follow the guide here: 
[SF2000 Multicore](https://github.com/madcock/sf2000_multicore?tab=readme-ov-file#setup-before-building)

## II. Get the source code
Clone this project inside the `sf2000_multicore/cores/` folder.
Command:
```
git clone https://github.com/GrGadam/froggyMP3.git --recurse-submodules
```

## III. Build the core
In the `sf2000_multicore` folder use the following command:
``` 
make CONSOLE=froggymp3 CORE=cores/froggyMP3
``` 
After this, the built core should be under `sf2000_multicore/sdcard/cores/froggyMP3`
First time, you can move the whole folder on to your sf2000 (which must have multicore installed) in the cores folder (like: /cores/froggymp3)
After that, you need to copy your `.mp3` files to your sf2000 `CORES/froggymp3/`. (If the folder doesn't exist first, you can just create a new folder and name it froggymp3).
