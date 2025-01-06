# DEKTeX
minimalistic TeX engines, with a WEB change file from TeX-fpc slightly modified to make it multiplatform.

At this point, some old executables ported to DOS386 (djgpp cross-compiled: requires cwsdpmi.exe to run on 386), Win32 (native), and Linux 386 (may run on Windows's C:\ drive with flinux typing `flinux initex32`) are provided in the `archive` branch: the web change files should work with any current FreePascalCompiler.

# BUGS

Wolfgang Helbig's specific code for *nix on [TeX-fpc](https://www.ctan.org/pkg/tex-fpc) has been disabled: Edit and Ctrl-D directives do not work at the moment.

These executables are highly experimental: try at your own risk.

# TODO

* Add a suitable (and as ancient) DVI driver; Andy Clark's [dvitops](https://www.ctan.org/pkg/dvitops) is the target of choice.
* Maybe work on a port of Metafont, to give the full experience of Lore.
