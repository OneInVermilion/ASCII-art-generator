# ASCII-art-generator

A simple Python utility that converts PNG images into ASCII art. The project maps image brightness values to a configurable set of ASCII characters, allowing you to customize the appearance and level of detail of the generated output.

## Features

* Convert PNG images into ASCII art
* Configurable ASCII character palette
* Lightweight and easy to use
* Written entirely in Python

## How It Works

The program reads a PNG image, processes its pixel brightness values, and replaces each pixel with a corresponding ASCII character from a user-defined palette. Darker pixels are mapped to denser characters, while lighter pixels are represented by simpler characters, producing a text-based representation of the original image.

## Configuration

The `settings.txt` file contains the configuration for the converter, including the ASCII palette used during image generation.
