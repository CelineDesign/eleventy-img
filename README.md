<p align="center"><img src="https://www.11ty.dev/img/logo-github.png" alt="eleventy Logo"></p>

# eleventy-img

Low level utility to perform build-time image transformations for both vector and raster images. Output multiple sizes, save multiple formats, cache remote images locally. Uses the [sharp](https://sharp.pixelplumbing.com/) image processor.

You maintain full control of your HTML—this plugin does not generate any markup. Use with `<picture>` or `<img>` or CSS `background-image`, or others! Works great to add `width` and `height` to your images! Does not require or rely on file extensions (like `.png` or `.jpg`) in URLs or local files, which may be missing or inaccurate.

## [The full `eleventy-img` documentation is on 11ty.dev](https://www.11ty.dev/docs/plugins/image/).

* _This is a plugin for the [Eleventy static site generator](https://www.11ty.dev/)._
* Find more [Eleventy plugins](https://www.11ty.dev/docs/plugins/).
* Please star [Eleventy on GitHub](https://github.com/11ty/eleventy/), follow [@eleven_ty](https://twitter.com/eleven_ty) on Twitter, and support [11ty on Open Collective](https://opencollective.com/11ty)

[![npm Version](https://img.shields.io/npm/v/@11ty/eleventy-img.svg?style=for-the-badge)](https://www.npmjs.com/package/@11ty/eleventy-img) [![GitHub issues](https://img.shields.io/github/issues/11ty/eleventy-img.svg?style=for-the-badge)](https://github.com/11ty/eleventy/issues)

## Installation

```
npm install @11ty/eleventy-img
```

_[The full `eleventy-img` documentation is on 11ty.dev](https://www.11ty.dev/docs/plugins/image/)._

## Tests

```
npm run test
```

- We use the [ava JavaScript test runner](https://github.com/avajs/ava) ([Assertions documentation](https://github.com/avajs/ava/blob/master/docs/03-assertions.md))
- ℹ️ To keep tests fast, thou shalt try to avoid writing files in tests.
