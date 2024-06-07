# The Transoformer website

This site used the template created by the [IDEAL Lab](https://ideal.umd.edu/about.html).

## Build site

To build the website locally, clone the repo with:

```
git clone git@github.com:DIGITLab23/digitlab23.github.io.git
```

Then install necessary Ruby dependencies by running `bundle install` from within the `digitlab23.github.io` directory.  After this, the site can be be built with:

```
bundle exec jekyll build
```

(If you are getting errors at this stage, it may be due to your version of `bundle`. Try `gem uninstall bundler` + `gem install bundler -v 1.13.1`.)

To view the site, run `bundle exec jekyll serve` and point a browser to `http://localhost:4000/`.  More information on Jekyll can be found [here](http://jekyllrb.com/).

To include projects, preprocessing scripts are necessary to clone project repos and update Jekyll metadata. This can be accomplished with:

```
ruby _scripts/update-and-preprocess.rb
```

Then `jekyll build` works as normal.

## For more information

* Look over the [metadata format guide](http://bedford.io/guide/format/)
* Look over the [Markdown style guide](http://bedford.io/guide/style/)

## License

[MIT](http://opensource.org/licenses/MIT)
