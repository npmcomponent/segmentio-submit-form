*This repository is a mirror of the [component](http://component.io) module [segmentio/submit-form](http://github.com/segmentio/submit-form). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-submit-form`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# submit-form

  Submit a form programmatically, triggering its submit handlers, since the native `submit` method doesn't...

## Installation

    $ component install segmentio/submit-form

## Example

```js
var submit = require('submit-form');
var form = document.querySelector('form');

form.onsubmit = function (e) {
  console.log('submitted!');  
};

submit(form);
// "submitted!"
```

## API

### submit(form)
  
  Submit a `form` programmatically, triggering its submit handlers.
  
## License

  MIT
