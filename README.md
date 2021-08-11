# [Synalytica Website](https://synalytica.xyz/)

This repository serves as the homepage of the collective known as Synalytica. 
<p>&nbsp;</p>

# Adding blog posts
You write blog posts as text files and Jekyll provides everything you need to turn it into a blog.

## The Posts Folder

The `_posts` folder is where your blog posts live. You typically write posts
in [Markdown](https://daringfireball.net/projects/markdown/), HTML is
also supported.

## Creating Posts

To create a post, add a file to your `_posts` directory with the following
format:

```
YEAR-MONTH-DAY-title.MARKUP
```

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit
numbers, and `MARKUP` is the file extension representing the format used in the
file. For example, the following are examples of valid post filenames:

```
2011-12-31-new-years-eve-is-awesome.md
2012-09-12-how-to-write-a-blog.md
```

All blog post files must begin with [front matter](/docs/front-matter/) which is
typically used to set a [layout](/docs/layouts/) or other meta data. Use the template given below to bootstrap 
blog creation. Currently supported topics:
1. Quant
2. Dev
3. Blockchain
4. AI

```markdown
---
layout: post
title:  "Welcome to Synalytica!"
topic:  "Quant"
---

# Welcome

**Hello world**, this is my first blog post.

I hope you like it!
```

## Including images and resources

At some point, you'll want to include images, downloads, or other
digital assets along with your text content. One common solution is to create
a folder in the root of the project directory called something like `assets`,
into which any images, files or other resources are placed. Then, from within
any post, they can be linked to using the site’s root as the path for the asset
to include. The best way to do this depends on the way your site’s (sub)domain
and path are configured, but here are some simple examples in Markdown:

Including an image asset in a post:

```markdown
... which is shown in the screenshot below:
![My helpful screenshot](/assets/screenshot.jpg)
```

Linking to a PDF for readers to download:

```markdown
... you can [get the PDF](/assets/mydoc.pdf) directly.
```
<p>&nbsp;</p>

# Development Setup

## Prerequisites
* Install [Jekyll](https://jekyllrb.com/docs/installation/)

We recommend using [Bundler](http://bundler.io/) to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler:

1. Install Ruby. For more information, see ["Installing Ruby"](https://www.ruby-lang.org/en/documentation/installation/) in the Ruby documentation.
2. Install Bundler. For more information, see ["Bundler"](https://bundler.io/).


## Building your site locally
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
```
