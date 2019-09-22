## Using the JS Interface

```javascript
var pa11y = require('pa11y');

pa11y('http://localhost:4200/', {
  //config options
}).then((results) => {
  // Do something with the results
  console.log(result);
});
```