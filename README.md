# [Synalytica Website](https://synalytica.xyz/)

[![Gem Version](https://img.shields.io/gem/v/jekyll.svg)][ruby-gems]
[![Linux Build Status](https://github.com/jekyll/jekyll/workflows/Continuous%20Integration/badge.svg)][ci-workflow]
[![Windows Build status](https://img.shields.io/appveyor/ci/jekyll/jekyll/master.svg?label=Windows%20build)][appveyor]
[![Security](https://hakiri.io/github/jekyll/jekyll/master.svg)][hakiri]

[ruby-gems]: https://rubygems.org/gems/jekyll
[hakiri]: https://hakiri.io/github/jekyll/jekyll/master
[ci-workflow]: https://github.com/jekyll/jekyll/actions?query=workflow%3A%22Continuous+Integration%22+branch%3Amaster
[appveyor]: https://ci.appveyor.com/project/jekyll/jekyll/branch/master

This repository serves as the homepage of the collective known as Synalytica. 
<p>&nbsp;</p>

## Development Setup

### Prerequisites
* Install [Jekyll](https://jekyllrb.com/docs/installation/)

We recommend using [Bundler](http://bundler.io/) to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler:

1. Install Ruby. For more information, see ["Installing Ruby"](https://www.ruby-lang.org/en/documentation/installation/) in the Ruby documentation.
2. Install Bundler. For more information, see ["Bundler"](https://bundler.io/).


### Building your site locally
1. Open Terminal.
2. Navigate to the publishing source for your site. For more information about publishing sources, see "[About GitHub Pages](https://docs.github.com/en/articles/about-github-pages#publishing-sources-for-github-pages-sites)".
3. Run bundle install.
4. Run your Jekyll site locally.
```
$ bundle exec jekyll serve
> Configuration file: /Users/octocat/my-site/_config.yml
>            Source: /Users/octocat/my-site
>       Destination: /Users/octocat/my-site/_site
> Incremental build: disabled. Enable with --incremental
>      Generating...
>                    done in 0.309 seconds.
> Auto-regeneration: enabled for '/Users/octocat/my-site'
> Configuration file: /Users/octocat/my-site/_config.yml
>    Server address: http://127.0.0.1:4000/
>  Server running... press ctrl-c to stop.```
To preview your site, in your web browser, navigate to http://localhost:4000.