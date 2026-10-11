---
{"dg-publish":true,"permalink":"/references/dashboard/","tags":["gardenEntry"],"dg-note-properties":{"date created":"2026-10-05, 11 20","date modified":"2026-10-09, 14 11","sector":"[[References]]","semester":null,"class":null,"form":null,"part":null,"tags":["gardenEntry"]}}
---


# Dashboard
 

```base
views:
  - type: cards
    name: View
    filters:
      and:
        - semester == link("S3")
        - sector == link("Dashboard")
    sort:
      - property: file.ctime
        direction: ASC
    cardSize: 240
    imageAspectRatio: 0.55
    image: note.cover

```

