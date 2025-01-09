This implementation of TeX is a small fork from Wolfgang Helbig's [TeX-fpc](https://ctan.org/pkg/tex-fpc) port for Unix, having removed the Unix specific code dependencies to make it portable: `dek.ch` provides a change file suitable to compile a portable TeX executable, while `njk.ch` shall provide one for `metafont` in due course. Diff files are also provided, to show in a glance the small changes applied.

The rest of the installation is left as Helbig prescribes.
