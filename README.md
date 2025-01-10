# TeX82lab
minimalistic TeX engines and tools.

This "distro" (or rather, "family of distros", if they deserve that name) are experiments in retrocomputing, providing change and source files for simple, primitive implementations of (Classic|DEK)TeX82. 

As such, the `TeX`es produced with these sources are unable to run `LaTeX2e+`, which now requires `eTeX`, but may run several `Plain` based macros.

Some old executables ported to DOS386 (djgpp cross-compiled: requires cwsdpmi.exe to run on DOS386; may run on other platforms with DOSBox or other emulators), Win32 (native), and Linux 386 (may run on Windows's C:\ drive with flinux typing `flinux initex32`, or the WINE compatibility layer) are provided in the `archive` branch for immediate evaluation. 

The web change files in the `TeX-fpc` and `isoTeX` branches should work with any current FreePascalCompiler. See notes in the subdirectories in `main`.

Some `dvi` drivers and other tools shall be provided in due course in a `dviware` branch.

# BUGS and CAVEATS

All these sources, and their respective executables, are highly experimental: try at your own risk.

* Specific notes are provided in the branches and/or folders in the main branch.
