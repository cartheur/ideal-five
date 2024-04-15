## Getting started with a fresh computer

As it will become necessary at any time to format a fresh computer for a myriad of perceived tasks, there is a baseline machine that should be created. In 2019, these were coalesced into _animals full steps_, which was a way to contain the complexities of bringing-online a _chip_ computer. Although these are defunct and not interesting to reconstitute, any Debian system should be brought into scope in the same fashion.

### Raspberry Pi 4 or 5

Although the final product will be in `an undisclosed mention`, dotnet sdk is handy to ensure compatibility in the transition phase. Therefore, on the pi, this [site](https://www.petecodes.co.uk/install-and-use-microsoft-dot-net-8-with-the-raspberry-pi/) gets one started.

The Pi-4 is neat as a battery hat from Waveshare makes it self-contained. The Pi-5 is highly-advanced and very fast. In either case use the Pi Imager program to burn a Debian Bookworm image onto an industrial-grade 32GB SD card. Then, once allowing the Pi to prepare and have it ready for run, use the `sudo` account to update and upgrade the OS. Now it is ready for preparation. Wifi will _not_ be utilized as a contention is the computer should not intentionally be made vulnerable. Use an ethernet cable instead. A USB soundcard with a speaker and microphone-pair is a nice-to-have but still rounds-out the use-case. Once these criteria are met, prepare it for its computational tasks.

`sudo apt install alsa-utils autoconf automake bison build-essential espeak gcc git libasound2-dev libtool mplayer`

