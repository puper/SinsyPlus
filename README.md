# SinsyPlus
Singing Voice Synthesis System based on Sinsy

My grandfather's clock (Japanese):
<audio controls="controls">
  <source src="https://raw.githubusercontent.com/740291272/Sinsy-NG/demo/demo/e.wav" type="audio/wav" />
Please to <a href="http://gloomyghost.com/SinsyPlus/">project</a> page listen the demo!
</audio>


This script relies on the sinsy.jp website from the Nagoya Institute of Technology which implements a HMM-based Singing Voice Synthesis System.

```bash
The HMM/DNN-Based Singing Voice Syntheis System "SinsyPlus"
Version 0.0.1 (https://github.com/740291272/SinsyPlus)
Copyright (C)2009-2018 Nagoya Institute of Technology
Copyright (C)2017-2018 GloomyGhost
All rights reserved

Usage:
        SinsyPlus [infile] [Language]
                Language:
                        Japanese:ja
                        Chinese :ch
                        English :ja
        Example : sinsyplus voice.xml ja

```

## Requirements
- musescore
- curl
- numpy
- matplotlib
- requests
- scipy	
- urllib

## For Windows User:
Windows Version Download:

https://pan.baidu.com/s/1ivBxM5hYoXzNdgfAANqTIg

## For Unix User 
You need to download curl before running.
```bash
sudo apt-get install curl
```
## Reference:
https://github.com/mathigatti/midi2voice
