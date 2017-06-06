# image-downloader v1.0.5
Downloading images off from a given url using a CasperJS-powered script onto the local filesystem.

## Why is this useful?

If you ever need an easy way to download all the images off from a given url. You are in luck. This can be as easy as it seems.

## Installation

CasperJS can be installed on Mac OSX, Windows and most Linuxes. Please head over [here](http://docs.casperjs.org/en/latest/installation.html) to install CasperJS. The source code are provided in two format (zip and tar.gz), please download the [files](https://github.com/poanchen/image-downloader/releases) to your computer to start downloading images off from almost any site easily.

Run the following commands to get the getImages.js working,

```
git clone https://github.com/poanchen/image-downloader.git
cd image-downloader
npm install
```

## Environment

Tested on both Windows 10 and OS X 10.11 El Capitan.

## Usage

```
casperjs getImages.js http://www.example.com
```

Or, to enable debugging mode

```
casperjs getImages.js http://www.example.com --g
```

## Demo

![Loading the first image](demo.gif)
![Loading the first image](demo.PNG)
