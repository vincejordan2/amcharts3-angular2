# Example

This project is based on the [Angular QuickStart seed](https://angular.io/docs/ts/latest/guide/setup.html).

## Development server

Run `npm install` and then `npm start` to run the server. Navigate to `http://localhost:3000/`. The app will automatically reload if you change any of the source files.

----

If you are creating your own QuickStart seed, you will need to add `amcharts3-angular2` to your `src/systemjs.config.js` file, like this:

```js
System.config({
  map: {
    'amcharts3-angular2': 'node_modules/amcharts3-angular2/index.js'
  }
});
```
