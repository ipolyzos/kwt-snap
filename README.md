# Kwt - Snap

 Snap package for Kubernetes Workstation Tools (kwt) CLI. 

 _kwt_ provides helpful set of commands for application developers to develop applications with Kubernetes.

This repository contains the code for the _knctl_ *snap* package.

**NOTE:**
  Works on Ubuntu, Fedora, Debian, and other major Linux distributions.

## Prerequisites

 Prerequisites include a linux installation and the snapd service. 
 In order to install snapd please follow the [Install snapd](https://docs.snapcraft.io/core/install) guide.

## Installation

In order to install the bosh snap use the 'snap' cli i.e :

```
sudo snap install kwt
```

## Build

Checkout the source code and from inside the snap directory execute the following command :

```
snapcraft
```

## Contributing

 See the [contribution guidelines](CONTRIBUTING.md).

## License
```
MIT License

Copyright (c) 2018-2019 Ioannis Polyzos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
