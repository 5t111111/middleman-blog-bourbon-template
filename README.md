# middleman-blog-bourbon-template

This is a [Middleman](http://middlemanapp.com) template styled with [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io) and [Bitters](http://bitters.bourbon.io).

## Screenshot

![screenshot.jpg](https://raw.githubusercontent.com/5t111111/middleman-blog-bourbon-template/master/screenshot.jpg)

## Features

- [Slim](http://slim-lang.com) as template engine
- Syntax highlighting with [middleman-syntax](https://github.com/middleman/middleman-syntax) (using [rouge](https://github.com/jneen/rouge))
- Responsive layout with Neat grid system
- [Font Awesome](http://fortawesome.github.io/Font-Awesome) for easily adding social media link icon
- Live reload with middleman-livereload

## Quickstart

Install Middleman if you haven't done yet.

```console
$ gem install middleman
```

### Clone this template to your machine

```console
$ mkdir ~/.middleman # if it doesn't exist
$ cd ~/.middleman
$ git clone https://github.com/5t111111/middleman-blog-bourbon-template.git blog-bourbon
```

### Create middleman blog

```console
$ middleman init my-fantastic-blog --template=blog-bourbon
```

### Install bitters

```console
$ cd my-fantastic-blog/source/stylesheets
$ bundle exec bitters install
```

### Enable Neat grid system in bitters' settings

Uncomment the below line in `source/stylesheets/base/_base.scss`

```scss
// Neat Settings -- uncomment if using Neat -- must be imported before Neat$
// @import 'grid-settings';$
```

### Start Middleman server

```console
$ bundle exec middleman
```

Open `http://localhost:4567` in a web browser.

## Site configuration

Edit at least the following settings in config.rb.

- :site_url - Your blog URL
- :site_author - Author name of your blog
- :site_title - Your blog title

## Thanks

- This project is strongly inspired by [middleman-blog-bootstrap-template](https://github.com/biblichor/middleman-blog-bootstrap-template)
- The article [Styling a Middleman Blog with Bourbon, Neat, and Bitters](http://robots.thoughtbot.com/middleman-bourbon-walkthrough) also gives me a lot of help.
