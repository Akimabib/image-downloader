# image-downloader
Downloading images off from a given url using a CasperJS-powered script onto the local filesystem.

## Why is this useful?

If you ever need an easy way to download all the images off from a given url. You are in luck. This can be as easy as it seems.

## Requirements

- [PhantomJS](http://phantomjs.org/) or [SlimerJS](https://slimerjs.org/)
- [CasperJS](http://casperjs.org/)

## Installation

Please make sure you have PhantomJS or SlimerJS with CasperJS ready, then you may continue. (You may run these commands to check if you have PhantomJS or SlimerJS or CasperJS installed)

```
casperjs --version
phantomjs --version
```

Run the following command to get the latest copy of getImages.js,

```
git clone https://github.com/poanchen/image-downloader.git
```

Then,

```
cd image-downloader
npm install
```

## Usage

```
casperjs getImages.js http://www.example.com
```

Or, to enable debugging mode

```
casperjs getImages.js http://www.example.com --g
```

## Demo

![Loading the first image](demo.PNG)

## License

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
