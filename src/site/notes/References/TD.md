---
{"dg-publish":true,"permalink":"/references/td/","dg-note-properties":{"date created":"2026-10-05, 11 38","date modified":"2026-10-05, 11 41","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":[]}}
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
