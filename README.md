# gSwitch

gSwitch allows control over the gpu on dual gpu macs. It also optionally gives a notification when the gpu changed.

## Install

Currently the only way to install is to build the source, however I will be adding a proper solution soon.

You must have Carthage installed:

```
brew update
brew install carthage
```

And then bootstrap the frameworks:

```
carthage bootstrap
```

## FAQ

Why create this when the amazing [gfxCardStatus](https://github.com/codykrieger/gfxCardStatus) exists? Well it was kind of buggy and I thought the notification system was a bit too happy so I rewrote the program in swift and made a bunch of changes. Also it seems like cody is no longer maintaining it like he used to.

## Notes

Unless you have a 2013 Macbook Pro with a 750m consider yourself a guinea pig. Since this is so new it is untested on anything else.

Does not support macs older than 2011

Since I wrote this in about 3 days I'm sure there are going to be issues.
