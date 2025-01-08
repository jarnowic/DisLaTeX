# DisLaTeX
minimalistic TeX engines and tools.

This "distro" (if it deserves that name) is an experiment in retrocomputing, providing change and source files for simple, primitive implementations of (Classic|DEK)TeX82. 

As such, the `TeX`es produced with these sources are unable to run `LaTeX2e+`, but may run several `Plain` based macros.

At this point, some old executables ported to DOS386 (djgpp cross-compiled: requires cwsdpmi.exe to run on 386), Win32 (native), and Linux 386 (may run on Windows's C:\ drive with flinux typing `flinux initex32`) are provided in the `archive` branch. 

The web change files in the `TeX-fpc` and `isoTeX` branches should work with any current FreePascalCompiler. 

Some `dvi` drivers and other tools shall be provided shortly in a `dviware` branch.

# BUGS and CAVEATS

All these sources, and their respective executables, are highly experimental: try at your own risk.

* Specific notes are provided in the branches and/or folders in the main branch.
