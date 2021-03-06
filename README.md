# month [![NPM version](https://badge.fury.io/js/month.svg)](http://badge.fury.io/js/month)

> Get the name or number of the current month or any month of the year.

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i month --save
```

## Usage

```js
var month = require('month');

month();
//=> 'January' (current month full name)

month('M');
//=> '1' (current month number)

month('MM');
//=> '01' (current month number, zero-filled)

month('MMM');
//=> 'Jan' (current month abbreviation)

month('MMMM');
//=> 'January' (current month full name)

month('January');
//=> '12' (number of the given month number)

month(1);
//=> 'January' (name of the given month number)

month(2);
//=> 'February'
```

## Related projects

* [days](https://github.com/jonschlinkert/days): Days of the week.
* [iso-week](https://github.com/jonschlinkert/iso-week): Get the ISO week of the year.
* [months](https://github.com/jonschlinkert/months): Months of the year.
* [o-clock](https://github.com/jonschlinkert/o-clock): Simple utility for displaying the time in 12-hour clock format.
* [seconds](https://github.com/jonschlinkert/seconds): Get the number of seconds for a minute, hour, day and week.
* [weekday](https://github.com/jonschlinkert/weekday): Get the name and number of the current weekday. Or get the name of the… [more](https://github.com/jonschlinkert/weekday)
* [week](https://github.com/jonschlinkert/week): Get the current week number.
* [year](https://github.com/jonschlinkert/year): Simple utility to get the current year with 2 or 4 digits.

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/datetime/month/issues/new)

## Author

**Jon Schlinkert**

+ [github/datetime](https://github.com/datetime)
+ [twitter/datetime](http://twitter.com/datetime)

## License

Copyright © 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on May 25, 2015._