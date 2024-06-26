# Packwerk Haml

> [!WARNING]
> This gem currently depends on a development branch for packwerk !!!
> Once https://github.com/Shopify/packwerk/pull/375 is merged and released, can this gem be safely used.

Add haml support to [packwerk](https://github.com/Shopify/packwerk/)

## Installation

1. Add the gem to your Gemfile

```ruby
gem "packwerk-haml"
```

2. Require `packwerk-haml` in your `packwerk.yml`

```yml
require:
  - packwerk_haml
```

3. Update `packwerk.yml` to include HAML files

```yml
include:
- "**/*.{rb,rake,erb,haml}"
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bundle exec rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/richardmarbach/packwerk-haml.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
