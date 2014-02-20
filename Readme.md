*This repository is a mirror of the [component](http://component.io) module [component/variance](http://github.com/component/variance). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-variance`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# variance

  variance utility

## Installation

    $ component install component/variance

## API

### variance(array)

  Return the variance of `array`:

```js
variance([1,5,6,1,2,0])
```

### variance(array, fn)

  variance of `array` with callback `fn(val, i)`:

```js
var age = variance(users, function(u){ return u.age })
```

### variance(array, string)

  variance of `array` with the given property `string`:

```js
var age = variance(users, 'age')
```

# License

  MIT
