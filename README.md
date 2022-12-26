This is the repository for the African Grey painting with playable sound effects! Originally a Christmas gift for my mom, I wanted a way for her to be reminded of memories from the kitchen of our late family bird with a beautiful image for the wall. Painted by [Gabriella Kostadinova](https://www.gabrielakostadinova.com/), the painting frame contains 3 buttons which play precious sound files that trigger our bird's most popular sayings.

#### The Arduino FX board has trigger pins and internal memory for sound bites, so this also doesn't need any code. There is a sketch included which allows serial communciation with the board to have more control over sound files and playback. A future version of the circuit may use a wifi module to listen to the network and trigger sounds from a routine.  

![](https://github.com/Jshulgach/SoundFX-Painting/blob/main/resources/20221225_134808.jpg)

## List of Parts:
<a name="parts"/>

   + [Arduino FX board](https://www.adafruit.com/product/2341)
   + [LiPo battery 2000mAh](https://www.adafruit.com/product/2011)
   + [5V LiPo rechargable power boost](https://www.adafruit.com/product/2465)
   + [Mono speaker 3W 4ohm](https://www.adafruit.com/product/3351)
   + [Buttons](https://www.adafruit.com/product/367)
   + [Toggle switch](https://www.amazon.com/Nilight-90013L-Toggle-Control-Warranty/dp/B07T1JG6BD/ref=sr_1_2_sspa?crid=243ILAD6JQ1RE&keywords=toggle+switch&qid=1672037322&sprefix=toggleswitch%2Caps%2C82&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyTEUySlMyOEIxUFdCJmVuY3J5cHRlZElkPUEwNTA2NDkwMlZKVUpVS05GVkZaWiZlbmNyeXB0ZWRBZElkPUEwNjcwODE0MVdLQlNVNlRBM0tPTyZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=)

## Building:
<a name="building"/>

1. The circuit can be taped/glues/fused to the back of any picture or frame. A painting canvas was used since the circuit could be easily tucked behind and glued 
   + A prototyping solder board was also used to reduce the wiring between the different breakout modules.
   + The toggle switch and buttons can have wires soldered for a stronger connection

## Wiring:
<a name="wiring"/>

There is a [wiring diagram](https://github.com/Jshulgach/SoundFX-Painting/blob/main/resources/Arduino%20Circuit.png) which explains all the connections for the circuit to control triggered sound bites. There are 3 buttons connected to trigger pins, and 2 buttons connected to volume control.




