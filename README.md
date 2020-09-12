# kiss-kernel

A KISS Linux repo that contains kernel sources and compilation scripts (optional).

## What's this?

KISS Linux is a Linux distro that, ironically, does not officially supply the Linux kernel in its (very versatile) package manager.  I really like the way that Gentoo supplies its kernel with binaries and sources, so I thought to make my own repo for this.

## How do I use this?

You install this repo by downloading it in anywhere accessible, add the path of the repo to KISS_PATH, and install one (or more than one!) kernel(s) below.

## What is the difference between sources and a binary

With both sources and binary the source is compiled.  The binaries are not precompiled, but instead compiled in the build script.  The source packages just download the sources to /usr/bin.  The configuration in the binary packages is created with "make defconfig".

## Kernels available

- linux-source (currently 5.8.9)
- linux-bin (currently 5.8.9)
