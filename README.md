# Pacm Recipes

A repository of recipes that are used in the `pacm` 
package manager https://github.com/vishen/pacm.

## Variables

The following variables are available at runtime depending
on where `pacm` is being run from. 

- {{ .Version }}: version specified in package
- {{ .OS }}: darwin, linux, dragonfly, freebsd, openbsd, solaris, netbsd
- {{ .Arch }}: 368, amd64, arm, arm64, ppc64
- {{ .OSAlt }}: osx
- {{ .ArchAlt }}: x86_64, x86_32
