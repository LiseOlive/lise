---
{"dg-publish":true,"permalink":"/references/code/","ctime":"2026-01-20T12:10:43.000+01:00","mtime":"2026-10-13T17:34:02.738+02:00","dg-note-properties":{"date created":"2026-01-20, 12 10","date modified":"2026-10-05, 12 42","sector":"[[References]]","semester":null,"class":null,"form":"[[References/Code]]","part":null,"tags":[]}}
---


# Code


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - sector == link("Code")
        - '!file.inFolder("References")'
    order:
      - file.name
      - class
    sort:
      - property: file.name
        direction: ASC
      - property: class
        direction: ASC
      - property: date created
        direction: DESC
      - property: file.basename
        direction: DESC
      - property: sector
        direction: ASC
    columnSize:
      file.name: 480

```

