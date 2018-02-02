# Spotlight example application for the Code4Lib 2018 preconference

## System dependencies

* Ruby 2.3 or greater
* Java 8 or greater

[GoRails](https://gorails.com/setup/) provides a tutorial for preparing your machine for Rails development on OS X and Linux.

## Getting Started

Cloning the project:

```console
$ git clone git@github.com:cbeer/code4lib_spotlight_workshop.git # preferred, or:
# $ git clone https://github.com/cbeer/code4lib_spotlight_workshop.git # or:
# download https://github.com/cbeer/code4lib_spotlight_workshop/archive/master.zip

$ cd code4lib_spotlight_workshop
```

Installing the dependencies:

```
$ bin/setup
# this runs `bundle install`, `rake db:setup`, and does environment sanity checks
```

Running the tests:

```console
$ bundle exec rake
```

Running the rails server:

```console
$ bundle exec rails server
```

Starting solr:

```console
# in a new terminal:
$ bundle exec solr_wrapper
```

## References

* [Blacklight wiki](https://github.com/projectblacklight/blacklight/wiki)
* [Spotlight wiki](https://github.com/projectblacklight/spotlight/wiki)
* [Customizing Blacklight tutorial](http://jessiekeck.com/customizing-blacklight)
* [Customizing Geoblacklight](http://geoblacklight.org/tutorial/2015/02/09/customize-your-application.html)
* [blacklight/configuration.rb](https://github.com/projectblacklight/blacklight/blob/master/lib/blacklight/configuration.rb)
* [Rails guides](http://guides.rubyonrails.org/)
* [Solr Reference Guide](https://cwiki.apache.org/confluence/display/solr/Apache+Solr+Reference+Guide)
