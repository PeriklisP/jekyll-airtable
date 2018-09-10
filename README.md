# Jekyll::Airtable

This gem enables you to easily integrate Airtable with Jekyll site and use it as a database. Everytime the Jekyll build is triggered, the gem would automatically send API request to the Airtable base and tables you specify from the environment variable and then store the records as collections, grouped according to the table names.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jekyll-airtable'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-airtable

## Usage

1. Add this gem to the Gemfile
2. Run ```sh bundle install ``` on the terminal
3. Do not forget to declare it also on the config.yml, below the "gems" or "plugins" YAML key.
4. Then you can execute the plugin using ```sh bundle exec jekyll serve ``` or ```sh bundle exec jekyll build ```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/jekyll-airtable. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Jekyll::Airtable project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/jekyll-airtable/blob/master/CODE_OF_CONDUCT.md).
