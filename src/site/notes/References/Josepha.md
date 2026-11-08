---
{"dg-publish":true,"permalink":"/references/josepha/","ctime":"2026-11-08T15:55:43.020+01:00","mtime":"2026-11-08T15:55:43.020+01:00","dg-note-properties":{"date created":"2026-11-08, 15 55","date modified":"2026-11-08, 15 55","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":[]}}
---


# Josepha

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

