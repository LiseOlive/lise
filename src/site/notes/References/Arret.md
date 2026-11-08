---
{"dg-publish":true,"permalink":"/references/arret/","ctime":"2026-11-08T18:59:29.528+01:00","mtime":"2026-11-08T18:59:29.529+01:00","dg-note-properties":{"date created":"2026-11-08, 18 55","date modified":"2026-11-08, 18 55","sector":"[[References]]","semester":null,"class":null,"form":"[[References/Arret]]","part":null,"tags":[]}}
---


# Arret


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - form == link("Arret")
        - '!file.inFolder("References")'
    order:
      - file.name
      - class
    sort:
      - property: file.name
        direction: ASC
      - property: class
        direction: DESC
      - property: date created
        direction: DESC
      - property: file.basename
        direction: DESC
      - property: sector
        direction: ASC
    columnSize:
      file.name: 480

```

