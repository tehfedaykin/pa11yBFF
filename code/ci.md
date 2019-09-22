.pa11yci

```json
{
  "defaults": {
    "standard": "WCAG2AAA"
  },
  "urls": [
    "http://localhost:4200/",
    "http://localhost:4200/posts",
    {
      "url": "http://localhost:4200/cast",
      "actions": [
        "click element #myButton",
        "wait for element modal-container to be hidden"
      ]
    }
  ]
}
```