# Factree
[![Gem Version](https://badge.fury.io/rb/factree.svg)](https://rubygems.org/gems/factree)
[![Build Status](https://travis-ci.org/jstrater/factree.svg?branch=master)](https://travis-ci.org/jstrater/factree)

Factree provides tools for making choices based on a set of facts that are not yet known. You write a decision function that takes a set facts and returns a conclusion. Factree will run your function and make sure it has all of the facts it needs to complete. If it doesn't, then Factree will tell you what's needed to continue.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'factree'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install factree

## Usage

[API documentation](http://www.rubydoc.info/github/jstrater/factree/)

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/jstrater/factree.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
