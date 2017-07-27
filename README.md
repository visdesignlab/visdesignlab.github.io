# Vis Design Lab Website

The Vis Design Lab website is based on the Caleydo website and built with
[Jekyll](http://jekyllrb.com).



## Setup Jekyll

If you have Ruby on your machine, just install Jekyll and a plugin:

``` shell
$ gem install jekyll
$ gem install jekyll-redirect-from
```

Further details on installing Jekyll and its requirements:
https://jekyllrb.com/docs/installation/


### Run Jekyll

``` shell
$ jekyll serve -i
```

Running Jekyll in incremental (`-i`) mode is _significantly_ faster.


### View the Generated Site

``` shell
$ open http://0.0.0.0:4000/
```


## Contributions

All VDL members are responsible for updating their content regularly. Small
changes that you have tested thoroughly using Jekyll may be pushed to _master_,
but we recommend using separate branches to submit _pull requests_ for
additional review and to catch mistakes. See the resources below for details on
the following:

- [Adding team members](_persons/README.md)
- [Adding publications](_publications/README.md)
- [Adding images](assets/images/README.md)


You can create a branch and add/edit files from the GitHub site. Alternatively,
you can write your changes from the command line (below), and go to GitHub to
create a _pull request_ from that branch.

``` shell
$ git checkout -b new-branch-name
$ git commit -am "make your changes and commit them"
$ git push origin new-branch-name
```



## Modifying the Code

Jekyll generates websites for you based on data stored in `_config.yaml`. One
important aspect is a "collection", such as publications, which get rendered
using specific layout templates to designated pages. For example, a single
publication gets its own webpage (`/publications/id/`), and it gets added to the
list of all publications as well (`/publications/`). Content for Jekyll can be
written in Markdown for automatic parsing, and variables stored in YAML at the
top of both Markdown and HTML pages. Check the Jekyll and [Liquid template
syntax](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)
documentation for further details.

The CSS is built using [SASS](http://www.sass-lang.com) along with several SASS
tools: [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io), and
[Bitters](http://bitters.bourbon.io). SASS provides imports, variables, mixins
(functions), and nested CSS so you can write better stylesheets. The additional
tools provide grid layouts, vendor prefixing, and preset styles, and they are
preloaded into the repository.


You can modify the CSS or SASS directly, since Jekyll builds it for you. The
main site SASS file is in `css/site.scss`, which imports all other files,
including the SASS tools in the `_sass` directory.


Unfortunately, changes to the code have been made throughout the SASS tools, so
the SASS tools should not be upgraded. In the future, I would recommend
rewriting the stylesheets (from scratch or through the Jekyll-compiled output
CSS) so that you just use SASS and more modern CSS3 features like media queries
and variables.



## GitHub Pages and Jekyll

Installation instructions above for Jekyll will work for the most part, but you
can also emulate the current GitHub Pages server environment with the following
installation instructions:
https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/


To install the GitHub Pages gem, you may need to install the Ruby DevKit for
your operating system.
