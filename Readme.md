*This repository is a mirror of the [component](http://component.io) module [yields/slug](http://github.com/yields/slug). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-slug`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# slug

  slug generator

## Installation

    $ component install yields/slug

## API

#### slug(str[, opts])

```javascript
slug('foo bar');
// > foo-bar
slug('foo bar', { separator: '_' });
// > foo_bar
slug('foo bar', { replace: /o/g });
// > f-bar
```

## Tests

    $ make test

## License

  MIT
