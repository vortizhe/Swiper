## ALERT! Swiper fork with IE9 support.

Since version 3 Swiper drop IE9 support, so I take swiper.jquery.js version and add a simple `classList` polyfill to get miniminal IE9 support.

**Use `dist/swiper.ie9.js` or minified version**.

Swiper
==========

Swiper - is the free and most modern mobile touch slider with hardware accelerated transitions and amazing native behavior. It is intended to be used in mobile websites, mobile web apps, and mobile native/hybrid apps. Designed mostly for iOS, but also works great on latest Android, Windows Phone 8 and modern Desktop browsers

Swiper is not compatible with all platforms, it is a modern touch slider which is focused only on modern apps/platforms to bring the best experience and simplicity.

# Getting Started
  * [Getting Started Guide](http://www.idangero.us/swiper/get-started/)
  * [API](http://www.idangero.us/swiper/api/)
  * [Demos](http://www.idangero.us/swiper/demos/)
  * [Forum](http://www.idangero.us/swiper/forum/)

# Dist / Build

On production use files (JS and CSS) only from `dist/` folder, there will be the most stable versions, `build/` folder is only for development purpose

### Build

Swiper uses `gulp` to build a development (build) and dist versions.

First you need to have `gulp-cli` which you should install globally.

```
$ npm install --global gulp
```

Then install all dependencies, in repo's root:

```
$ npm install
```

And build development version of Swiper:
```
$ gulp build
```

The result is available in `build/` folder.

### Dist/Release

After you have made build:

```
$ gulp dist
```

Distributable version will available in `dist/` folder.

# Contributing

All changes should be commited to `src/` files. Swiper uses LESS for CSS compliations, and concatenated JS files (look at gulpfile.js for concat files order)

Swiper 2.x.x
==========

If you still using Swiper 2.x.x or you need old browsers support, you may find it in [Swiper2 Branch](https://github.com/nolimits4web/Swiper/tree/Swiper2)
* [Download Latest Swiper 2.7.6](https://github.com/nolimits4web/Swiper/archive/v2.7.6.zip)
* [Source Files](https://github.com/nolimits4web/Swiper/tree/Swiper2/src)
* [API](https://github.com/nolimits4web/Swiper/blob/Swiper2/API.md)
