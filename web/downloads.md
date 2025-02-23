# Downloads

The heart of the Mingw-w64 project is headers and support libraries to
run the output of GCC on Windows. Since Mingw-w64 is neither the home of
GCC nor of binutils, several sets of installation packages which combine
them are available.

In addition, the sources are available but most people will want to grab
binaries directly..

## Pre-built toolchains and packages

<table>
    <tbody>
        <tr>
            <th>
            </th>
            <th>Version </th>
            <th>Host </th>
            <th>GCC / Mingw-w64 Version </th>
            <th>Languages </th>
            <th>Additional Software in Package Manager </th>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#arch-linux"><img
                            src="../logos/archlinux-logo.png" 
                            title="Arch Linux logo" alt="Arch Linux logo" width="32"></a><br><a
                        href="#arch-linux"> Arch
                        Linux</a></strong>
            </td>
            <td colspan="2">Arch Linux </td>
            <td>
                <a href="https://aur.archlinux.org/packages/mingw-w64-gcc/" class="urlextern"
                    title="https://aur.archlinux.org/packages/mingw-w64-gcc/" rel="nofollow">8.2.0</a>/<a
                    href="https://aur.archlinux.org/packages/mingw-w64-crt/" class="urlextern"
                    title="https://aur.archlinux.org/packages/mingw-w64-crt/" rel="nofollow">5.0.4</a>
            </td>
            <td>Ada, C, C++, Fortran, Obj-C, Obj-C++ </td>
            <td>305+</td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#cygwin"><img
                            src="../logos/cygwin-logo.png"
                            title="Cygwin logo" alt="Cygwin logo" width="32"></a><br>
                            <a href="#cygwin">Cygwin</a></strong>
            </td>
            <td>Rolling</td>
            <td>Windows</td>
            <td>5.4.0/5.0.2 </td>
            <td>Ada, C, C++, Fortran, Obj-C </td>
            <td>5 (bzip2, libgcrypt, libgpg-error, minizip, xz, zlib) </td>
        </tr>
        <tr>
            <td style="text-align:center;" rowspan="4">
                <strong><a href="#debian"><img src="../logos/debian-logo.png" title="Debian logo" alt="Debian logo" width="32"></a>
                <br>
                <a href="#debian">Debian</a></strong>
            </td>
            <td colspan="2">Debian 7 (Wheezy) </td>
            <td>4.6.3/2.0.3 </td>
            <td rowspan="4">Ada, C, C++, Fortran, Obj-C, Obj-C++, OCaml </td>
            <td rowspan="2">2 (gdb, nsis) </td>
        </tr>
        <tr>
            <td colspan="2">Debian 8 (Jessie) </td>
            <td>4.9.1/3.2.0 </td>
        </tr>
        <tr>
            <td colspan="2">Debian 9 (Stretch) </td>
            <td>6.3.0/5.0.0 </td>
            <td rowspan="2">9 (gdb, libassuan, libgcrypt, libgpg-error, libksba, libnpth, nsis, win-iconv, zlib) </td>
        </tr>
        <tr>
            <td colspan="2">Debian 10 (Buster) </td>
            <td>8.3.0/6.0.0 </td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#fedora"><img
                            src="../logos/fedora-logo.png"
                            title="Fedora Linux logo" alt="Fedora Linux logo" width="32"></a><br><a
                        href="#fedora" > Fedora</a></strong>
            </td>
            <td colspan="2">Fedora 19 </td>
            <td>4.8.1/? </td>
            <td>Ada, C, C++, Fortran, Obj-C, Obj-C++ </td>
            <td>149+</td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#llvm-mingw">LLVM-MinGW</a></strong>
            </td>
            <td>20210423</td>
            <td>Windows, Linux</td>
            <td>LLVM 12.0.0/trunk</td>
            <td>C, C++</td>
            <td>make</td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#macports"><img
                            src="../logos/macports-logo.png"
                            title="MacPorts logo" alt="MacPorts logo" width="32"></a><br><a
                        href="#macports">
                        MacPorts</a></strong>
            </td>
            <td>Rolling </td>
            <td>macOS</td>
            <td>
                <a href="https://github.com/macports/macports-ports/blob/master/cross/x86_64-w64-mingw32-gcc/Portfile"
                    class="urlextern"
                    title="https://github.com/macports/macports-ports/blob/master/cross/x86_64-w64-mingw32-gcc/Portfile"
                    rel="nofollow">8.2.0</a>/<a
                    href="https://github.com/macports/macports-ports/blob/master/cross/mingw-w64/Portfile"
                    class="urlextern"
                    title="https://github.com/macports/macports-ports/blob/master/cross/mingw-w64/Portfile"
                    rel="nofollow">5.0.4</a>
            </td>
            <td>C, C++, Fortran, Obj-C, Obj-C++ </td>
            <td>1 (nsis)</td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#mingw-builds">MingW-W64-builds</a></strong>
            </td>
            <td>Rolling </td>
            <td>Windows</td>
            <td>7.2.0/5.0.3 </td>
            <td>C, C++, Fortran </td>
            <td>4 (gdb, libiconf, python, zlib) </td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#msys2" class="media" title="download:msys2"><img
                            src="../logos/msys2-logo.png"
                            title="Msys2 logo" alt="Msys2 logo" width="32"></a><br>
                            <a href="#msys2">Msys2</a></strong>
            </td>
            <td>Rolling </td>
            <td>Windows</td>
            <td>
                <a href="https://github.com/Alexpux/MINGW-packages/blob/master/mingw-w64-gcc/PKGBUILD" class="urlextern"
                    title="https://github.com/Alexpux/MINGW-packages/blob/master/mingw-w64-gcc/PKGBUILD"
                    rel="nofollow">9.2.0</a>/<a
                    href="https://github.com/Alexpux/MINGW-packages/blob/master/mingw-w64-crt-git/PKGBUILD"
                    class="urlextern"
                    title="https://github.com/Alexpux/MINGW-packages/blob/master/mingw-w64-crt-git/PKGBUILD"
                    rel="nofollow">trunk</a>
            </td>
            <td>Ada, C, C++, Fortran, Obj-C, Obj-C++, OCaml </td>
            <td><a href="https://github.com/Alexpux/MINGW-packages">many</a></td>
        </tr>
        <tr>
            <td style="text-align:center;" rowspan="6">
                <strong><a href="#ubuntu"><img
                            src="../logos/ubuntu-logo.png" 
                            title="Ubuntu logo" alt="Ubuntu logo" width="32"></a><br><a href="#ubuntu"> Ubuntu</a></strong>
            </td>
            <td colspan="2">12.04 Precise Pangolin </td>
            <td>4.6.3/2.0.1 </td>
            <td rowspan="6">Ada, C, C++, Fortran, Obj-C, Obj-C++, OCaml </td>
            <td rowspan="5">2 (nsis, gdb) </td>
        </tr>
        <tr>
            <td colspan="2">14.04 Trusty Tahr </td>
            <td>4.8.2/3.1.0 </td>
        </tr>
        <tr>
            <td colspan="2">14.10 Utopic Unicorn </td>
            <td>4.9.1/3.1.0 </td>
        </tr>
        <tr>
            <td colspan="2">15.04 Vivid Vervet </td>
            <td>4.9.2/3.2.0 </td>
        </tr>
        <tr>
            <td colspan="2">15.10 Wily Werewolf </td>
            <td>4.9.2/4.0.2 </td>
        </tr>
        <tr>
            <td colspan="2"> 16.04 Xenial Xerus </td>
            <td>5.3.1/4.0.4 </td>
            <td>3 (nsis, gdb, zlib) </td>
        </tr>
        <tr>
            <td style="text-align:center;">
                <strong><a href="#win-builds"><img
                            src="../logos/win-builds-logo.png" title="Win-builds logo" alt="Win-builds logo" width="32"></a><br><a
                        href="#win-builds">
                        Win-Builds</a></strong>
            </td>
            <td>1.5 </td>
            <td>Windows, Linux</td>
            <td>4.8.3/3.3.0 </td>
            <td>C, C++ </td>
            <td>91+</td>
        </tr>
        <tr>
        </tr>
    </tbody>
