# Isis plugin: Stock Ticker

This plugin adds a [Yahoo Finance stock ticker](http://finance.yahoo.com/) command to the [Isis chatbot](https://github.com/silentgrowl/isis)

## Installation

Copy config/stockticker.csv.example from the gem repo and save as ```config/stockticker.csv``` in your Isis installation.

Edit the config/stockticker.csv file to define a comma-separated value list of stock symbols to include in the ticker report.

Add this line to your Isis installation's Gemfile:

``ruby
gem 'isis-plugin-stockticker'
``

And then execute:

    $ bundle

## Usage

To post the latest stock ticker report into a room, type ```!stockticker```, ```!stocks```, ```!stockquotes```, ```!ticker```, or ```!yahoofinance``` into chat.
