---
{"dg-publish":true,"permalink":"/references/td/","ctime":"2026-10-05T11:38:24.338+02:00","mtime":"2026-10-13T17:34:01.312+02:00","dg-note-properties":{"date created":"2026-10-05, 11 38","date modified":"2026-10-05, 11 41","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":[]}}
---


# TD

```base
views:
  - type: table
    name: Table
    filters:
      and:
        - semester == link("S3")
        - "!form.isEmpty()"
    order:
      - file.name
      - semester
      - class
      - form
    sort:
      - property: form
        direction: ASC
      - property: semester
        direction: ASC

```
