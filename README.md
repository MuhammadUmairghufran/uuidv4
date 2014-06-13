# uuid

uuid creates UUIDs.

## Installation

At the moment, installation of this module must be made manually.

## Quick start

The first thing you need to do is to integrate uuid into your project by using the `require` function.

```javascript
var uuid = require('uuid');
```

Then you can create UUIDs. To do so simply call the `uuid` function.

```javascript
console.log(uuid());
// => 11bf5b37-e0b8-42e0-8dcf-dc8c4aefc000
```

## Running the tests

uuid has been developed using TDD. To run the tests, go to the folder where you have installed uuid to and run `npm test`. You need to have [mocha](https://github.com/visionmedia/mocha) installed.

    $ npm test

Additionally, this module can be built using [Grunt](http://gruntjs.com/). Besides running the tests, Grunt also analyses the code using [JSHint](http://www.jshint.com/). To run Grunt, go to the folder where you have installed uuid and run `grunt`. You need to have [grunt-cli](https://github.com/gruntjs/grunt-cli) installed.

    $ grunt