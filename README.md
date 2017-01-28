# Hot Chocolate

A consistent and responsive [Hugo](http://gohugo.io) [theme](https://github.com/spf13/hugoThemes/) with clean typography. The primary typefaces are Open Sans, Raleway, and Ubuntu Mono.

It is a fork of of Nishanth Shanmugham's great [Cocoa](https://github.com/nishanths/cocoa-hugo-theme) theme. However, it isn't compatible, since it assumes a different folder structure.

[__Demo__](http://themes.gohugo.io/theme/cocoa/)

#### Features

```
* Responsive
* Suited for blogging and personal webpages
* Disqus support
* Built-in 404 page
* Syntax highlighting (by @andy4thehuynh)
* Gravatar/static profile image (by @remeh)
* RSS feed and icon (by @mvrilo)
* Optimized SVG icons (by @robinst)
* Cache busting
* Google Analytics
```

Most features are optional and can be individually enabled/disabled in your [`config.toml`](https://github.com/andrewjesaitis/hot-chocolate/blob/master/exampleSite/config.toml).

## Screenshots

<img src="" width="400">


## Table of Contents

* [Quick start](#quick-start)
* [Usage](#usage)
* [License](#license)

## Quick start 

From the root of your Hugo site, clone the theme into `themes/hot-chocolate` by running:

```sh
# Clone theme into the themes/cocoa directory
$ git clone https://github.com/andrewjesaitis/hot-chocolate.git themes/hot-chocolate

# Generate site files into the public directory
$ hugo -t hot-chocolate

# Or, serve your site and visit localhost:1313 in your browser
$ hugo -t hot-chocolate --watch serve
```

## Usage

#### config.toml

Please see the sample [`config.toml`](https://github.com/andrewjesaitis/hot-chocolate/blob/master/exampleSite/config.toml). Note that if you already use cocoa but have updated to Hugo 0.18, you must lowercase every params of your existing `config.toml` (like in the sample).

#### Creating posts

Posts should generally go under a `content/post` directory. Typically you would run:

````
hugo new post/your-new-post.md
````
For posts to appear on your site, you may need `draft = false` in the post's front matter or use the `--buildDrafts` option when building.

#### Creating fixed pages

Fixed pages such as an About page should preferably go under `content/pages` or be present at the root of the `content` directory.

````
hugo new pages/about.md
````

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/andrewjesaitis/hot-chocolate/blob/master/LICENSE) file for more details.
