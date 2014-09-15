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
