# CS:GO Cheat Guide For Linux

## Table of contents

- [Quick Start](#quick-start)
- [What's Included]($whats-included)
- [Cheats](#cheats)
- [Compilation](#compilation)
- [How To](#how-to)
- [Contributing](#contributing)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)

## Quick Start

- Launch Steam
- Drag the files from the [Scripts](https://github.com/firaenv/CS-GO-Cheat-Guide-Linux/tree/master/Scripts) into a folder
- Launch CS:GO
- run ./load and once injected
- Press `Insert` and there you go!

## What's included

I included a pre compiled version of [Osiris](https://github.com/danielkrupinski/Osiris).

## Cheats

The Cheat used is listed above, but there are many other great ones.

## Compilation

- Install Deps:
```console
$ sudo apt-get update && sudo apt-get install -y libsdl2-dev gcc-10 g++-10
```
- Compile it:
```console
$ mkdir Release && cd Release && cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_C_COMPILER=gcc-10 -D CMAKE_CXX_COMPILER=g++-10 ..
```
- Make it:
```console
$ make -j $(nproc --all)
```


## How To

Simpily Run the ./load script when CS:GO is loaded.

If you get errors, make sure you ran:
```console
$ chmod +x ./load.sh
```
## Contributing

Contributing is welcome in anyway.  If I managed to miss something, make sure to create a Pull Request or let me know in Issues.

## Creators
- Jack Boecker <boeckerjack@protonmail.com>

## Thanks
- [Daniel Krupiński](https://github.com/danielkrupinski)
- [Osiris](https://github.com/danielkrupinski/Osiris)

## Copyright and license
This project is protected under the GNU Public License Agreement.  Check the LICENSE file for more info.
