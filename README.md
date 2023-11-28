# colorama_ex
A 256-color extension of Colorama.

## What Is Colorama_EX?

Colorama_EX is a basic 256-color extension of the famous Colorama module used in various Python CLI (Command-Line Interface) projects. While Colorama already does a good job in introducing independent colorization of font and background, thus allowing very colorful consoles to materialize, Colorama_EX takes this even further and gives Colorama the ability to use 256-color ANSI escape codes for even more colorful consoles.

## Usage

As the Colorama_EX is an extension module of Colorama, the Colorama_EX is to be used along with Colorama. It can even be used along with the standard 16-color escape codes of Colorama. All that needs to be done is to import Colorama's init function, perform the initialization at the beginning, and then to import Colorama_EX and to use it in your consoles. Its syntax is virtually the same as the original Colorama, except with a much bigger variety of colors to choose from.

## Status

- The code numbers 17-231 has been successfully implemented and tested for both foreground and background.
- The code numbers 0-16 will be implemented into Colorama_EX to ease the usage.
- The code numbers 232-255 (grayscales) will be implemented to complete the 256-color code matrix.
- An official, finished package will be published on PyPI later, as PyPI doesn't allow new user registers at the moment (28.11.2023)
