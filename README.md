# German bank tools

Ruby gem to validate, normalize/prettify and to some extent interpret German Bankleitzahl (BLZ) and bank account numbers.

## Installation

Add this line to your application's Gemfile:

    gem 'banktools-de'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install banktools-de

## Usage

(Very much in progress. Expect this list to change rapidly.)

    blz = BankTools::DE::BLZ.new("10070024")
    blz.normalize  # => "100 700 24"

## Tests

    rspec
    # or: rake

## Also see

* [BankTools::SE (Swedish)](https://github.com/barsoom/banktools-se)
* [iban-tools](https://github.com/iulianu/iban-tools)

## Credits and license

By [Henrik Nyh](http://henrik.nyh.se) for [Barsoom](http://barsoom.se) under the MIT license:

Copyright (c) 2014 Barsoom AB

MIT License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
