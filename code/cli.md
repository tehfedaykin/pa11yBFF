## pa11y cli is fun ..

```bash
pa11y https://revolutionconf.com/

pa11y --report html https://revolutionconf.com/ > revconf-report.html

pa11y --ignore "warning;notice" --report html https://revolutionconf.com/ > revconf-report.html

pa11y --standard Section508 https://revolutionconf.com/

```

but not super useful in a typical workflow