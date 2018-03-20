# horizontal-bar

A Polymer Element showing a sized, labeled, colored bar with options for a checkbox with toggle behavior, an icon, an image, or a link.

### Example
```html
<horizontal-bar
  name="Test"
  count="123"
  max="456">
</horizontal-bar>
```

### Styling

`<horizontal-bar>` provides the following custom properties and mixins for styling:

Custom property                      | Description                                        | Default
-------------------------------------|----------------------------------------------------|--------
`--horizontal-bar-color`             | The color of the bar.                              | --paper-grey-300
`--horizontal-bar-count-color`       | The color of the count label.                      | --paper-grey-900
`--horizontal-bar-height`            | The height of the bar.                             | 20px
`--horizontal-bar-title-color`       | The color of the title label.                      | --paper-grey-900
`--horizontal-bar-title-hover-color` | The color of the title label on hover (if a link). | --paper-indigo-900

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

