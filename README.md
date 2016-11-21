# Customer Number Validation

A few Ruby snippets showing how you can use Nexmo Number Insight to validate and cleanup phone numbers.

## Prerequisites

* [A Nexmo account](https://dashboard.nexmo.com/sign-up)
* [Ruby 2.1+](https://www.ruby-lang.org/) and [Bundler](http://bundler.io/)

## Getting started

```sh
# clone this repository
git clone git@github.com:Nexmo/ruby-ni-customer-number-validation.git
# change to folder
cd ruby-ni-customer-number-validation
# install dependencies
bundle install
# create a .env
cp .env.example .env
```

Next you will need to sign up for a Nexmo account and get your API credentials from the API dashboard and put them in your `.env`
file.

Then you can run every script as follows.

```sh
ruby snippets/1_validation.rb
```

## Usage

This is not an app but rather a set of snippets showing how Nexmo Number Insight can be used to validate and clean up numbers, as well as be used to determine the channel type and cost of a number.

The scripts are:

* `1_country_code.rb` shows how to find the country code for a number
* `2_cleanup.rb` shows how to turn a local number into its international format
* `3_cost.rb` is a little extra that shows how to then calculate the pricing of a number
* `4_channels.rb` shows how to extract more details, like the channel format (landline or mobile) from a number
* `5_validation.rb` shows how to validate a number is likely to be a real number

## License

This project is licensed under the [MIT license](LICENSE).
