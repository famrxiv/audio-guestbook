# audio-guestbook
The audio guestbook is a converted telephone handset that guests can use to leave recorded messages at weddings, parties and other events, as sold by companies such as "After the Tone", "Fête Fone", "Life on Record", "At the Beep", and others.

Watch the full step-by-step tutorial on how to use the code here to build your own at https://youtu.be/dI6ielrP1SE

**Modifications by DD4WH, August 1st, 2022:**
* recordings are now saved as WAV files
* recordings on the SD card can be accessed via USB, no more need to take out the SD card
* code modifications for a telephone with closing contact as the handheld is being lifted
* playback only plays the very last recorded file, not ALL the files ever recorded
* does not play the greeting message again when you want to listen to your recordings
* some bugfixes and warnings eliminated
* do not forget that your greeting message has to be recorded as a wav with a sample rate of 44.1ksps, otherwise it is not played
* compile the code with CPU speed 150MHz, this can save a lot of battery power (reduction by about 70%)

**DD4WH hardware:**
* telephone model "POST FeTAp 611-2a", built about 1972
* Teensy 4.0
* Audio Board for Teensy 4
* AOM5024 electret low noise microphone capsule (the original mic capsule was thrown away)
* push button with red knob
* microUSB to USB-A cable 
* shielded microphone cable


![](https://github.com/DD4WH/audio-guestbook/blob/main/DD4WH_Audio_guest_book_611.jpg)


![](https://github.com/playfultechnology/audio-guestbook/raw/main/thumbnail.jpg)

![](https://raw.githubusercontent.com/playfultechnology/audio-guestbook/main/AudioGuestbook_bb.jpg)
