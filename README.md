# DEKTeX
minimalistic TeX engines, with DEK's sources slightly modified to make it multiplatform

At this point, only the executables ported to DOS386 (djgpp cross-compiled: requires cwsdpmi.exe to run on 386), Win32 (native), and Linux 386 (may run on Windows's C:\ drive with flinux typing `flinux initex32`) are provided: web sources should follow if I can sort them out in this lab's mess.

# BUGS

Wolfgang Helbig's specific code for Linux on [TeX-fpc](https://www.ctan.org/pkg/tex-fpc) has been disabled: Edit and Ctrl-D directives do not work at the moment.

These executables are highly experimental: try at your own risk.

# TODO

* Add a suitable (and as ancient) DVI driver; Andy Clark's [dvitops](https://www.ctan.org/pkg/dvitops) is the target of choice.
* Provide basic recursive path search for these ports, in Pascal again; Peter Breitenlohner's [DOStp](https://www.ctan.org/tex-archive/systems/msdos/dostp22) unit looks suitable.
   
