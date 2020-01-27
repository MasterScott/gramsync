# gramsync

Parallelized and simplified command-line support for [rsync](https://linux.die.net/man/1/rsync) commands.

## Purpose

I immediately got lazy after learning how to use rsync to back up files from my personal computer to my lab server.

## Usage

The first divergence of usage depends on whether you want to back up individual files or an entire directory.

...

## Installation

- Install the latest version of Python 3
- Install the latest version of rsync on all of your machines involved in file transfer
- Clone/pull repo to your machine 
```
HTTPS: git clone https://github.com/washedgram/gramsync.git
SSH:   git clone git@github.com:washedgram/gramsync.git
```
- Install package requirements
```
$ cd gramsync
$ pip install -r requirements.txt
```

## License

```
MIT License

Copyright (c) 2020 washedgram / gramlabs

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