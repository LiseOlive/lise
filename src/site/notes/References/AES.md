---
{"dg-publish":true,"permalink":"/references/aes/","ctime":"2026-10-05T11:34:57.215+02:00","mtime":"2026-11-05T15:03:40.750+01:00","dg-note-properties":{"date created":"2026-10-05, 11 34","date modified":"2026-11-05, 15 03","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":[]}}
---


# AES


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

