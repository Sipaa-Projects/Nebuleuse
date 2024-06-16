<p align="center">
  <img src="nebuleuse.png" height="96" />

</p>

Nébuleuse Linux is a small GNU/Linux distro made with Buildroot. This repository contains a modified Buildroot 2024.5 source.

## Included programs
Nébuleuse 2024.5 contains these programs:
* Bash 5.2
* Linux 6.9.3 (Configuration based on Arch's kernel)
* GLibC 2.39
* Busybox 1.36.1
* DBus 1.14.10
* DiffUtils 3.10
* Git
* Grep
* SystemD 254
* TMux
* Util-Linux

(this list surely doesn't contains all the programs included.)

## How to build?
Run `make defconfig` and `make` (you can use multiple cores with -J)
Or, if you are too lazy / you wanna use your PC / your PC is a potato, you can download prebuilt Nébuleuse images in the Releases section.

## System requirements
* Memory: 512mb