# The Go Programming Language

Go is an open source programming language that makes it easy to build simple,
reliable, and efficient software.

![Gopher image](doc/gopher/fiveyears.jpg)
*Gopher image by [Renee French][rf], licensed under [Creative Commons 3.0 Attributions license][cc3-by].*

Our canonical Git repository is located at https://go.googlesource.com/go.
There is a mirror of the repository at https://github.com/golang/go.

Unless otherwise noted, the Go source files are distributed under the
BSD-style license found in the LICENSE file.

### Unofficial Binary

This is an unofficial binary of Go/Golang for Windows on ARM (ARM64) devices,
such as Microsoft Surface Pro X, Lenovo Yoga C630, Samsung Galaxy Book S, etc.
The repo will be maintained until the official binary is released.

### Download and Install

#### Windows on ARM (ARM64)

[go1.15.2.windows-arm64.zip](https://github.com/thongtech/go-windows-arm64/releases/download/1.15.2/go1.15.2.windows-arm64.zip)

- Extract ZIP to C:\Go
- Add C:\Go\bin to system PATH
- Add %USERPROFILE%/go/bin to user PATH
- Add %USERPROFILE%/go as GOPATH to user variables
- Done

#### Binary Distributions

Official binary distributions are available at https://golang.org/dl/.

After downloading a binary release, visit https://golang.org/doc/install
or load [doc/install.html](./doc/install.html) in your web browser for installation
instructions.

#### Install From Source

If a binary distribution is not available for your combination of
operating system and architecture, visit
https://golang.org/doc/install/source or load [doc/install-source.html](./doc/install-source.html)
in your web browser for source installation instructions.

### Contributing

Go is the work of thousands of contributors. We appreciate your help!

To contribute, please read the contribution guidelines:
	https://golang.org/doc/contribute.html

Note that the Go project uses the issue tracker for bug reports and
proposals only. See https://golang.org/wiki/Questions for a list of
places to ask questions about the Go language.

[rf]: https://reneefrench.blogspot.com/
[cc3-by]: https://creativecommons.org/licenses/by/3.0/
