# CurrencyFormatter::Rails

[![Gem Version](https://badge.fury.io/rb/currencyFormatter-rails.svg)](https://rubygems.org/gems/currencyFormatter-rails) 
[![Downloads](https://img.shields.io/gem/dt/currencyFormatter-rails.svg)](https://rubygems.org/gems/currencyFormatter-rails)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/tanvir002700/currencyFormatter-rails/master.svg)](https://github.com/tanvir002700/currencyFormatter-rails)
[![license](https://img.shields.io/github/license/tanvir002700/currencyFormatter-rails.svg)](https://github.com/tanvir002700/currencyFormatter-rails/blob/master/LICENSE)

This gem packages the javascript currencyFormatter.js plugin. So you never have to download a custom package through the web interface again.

CurrencyFormatter.js allows you to format numbers as currencies. It contains 155 currency definitions and 715 locale definitions out of the box. It handles unusually formatted currencies, such as the INR.

See VERSIONS.md to see which versions of tabulator-rails bundle which versions of currencyFormatter.js.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'CurrencyFormatter-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install CurrencyFormatter-rails
    
And then edit your app/assets/stylesheets/application.js file to look something like:
``` css
/*
*= require_self
*= require currencyFormatter
*= require_tree .
*/
```

## Usage

View [CurrencyFormatter.js](https://osrec.github.io/currencyFormatter.js/) for complete useage information.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/tanvir002700/CurrencyFormatter-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the CurrencyFormatter::Rails project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/tanvir002700/CurrencyFormatter-rails/blob/master/CODE_OF_CONDUCT.md).
