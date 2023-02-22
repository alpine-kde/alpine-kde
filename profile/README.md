# Alpine live (kde edition)
Alpine linux live for laptop devices.

## Download:
https://github.com/alpine-kde/teaiso/releases/tag/latest

## Features
* Live iso (created by teaiso)
* Low power usage (optimize for laptops)
* Btrfs support (powered by 17g)
* Lite kde desktop environment

## Known bugs:
* Automatic installation with 17g is broken
* ext4 filesystem require disable metadata_csum feature
    (You can use `mkfs.ext4 -O ^metadata_csum /dev/xxx` for format partition)
* wayland keyboard settings missing
