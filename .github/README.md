
***

# DroppedText language specification

## Version 0.0.1

DroppedText is a markup language for keeping track of file names. It makes use of backslashes, as no functional system uses a backslash in the name of a file. Folders are not currently supported.

### Header

This is an example of a droppedtext header for Ubuntu Linux:

```droppedtext
/:DroppedText:\
/:OS{Linux/Ubuntu}:\
/:DroppedTextSpec={"V0.0.1"}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
// All extensions: *.dropt *.droptex *.droptxt *.drotex *.drotxt *.drtxt *.dtxt *.droppedtext *.droppedtxt *.droppedtex
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
// UTF-16 and UTF-32 are also supported
```

Lines starting with `/:` and ending with `:\` are known as configuration lines. Lines starting with `//` are just comments.

The headers for other operating systems include:

**Fedora Linux**

```droppedtext
/:DroppedText:\
/:OS{Linux/Fedora}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Arch Linux**

```droppedtext
/:DroppedText:\
/:OS{Linux/Arch}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Gentoo Linux**

```droppedtext
/:DroppedText:\
/:OS{Linux/Gentoo}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Mint Linux**

```droppedtext
/:DroppedText:\
/:OS{Linux/Mint}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Red Hat Linux**

_Not to be confused with Red Hat Enterprise Linux (RHEL)_

```droppedtext
/:DroppedText:\
/:OS{Linux/RedHat}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Red Hat Enterprise Linux**

_Not to be confused with Red Hat Linux_

```droppedtext
/:DroppedText:\
/:OS{Linux/RHEL}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Mac OS X (10.0 to 10.6)**

```droppedtext
/:DroppedText:\
/:OS{MacOS/10X}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**OS X (10.7 to 10.11)**

```droppedtext
/:DroppedText:\
/:OS{OS/X}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**MacOS 10.12 to 10.15**

```droppedtext
/:DroppedText:\
/:OS{MacOS/10}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**MacOS 11.0 (Big Sur)**

```droppedtext
/:DroppedText:\
/:OS{MacOS/11}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**MacOS 12.0 (Monterey)**

```droppedtext
/:DroppedText:\
/:OS{MacOS/12}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**ReactOS**

```droppedtext
/:DroppedText:\
/:OS{ReactOS/0.4}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**NixOS**

```droppedtext
/:DroppedText:\
/:OS{Li/Nix}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Vinix**

```droppedtext
/:DroppedText:\
/:OS{Vi/nix}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows XP**

_Windows XP is the oldest version of Windows to be natively supported by this project. The community can port to Windows ME/Windows 2000 and earlier if needed._

```droppedtext
/:DroppedText:\
/:OS{Win/XP}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Vista**

```droppedtext
/:DroppedText:\
/:OS{Win/Vista}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows 7**

```droppedtext
/:DroppedText:\
/:OS{Win/7}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows 8**

```droppedtext
/:DroppedText:\
/:OS{Win/8}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows 8.1**

```droppedtext
/:DroppedText:\
/:OS{Win/8.1}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows 10**

```droppedtext
/:DroppedText:\
/:OS{Win/10}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows 11**

```droppedtext
/:DroppedText:\
/:OS{Win/11}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2003**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2003}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2003 R2**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2003-R2}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2008**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2008}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2008 R2**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2008-R2}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2012**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2012}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2012 R2**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2012-R2}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2016**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2016}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2019**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2019}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Windows Server 2022**

```droppedtext
/:DroppedText:\
/:OS{WinServe/2022}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**FreeBSD**

```droppedtext
/:DroppedText:\
/:OS{BSD/Free}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**NetBSD**

```droppedtext
/:DroppedText:\
/:OS{BSD/Net}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**OpenBSD**

```droppedtext
/:DroppedText:\
/:OS{BSD/Open}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**DragonflyBSD**

```droppedtext
/:DroppedText:\
/:OS{BSD/DragonFly}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Solaris**

```droppedtext
/:DroppedText:\
/:OS{Solaris/Prop}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**OpenSolaris**

```droppedtext
/:DroppedText:\
/:OS{Solaris/Open}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Oberon**

```droppedtext
/:DroppedText:\
/:OS{Ober/on}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**OS/2**

```droppedtext
/:DroppedText:\
/:OS{OS/2}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

**Lisp Machine**

```droppedtext
/:DroppedText:\
/:OS{Lisp/M}:\
/:FileDate:Y2022-M1-D04:\
/:FileExtension:*.drotex:\
/:FileLanguage:English{US}:\
/:Encoding:{UTF-8}:\
```

Notes:

1. The processor type of the computer (IA-32, 86x64, etc.) does not need to be defined, as it is unnecessary to the format.

2. ChromeOS, ChromiumOS, Android, iOS, iPadOS, iPhoneOS, Windows Mobile/PocketPC, Classic MacOS, Windows ME, Windows 2000, Windows 9x, MS-DOS, Windows 3.x.x, Windows 2.x.x, Windows 1.x.x, PC-DOS, FreeDOS, Google Fuchsia, and any other operating systems not already listed here or above are not officially supported at the moment.

3. No other notes currently available

***

## Encoding

DroppedText supports the following encoding styles:

**UTF-8**

```droppedtext
/:Encoding:{UTF-8}:\
```

**UTF-16**

```droppedtext
/:Encoding:{UTF-16}:\
```

**UTF-32**

```droppedtext
/:Encoding:{UTF-32}:\
```

***

## File extension

DroppedText uses the following file extensions:

{ `*.dropt` | `*.droptex` | `*.droptxt` | `*.drotex` | `*.drotxt` | `*.drtxt` | `*.dtxt` | `*.droppedtext *` | `.droppedtxt` | `*.droppedtex` }

10 file extensions total.

***

## Backslash

Q: Why are backslashes used in syntax?
A: A backslash is the only character that can't be used in a filename (which is a good thing) and it is used for configuration and comments in this file specification

***

## EOL

After the end of a config line, everything after `:\` is ignored. This sort of applies to comments as well, because comments are ignored entirely (comments don't recognize the `:\` sequence.

***

## Table of Contents

A table of contents can be defined in a config line like so:

```droppedtext
/:TOC:\
/:Section count: 3:\
/:Section1#Pictures
/:Section2#Videos
/:Section3#Work Documents
```

Each section must be defined in the document for this to work. Sections are documented in the section below.

***

## Sections

A section is defined like so:

```droppedtext
/:Section1:\
/:Pictures:\ Title of the section
/:Entry count: 4:\
Memory.tiff
Cat.jpeg
Ball.svg
Checkers.png
```

A section does not require a footer. Everything after the last config line that isn't a comment or a filename is ignored until the next config line, which will count as the next section.

***

## Whitespace

Whitespace is counted as whitespace to prevent headaches. You don't need to enter `%20` each time.

***

## Footer

To mark the end of a file, you will need to place this line:

```droppedtext
/:Entry{end}:\
```

***

## Proposals for V0.0.2

* Automation features:

- [ ] Drop folders/files into a special IDE and then go through settings to mass-rename them, and make a log file

- [ ] Same as above, but import options as well, instead of drag and drop

- [ ] Native support for Linux drag and drop droppedtext file

* DroppedText IDE

- [ ] Above: automation

- [ ] Basic IDE, similar in style to Python IDLE

- [ ] Syntax highlighting

- [ ] GTK support, QT support

* Support for folders/directories

***

## File info

**File type:** `Markdown document (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Tuesday, January 4th at 11:16 pm)`

**Line count (including blank lines and compiler line):** `605`

***
