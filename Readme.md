
# resizable

  UI Resizable component, make any element resizable.

## Installation

    $ component install chemzqm/resizable

## Example

```js
var resizable = require('resizable')(myElement);
resizable.set('handles', 'se, s, e');
resizable.bind();
```

## API

### resizable(el[, opts])

  Create a new `Resizable` instance.

### resizable.set(optname, optvalue)

  Set options.

### resizable.bind()

  bind events and append handles.

### resizable.unbind()

  unbind events and remove handles.
   

## License

  MIT
