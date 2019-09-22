## Async, await

```javascript
async function runPa11y() {
  try {
    const results = await pa11y('http://localhost:4200');
    //do something with results
  } catch (error) {
    //deal with the error
  }
};
runPa11y();
```