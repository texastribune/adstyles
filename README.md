# adstyles

## This is the style guide for Texas Tribune ads.

### Getting started

To get started, clone down the project repo.

If you don't already have Ruby installed, you'll need to [install it](https://www.ruby-lang.org/en/documentation/installation/). This project uses Ruby 2.1.4.

You'll need the Ruby gem bundler. If you need to install the bundler, run:

    gem install bundler

Install the necessary gems from the Gemfile by running:

    bundle install

You might find it helpful to use [rbenv](https://github.com/sstephenson/rbenv) to manage your Ruby environment.

## Initial setup

You'll need to configure your authentication with Google docs for the middleman-google_drive gem. See the Setup section in the README for the gem [here](https://github.com/voxmedia/middleman-google_drive).


You'll also need to set the GOOGLE_DRIVE_KEY environment variable to load data from Google docs.

## Development

Middleman is configured to live reload as changes are made to files. To start up the Middleman server, run:

    bundle exec middleman

To build the site, run:

    bundle exec middleman build

When Middleman builds, it creates a static file for each file located in the source folder. The build process is configured in config.rb.

## Deploying

The style guide deploys to Heroku.


