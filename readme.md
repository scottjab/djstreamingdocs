# Streaming music on the internet

So you want to stream some sweet music on the internet, but don't want your set to sound like it was recorded on a 
potato underwater? It is possible to stream on the internet without shelling out for a new mixer, or some magic
streaming box. 

This document covers streaming to Facebook and Twitch. (Pull requests welcome for other services.)

## Overview 
Basically you need to get the music from your mixer into a computer and a webcam connected to the computer (this isn't even required).

If you DJ with a controller, just connect it to your damn computer. 

## Mixer to Computer

Getting the sound form your mixer to your computer can happen a few different ways: 

1. [The line/mic in on your computer](#linein)
2. [Using a usb sound card or DAC](#dac)
3. [Just using your mixer's USB port](#mixer)


Most mixers will have an analog line level record output. Usually these are RCA jacks. 

If your mixer doesn't have a record out, it is possible to 


### <a name="linein"></a> Line in / Mic Jack
This is potentially the worst sound of all three options, but is the cheapest. Most computers have a 3.5mm line in port
be careful sometimes this is a mic jack and you may have to adjust levels 

Extra gear: 
Equipment: [RCA to 3.5mm Jack](https://www.amazon.com/AmazonBasics-3-5mm-2-Male-Adapter-Stereo/dp/B01D5H8JW0/)


#### Mac
Unlike the most recent iPhones, Most mac laptops have a combo headphone/line-in/optical jack.
Mac's by default have a line in level port, all you need to connect your mixer's record out to your mac's headphone jack
with the cable linked above. 

#### PC 
PC Laptops generally will have a headphone jack and a microphone jack. If you have a mic jack, your results may vary if
you connect your mixer into the mic port.  Some sound cards can disable the amp on a mic port, but you will have to
consult the documentation for your PC.

### <a name="dac"></a> USB soundcard or DAC
If your mixer does not have a USB port, and connecting the mixer directly to your PC isn't working, you can try using a
USB sound card or DAC (Digital audio converter)

There are tons of these devices on the internet and like all audio gear the price does not always correlate with sound
quality. There are plenty of Audiophile scams out there in this product space. 

Extra gear options: 
[Behringer U-Control UCA202](https://www.amazon.com/Behringer-U-Control-UCA202-Ultra-Low-Interface/dp/B000KW2YEI/) Discontinued, but if you can
find it for cheap this is a good option. 

[StarTech.com 7.1 USB Sound Card ](https://www.amazon.com/StarTech-com-7-1-USB-Sound-Card/dp/B002LM0U2S/)
and cables to match. 

Depending on the DAC you choose, your cable requirements, but just like above, attach record out from mixer into DAC.
Then connect the USB from the DAC to your computer.

### <a name="mixer"></a> Mixer with USB port

Most modern mixers have DACs built in, if your mixer supports sarato it probably has this feature.  If your mixer has a 
USB port anywhere on it, check the manual to see if you can export the main audio.  All of the current generation pionner
mixers, most of the allen and heath, and most rane mixer support this feature.  This will give you the best sound quality.

    If your mixer has a USB port you probably don't need any other gear. 

## Software 
[OBS: Open Broadcaster Software](https://obsproject.com/)

OBS will combine the audio from your mixer and the video from your webcam and encode and stream the data to whichever 
service you want.

Their documentation is very good on this subject: https://obsproject.com/wiki/OBS-Studio-Quickstart

Basically
1. Download and install OBS
2. Configure OBS to use your Webcam as a video source and your mixer as the audio source, depending on which solution
you used above, your mixer could be ether the default line in audio device on your computer, or a USB source.
3. In the settings of OBS there is a "stream" section, select the platform you want to stream to and add your Stream key.
4. Click stream. If you have no errors it is time to party.
5. Click record. 
6. Go live on service.
7. Play Party Jams.

## Other shit.

### What is my freaking stream key?
FB: https://www.facebook.com/live/create Then click create live stream the stream key should be on the next page.

Twitch: Log in to Twitch -> Click on your username in the upper right -> settings -> channel -> Primary stream key

### Why did those jerks mute me?!
No they don't hate your music, no the "man" isn't out to get you.  The fact is the RIAA is still quite litigious when it
comes to protecting rights online, laws like the DMCA have forced tech companies to auto moderate content on
their platforms.  When you get muted it is because a portion of the song you are playing matches copyrighted content. 
These services are basically running shazam in real time against the stream if something matches they mute you. 
 
Basic rule of thumb to not get muted or copyright strikes is:

    If you can shazam it, don't play it. 