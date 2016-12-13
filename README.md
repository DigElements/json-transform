# json-transform

A Polymer Element that transforms a JSON object into another JSON object using a transform function.

### Example
```html
<json-transform
  data-in="[[data]]"
  data-out="{{newData}}"
  transform-function="[[transform]]">
</json-transform>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

