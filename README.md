# wildtreetech.github.io
Wild Tree Technologies homepage.

Images from Unsplash

Based on the "Landed" template by [HTML5 UP](//html5up.net) | @n33co
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


## Making changes

To change the appearance modify the files in `assets/sass` and recreate
the CSS with `sass --watch assets/sass:assets/css`. Convert a big image
to one suitable for the web with
`convert pic0N.big.jpg -resize 1600x1050\! pic0N.jpg`.


## Run jekyll locally

You can [test your changes locally](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#platform-mac) using `jekyll`:

```
# first time after checking out the repo
rvm install ruby-2.4.2
gem install bundler
bundle install
# generate and serve pages locally
bundle exec jekyll build --safe
bundle exec jekyll serve
```


## Setup from scratch

* Install SASS: `gem install sass`
