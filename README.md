# middleman-blog-slim-template

This is a [middleman](http://middlemanapp.com) template styled with [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io) and [Bitters](http://bitters.bourbon.io).

## Screensshot

![screenshot.jpg](https://raw.githubusercontent.com/5t111111/middleman-blog-bourbon-template/master/screenshot.jpg)

## Quickstart

### Clone this tempalate to your machine

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

## Thanks

- This project is strongly inspired by [https://github.com/biblichor/middleman-blog-bootstrap-template](https://github.com/biblichor/middleman-blog-bootstrap-template)
- [Styling a Middleman Blog with Bourbon, Neat, and Bitters](http://robots.thoughtbot.com/middleman-bourbon-walkthrough) written by Carolann Bonner also gives me a lot of help.
