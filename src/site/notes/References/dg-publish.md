---
{"dg-publish":true,"permalink":"/references/dg-publish/","ctime":"2026-10-11T23:57:16.918+02:00","mtime":"2026-10-14T16:23:48.046+02:00","dg-note-properties":{"date created":"2026-10-11, 23 57","date modified":"2026-10-13, 17 35","sector":null,"semester":null,"class":null,"form":null,"part":null,"tags":[]}}
---


# dg-publish


```base
views:
  - type: table
    name: View
    filters:
      and:
        - file.hasProperty("dg-publish")
    order:
      - date created
      - file.name
      - dg-publish
    sort:
      - property: dg-publish
        direction: ASC
      - property: file.name
        direction: DESC
      - property: formula.Untitled
        direction: DESC
    columnSize:
      file.name: 423

```
