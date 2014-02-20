*This repository is a mirror of the [component](http://component.io) module [code42day/hilo](http://github.com/code42day/hilo). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/code42day-hilo`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# hilo

  Add .bottom and .top classes to document body when page is all the way up or down.
  Check out the [live demo](http://code42day.github.io/hilo)

## Installation

  Install with [component(1)](http://component.io):

    $ component install code42day/hilo

## API

```javascript
require('hilo')();
```

`document.body` will have `.top` class when the top of the page is displayed
and the `.bottom` class when the bottom of the page is displayed

## License

  MIT
