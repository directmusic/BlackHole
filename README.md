This is a custom modification of BlackHole for my own private use.

It clips the output at 0db as well as removing the ability to change the volume in reality while still being able to tell the system to read it.

## These are the modifications I made:


'*ringSample += *ioSample * gVolume_Output_Master_Value * gVolume_Input_Master_Value;'

to 

'*ringSample += *ioSample;'

and

'#define NUMBER_OF_CHANNELS 2'

I enocourage you to support the individual who made the original software:


![Platform:macOS](https://img.shields.io/badge/platform-macOS-lightgrey)
![GitHub](https://img.shields.io/github/v/release/ExistentialAudio/BlackHole)
[![GitHub](https://img.shields.io/github/license/ExistentialAudio/BlackHole)](LICENSE)
[![Build Status](https://travis-ci.com/ExistentialAudio/BlackHole.svg?branch=master)](https://travis-ci.com/ExistentialAudio/BlackHole) [![Twitter](https://img.shields.io/badge/Follow%20on%20Twitter-1da1f2)](https://twitter.com/ExistentialAI)
[![Facebook](https://img.shields.io/badge/Like%20on%20Facebook-4267B2)](https://www.facebook.com/Existential-Audio-103423234434751)
