# img-swap

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

img-swap is a command-line tool that allows you to change the reading order of a
book by renaming pages in pair.

## How to install

You can download a pre-compiled executable for Linux, MacOS and Windows
operating systems
[on the release page](https://github.com/TehUncleDolan/img-swap/releases/latest),
then you should copy that executable to a location from your `$PATH` env.

## Usage

The simplest invocation only requires you to specify the directory where the
files you want to rename are.

```bash
img-swap my-book
```

You can also gives the path to several books:

```bash
img-swap "Tome 01" "Tome 02"
```
