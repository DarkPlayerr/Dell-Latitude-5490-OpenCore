# DellBookPro

These files are valid for a Dell Latitude E5490. There are some Dell computers with the same specs, such as 7490, who can benefit from this as well. As there are specific tweaks for Dell laptops, you could or could not be able to make it work with other computers wit the same specifications. Previously it was working with Clover, but later I migrated to OpenCore; you can find both attached.

## About Dell E5490

Technical Specs (what is important for us):
- Intel® Core™ i7-8650U (Quad Core, 8M Cache, 1.9GHz)
- Intel® UHD Graphics 620 / HDMI + VGA + Displayport over USBC
- Realtek ALC3246 (ALC256) + headphone jack
- Webcam 720p
- 3x USB 3.1 gen 1 / 1x USBC
- SD Reader
- I2C trackpad + Trackpoint
- ~~Intel Wifi + BT~~ Replaced it by a Dell DW1650

## Clover

I started working with Clover, getting everything working thanks to [this guide at OSXlatitude.com](https://osxlatitude.com/forums/topic/11410-dell-latitude-7490-with-i7-8650u-intel-uhd-620-and-1920x1080-lcd-mojavecatalina/). I kepp it updated, being Clover 5120 the last update and the end of this path. Catalina 10.15.6 is the current last release of MacOS supported by my version of Clover.

### What is working:

- [X] Intel Processor + Sleep + Power Management
- [X] Intel UHD 620 with Metal
- [X] Video output through VGA
- [X] Video output through Displayport over USBC
- [X] Sound though internal speakers
- [X] Sound through headphone jack
- [X] Internal Microphone
- [X] USB ports
- [X] Keyboard + fn keys
- [X] Trackpad
  - PHYSICAL BUTTONS ARE NOT WORKING
- [X] Bluetooth
- [X] Wifi
- [X] Handoff / Continuity / Sidecar
- [X] iMessages / Facetime
- [X] Dual Boot
- [X] MacOS Catalina

### What is not working
- [ ] Sound through headphone jack
- [ ] SD Reader
- [ ] Trackpoint
- [ ] MacOS Big Sur Beta

### What I don't have tested yet
- [ ] Video + audio output though HDMI


## OpenCore

When Big Sur beta was issued, I tried with Clover, but failed to have it running in this computer. I switched from Clover to Opencore using the excellent [Dortania guide](https://dortania.github.io/OpenCore-Install-Guide/), being successfull after some days. From now on, I will be only using OpenCore and updating here on a regular basis.

### What is working:

- [X] Intel Processor + Sleep + Power Management
- [X] Intel UHD 620 with Metal
- [X] Video output through VGA
- [X] Video output through Displayport over USBC
- [X] Sound though internal speakers
- [X] Sound through headphone jack
- [X] Internal Microphone
- [X] USB ports
- [X] Keyboard + fn keys
- [X] Trackpad
- [X] Bluetooth
- [X] Wifi
- [X] Handoff / Continuity / Sidecar
- [X] iMessages / Facetime
- [X] Dual Boot
- [X] MacOS Catalina
- [X] MacOS Big Sur Beta

### What is not working
- [ ] Sound through headphone jack
- [ ] SD Reader
- [ ] Trackpoint


### What I don't have tested yet
- [ ] Video + audio output though HDMI

### What is working:

- [ ] Intel Processor + Sleep + Power Management
- [ ] Intel UHD 620 with Metal
- [ ] Video output through VGA
- [ ] Video + audio output though HDMI
- [ ] Video output through Displayport over USBC
- [ ] Sound though internal speakers
- [ ] Sound through headphone jack
- [ ] Internal Microphone
- [ ] USB ports
- [ ] SD Reader
- [ ] Keyboard + fn keys
- [ ] Trackpoint
- [ ] Trackpad
- [ ] Bluetooth
- [ ] Wifi
- [ ] Handoff / Continuity / Sidecar
- [ ] iMessages / Facetime
- [ ] Dual Boot
- [ ] MacOS Catalina
- [ ] MacOS Big Sur Beta

### What is not working


### What I don't have tested yet


