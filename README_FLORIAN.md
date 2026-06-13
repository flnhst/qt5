# Qt

This repository and the qtbase repository contains changes specific for our use.

## Changes

The addition of the addWaitVkSemaphoreToNextSubmit method in the QRhi class, and associated method in the QRhiImplementation class and QRhiVulkan.

## Setup

Based on Qt v6.11.1.

This repo only difference is this README and the reference to the correct qtbase checkout.

## Building

See the Qt website for general information in building Qt.

To build release (in the D:\qt-dev\qt-build-for-install directory):

```
..\qt\configure -prefix D:\qt-dev\qt-install-release -release -skip qtconnectivity,qtspeech,qtpdf,qtwebengine,qtwebview
```
