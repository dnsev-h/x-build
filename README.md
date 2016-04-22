# x-build

Nice script for userscript building


### Install

Install the dependencies in package.json using add ```x-build.js```, ```x-build-src```, and ```package.json```
to your source directory and run ```npm install```. You can then remove or change ```package.json```.


### Usage

```batch
node x-build [options] <meta files...>

Available options:
  --dev   Enable continous builds when relevant script files are updated
  --full  Build with full debugging information

If no meta files are specified, "./src/main.json" is used.
Otherwise, <meta files> is a list of .json files that act as build descriptors.
```