</table>

#### Arch Linux

Installation:

* [Community repository (toolchain)](https://www.archlinux.org/packages/?q=mingw-w64)
* [AUR repository (additional packages)](https://aur.archlinux.org/packages/?SeB=n&K=mingw-w64&SB=c&PP=250)

#### Ubuntu

Installation: through integrated package manager.

[Mingw-w64 packages on Ubuntu](https://launchpad.net/ubuntu/+source/mingw-w64)

#### Cygwin

[Cygwin](https://cygwin.com) is a Unix-like environment and command-line
interface for Microsoft Windows. Its core is the cygwin1.dll library which
provides POSIX functionality on top of the Win32 API. It can be used as a build
environment which targets Windows directly and for which output doesn't depend
on cygwin1.dll.

Installation is done through cygwin's package manager:
[setup.exe](http://cygwin.com/install.html).

As part of the numerous packages in cygwin, there are cross-compilation
toolchains which target both 32 bits and 64 bits; their names start with
“mingw64-”.

Once they are installed, they should be used according to the general
cross-compilation approach.

#### Debian

Installation: through integrated package manager.

[Mingw-w64 packages on Debian](https://packages.debian.org/mingw-w64)

#### Fedora

Installation: through integrated package manager.

#### LLVM-MinGW

LLVM-MinGW is a toolchain built with Clang, LLD, libc++, targeting
i686, x86\_64, arm and aarch64 (ARM64), with releases both for running
as a cross compiler from Linux and for running on Windows. It supports
Address Sanitizer, Undefined Behaviour Sanitizer, and generating debug
info in PDB format.

Installation: [GitHub](https://github.com/mstorsjo/llvm-mingw/releases)

#### MacPorts

To install just the 32-bit or just 64-bit compiler with dependencies, use:

```
sudo port install i686-w64-mingw32-gcc
sudo port install x86_64-w64-mingw32-gcc
```

A shortcut to install both:

```
sudo port install mingw-w64
```

Here is the list of [Mingw-w64 packages on MacPorts](https://www.macports.org/ports.php?by=name&substr=mingw).

#### Mingw-builds

Installation: [Sourceforge](http://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/installer/mingw-w64-install.exe/download)

#### MSYS2

Installation: [GitHub](http://msys2.github.io/)


#### Win-Builds

Win-builds is a cross-platform project that makes building for Windows easy. It
supports building from both Windows and Linux systems and provides many
pre-built libraries which can be installed through a graphical package manager.

It aims for stability while still providing recent versions of software
packages.

Installation: http://win-builds.org. 


## Sources

Tarballs for the mingw-w64 sources are hosted on
[SourceForge](http://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/).
The latest version from the 6.x series is **[6.0.0](https://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/mingw-w64-v6.0.0.tar.bz2/download)**.
The latest version from the 5.x series is **[5.0.4](https://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/mingw-w64-v5.0.4.tar.bz2/download)**.
The latest version from the 4.x series is **[4.0.6](http://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/mingw-w64-v4.0.6.tar.bz2/download)**.
The latest version from the 3.x series is **[3.3.0](http://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/mingw-w64-v3.3.0.tar.bz2/download)**.
Winpthreads has been merged into the main tarball as of 3.1.0.

The old wiki has instructions for building
[native](http://sourceforge.net/p/mingw-w64/wiki2/Native%20Win64%20compiler/)
and
[cross](http://sourceforge.net/p/mingw-w64/wiki2/Cross%20Win32%20and%20Win64%20compiler/)
toolchains.

Details on how to get the mingw-w64 code from Git and an Git-web viewer are
available on
[SourceForge](https://sourceforge.net/p/mingw-w64/mingw-w64/ci/master/tree/).

## Unsorted complementary list

### Darwin/Mac OS X

The existing Darwin binaries have been built through buildbot in 2013 and links
to them can be found on the [dedicated
page](http://mingw-w64.org/doku.php/download/darwin).

### OpenSUSE

The [OpenSUSE Linux
distribution](http://mingw-w64.sourceforge.net/www.opensuse.org) also has a
large and well-maintained set of packages for cross-compilation.

### Rubenvb

Rubenvb has built a number of toolchains including some for less common setups.
They are split into two categories: toolchains targeting
[Win32](http://sf.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/rubenvb/)
or
[Win64](http://sf.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/rubenvb/).

### GCC with the MCF thread model

[GCC with the MCF thread model](https://gcc-mcf.lhmouse.com/) is a series of x86
and x64 native toolchains built by LH_Mouse. The MCF thread model involves the
[mcfgthread](https://github.com/lhmouse/mcfgthread/) library to provide minimum
yet complete C++11 thread support. Disregarding POSIX or Windows XP
compatibility, it implements (hopefully the most) efficient mutexes and
condition variables that are competitive with even native slim reader/write
(SRW) locks and condition variables since Windows Vista.

### Store of binaries on SourceForge

A very large number of other binaries and sources are hosted in the [File
Release System on Sourceforge](http://sf.net/projects/mingw-w64/files/) which
might have what you are after.
