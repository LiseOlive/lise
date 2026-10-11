---
{"dg-publish":true,"permalink":"/references/aes/","dg-note-properties":{"date created":"2026-10-05, 11 34","date modified":"2026-10-05, 11 36","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":[]}}
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

