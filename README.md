# Compose

Compose is a [Hugo](https://gohugo.io/) theme for documentation websites, inspired by [forestry.io](forestry.io)'s docs page. The theme provides a simple navigation & structure.

![Hugo Compose Theme](https://github.com/onweru/compose/blob/master/images/tn.png)

![Hugo Compose Theme](https://github.com/onweru/compose/blob/master/images/tn-1.png)

## Features

1. Docs
2. Gallery Support (via shortcode)
3. Native lazy loading of images

## Installation

Install a recent release of the Hugo "extended" version; ideally versions `>= 0.61.0`. If you install from [hugo releases page](https://github.com/gohugoio/hugo/releases),  download the `_extended` version, which supports sass.

## ExampleSite

The [exampleSite](https://github.com/onweru/compose/exampleSite), as the theme's user guide.

> This guide covers the necessary bits. As the project evolves, the userguide will get more comprehensive

You can use Hugo to generate and serve a local copy of the guide (also useful for testing local theme changes), making sure you have installed all the prerequisites listed above:

```
git clone --recurse-submodules --depth 1 https://github.com/onweru/compose.git
cd compose/exampleSite/
hugo server --themesDir ../..
```

Note that you need the `themesDir` flag when running Hugo because the site files are inside the theme repo.

### How do I disable dark mode?

Under `params` add `darkMode = false` to your `config.toml` file. If your site is based on the exampleSite, the value is already included; you only need to uncomment it.

> The user will still have the option to activate dark mode, if they so wish

## From the same creator

1. [Clarity Theme](https://github.com/chipzoller/hugo-clarity)
2. [Newsroom Theme](https://github.com/onweru/newsroom)
3. [Swift Theme](https://github.com/onweru/hugo-swift-theme)

## License

This theme is available under the [MIT license](https://github.com/onweru/compose/blob/master/LICENSE.md).
