---
{"dg-publish":true,"permalink":"/references/cm/","ctime":"2026-10-05T11:37:45.132+02:00","mtime":"2026-11-05T15:03:57.967+01:00","dg-note-properties":{"date created":"2026-10-05, 11 37","date modified":"2026-11-05, 15 03","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":[]}}
---


# CM

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
