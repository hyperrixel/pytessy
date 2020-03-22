# PyTessy - Tesseract-OCR, faster!

This module allows faster access to Tesseract-OCR from Python scripts.

## Why and when is it so fast?

PyTessy uses direct library-level access to Tesseract-OCR's core library. Therefore is it so fast in case when the image is already in the memory or when the image need to be processed before scanning with Tesseract-OCR. In case of reading and scanning existing files only PyTessy is just a bit faster than usual Tesseract-OCR Python wrappers.

## Requirements

### Operating system

PyTessy is operating system independent in case if you set the exact location of your Tesseract-OCR library since presently library search process is implemented on Windows only.

### Python modules

PyTessy uses only modules from the Standard Library only. Python version must be ` >= 3.6 `.

### External requirements

You have to have installed or portable version of Tesseract-OCR (at least a working library and ` tessdata `).

You can download Tesseract-OCR from [here](https://tesseract-ocr.github.io/tessdoc/Downloads).

## Installation

You can install the latest PyTeyy version with ` pip install pytessy ` or you can download the wheel from this repository or build the source code.

## Documentation

PyTessy has a [ReadTheDocs page](https://pytessy.readthedocs.io/)
