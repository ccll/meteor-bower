# Bower for Meteor

[Bower](http://bower.io/) is a popular repository of client-side JavaScript
librairies. In your `smart.json` you can specify a dictionnary of bower packages:

```json
{
  "meteor": { ... },
  "packages": { ... },
  "bower": {
    "select2": "3.4.5",
    "backbone": "1.1.0"
  }
}
```

You now have `select2` and `backbone` librairies in your client application!

> To ensure that other people running your app will always get the exact same
dependencies you must always provide a version number.

If you don't want to use the `smart.json` file for that purpose, you can use a
dedicated file named `bower.json`.

## Contribute

Contributions are very welcome, whether it is for a
[bug report](https://github.com/mquandalle/meteor-bower/issues/new), a fix or a
new functionnality proposition.

## License

This code is published under the [MIT license](LICENSE).
