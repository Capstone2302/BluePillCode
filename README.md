# BluePillCode
Code for the BluePill that is gonna be used to handle the encoder. The current set up is using an ST-Link V2 plugged in via this tutorial:https://community.platformio.org/t/how-to-flash-a-blue-pill-with-an-st-link/20759

It is important to note that we do not have an actual bluepill, it is a 'knock off' so to speak and requires the suppression of the ID flag: upload_flags = -c set CPUTAPID 0x2ba01477

