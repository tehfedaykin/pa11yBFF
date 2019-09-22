## Actions

```javascript
pa11y('http://localhost:4200', {
  actions: [
    'click element #tab-1',
    'wait for element #tab-1-content to be visible',
    'set field #fullname to John Doe',
    'check field #terms-and-conditions',
    'uncheck field #subscribe-to-marketing',
    'wait for #modal to be visible',
    'wait for fragment to be #page-2',
    'wait for path to not be /login'
  ]
});
```

Sets of instructions to run before accessibility tests are run.