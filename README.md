# mjambon-opam-repo

Opam package definitions for various experimental projects
hosted on by @mjambon.

## Package list

https://github.com/mjambon/mjambon-opam-repo/tree/master/packages

## Installing a package

To install one of the packages listed above, first add the repository
to [opam](https://opam.ocaml.org/opam):

```
$ opam remote add -k git mjambon https://github.com/mjambon/mjambon-opam-repo
```

Now `opam` can be used to install packages and their dependencies:

```
$ opam install moving-percentile
```
