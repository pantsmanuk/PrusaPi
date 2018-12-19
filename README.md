# PrusaPi

A [CustomPiOS](https://github.com/guysoft/CustomPiOS) variant package that permits building [OctoPi](https://github.com/guysoft/OctoPi) with the changes from the [Prusa3D OctoPi fork](https://github.com/prusa3d/OctoPi): 

* black theme and OctoPrint name change
* IPOnConnect plugin pre-installed
* default printer profile changed to Prusa i3 MK3
* multiple filament pre-heat profiles added

I also change the hostname to **prusapi**; I run multiple OctoPi instances, this helps me. If you want to reverse this change, just modify ```boot/octopi-hostname.txt``` on the burned image.
