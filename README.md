# MemJect [![C](https://img.shields.io/badge/language-C-%23f34b7d.svg)](https://en.wikipedia.org/wiki/C) [![Windows](https://img.shields.io/badge/platform-Windows-0078d7.svg)](https://en.wikipedia.org/wiki/Microsoft_Windows) [![x86](https://img.shields.io/badge/arch-x86-red.svg)](https://en.wikipedia.org/wiki/X86)[![License](https://img.shields.io/github/license/danielkrupinski/MemJect.svg)](LICENSE)
Simple Dll injector loading from memory. Supports PE header and entry point erasure. Written in C99.

## Features

* load Dll from byte array in memory, without storing dll file on disk
* erase DllEntryPoint
* erase PE header
