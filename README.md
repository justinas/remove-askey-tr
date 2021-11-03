# Remove `/system/bin/askey_tr` from your Dynalink 4K box

This removes `/system/bin/askey_tr`, a shady "remote management" binary
that automatically runs as root.
([more info here](https://forum.xda-developers.com/t/shady-process-in-my-dynalink-4k-box-possible-backdoor.4356491/)).

There could be other backdoors in the stock firmware.
This is not intended to be a way to get rid of them all.
I recommend at least using a
[custom ROM](https://forum.xda-developers.com/t/unofficial-lineageos-18-1-for-amlogic-g12-sm1-family-devices.4313743/)
if its feature set satisfies your needs.

I've only tested this on my Dynalink 4K Box, rooted stock ROM.

To install, simply zip up this repo's contents and use Magisk Manager to install.

**Disclaimer**: I don't know what I'm doing. This is my first time creating a Magisk module.
You might brick your device. Good luck.
