# PrusaPi

A [guysoft/CustomPiOS](https://github.com/guysoft/CustomPiOS) variant package that modifies [OctoPi](https://github.com/guysoft/OctoPi) 0.16.0 ([OctoPrint](https://github.com/foosel/OctoPrint) 1.3.10) with the changes from the [Prusa3D OctoPrint fork](https://github.com/prusa3d/OctoPi) applied: 

* black theme and OctoPrint name change
* IPOnConnect plugin pre-installed
* default printer profile changed to Prusa i3 MK3
* multiple filament pre-heat profiles added

I also change the hostname to **prusapi**; I run multiple OctoPi instances, this helps me. If you want to reverse this change, just modify:
```boot/octopi-hostname.txt```

*Since @guysoft has not released OctoPi 0.16.0, this should be considered beta and not used in production.*
