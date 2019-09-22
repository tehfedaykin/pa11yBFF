## log

```javascript
pa11y('http://localhost:4200', {
  log: {
    debug: console.log.bind(console),
    error: console.error.bind(console),
    info: console.info.bind(console)
  }
});
```