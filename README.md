# Chebyshev

#### testfile
```testfile
test <%= arg1 %> test
```

#### test.yml
```test.yml
arg1: testtest
```

#### run chebyshev

    $ chebyshev testfile test.yml


#### Outputs
```output
test testtest test
```

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'chebyshev'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install chebyshev

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment. Run `bundle exec chebyshev` to use the gem in this directory, ignoring other installed copies of this gem.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/chebyshev. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
