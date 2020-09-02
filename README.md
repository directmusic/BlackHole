This is a custom modification of BlackHole for my own private use.

It clips the output at 0db as well as removing the ability to change the volume in reality while still being able to tell the system to read it.

## These are the modifications I made:


`*ringSample += *ioSample * gVolume_Output_Master_Value * gVolume_Input_Master_Value;`

to 

`*ringSample += *ioSample;`

and

`#define NUMBER_OF_CHANNELS 2`

I enocourage you to support the individual who made the original software:
[Blackhole on GitHub](https://github.com/ExistentialAudio/BlackHole)
