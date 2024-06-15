# Nébuleuse Linux
Nébuleuse Linux is a small GNU/Linux distro made with Buildroot. This repository contains a modified Buildroot 2024.5 source.

## Included programs
Nébuleuse 2024.5 contains these programs:
* Bash 5.2
* Linux 6.8
* GLibC 2.39
* Busybox 1.36.1
* DBus 1.14.10
* DiffUtils 3.10
* Git
* Grep
* SystemD 253
* TMux
* Util-Linux

(this list surely doesn't contains all the programs included.)

## How to build?
The .defconfig file in the repo root already contains the modified configuration. Just run `make defconfig`, and then `make` (PSSS: you can use multiple cores for parralel building by using -j followed by the core count). You may also copy the provided linux-X.X.X-config file to output/build/linux-X.X.X

Or, if you are too lazy / you wanna use your PC / your PC is a potato, you can download prebuilt Nébuleuse images in the Releases section.

## System requirements
* Memory: You may calculate the required memory by using this: kernel size (in a unit) + initrd size (in the same unit), plus some memory for the runtime data.
