## Result Output

```javascript
[{
  documentTitle: 'The title of the page that was tested',
  pageUrl: 'The URL that Pa11y was run against',
  issues: [
  {
    code: 'WCAG2AA.Principle1.Guideline1_1.1_1_1.H30.2',
    context: '<a href="http://example.com/"><img src="example.jpg" alt=""/></a>',
    message: 'Img element is the only content of the link, but is missing alt text. The alt text should describe the purpose of the link.',
    selector: 'html > body > p:nth-child(1) > a',
    type: 'error',
    typeCode: 1
  }
  // more issues appear here
  ]
}]
```