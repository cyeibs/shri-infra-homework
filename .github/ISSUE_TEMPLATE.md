---
title: Release {{ github.run_number }}
labels: release
---
**Дата:** {{ date }}
**Автор релиза:** {{ github.actor }}
**Номер версии:** {{ github.run_number }}
**Коммиты:**
{{ github.event.head_commit.message }}
**Docker образ:**
cr.yandex/crpk6ta1ej2mrcheq6qs/app:{{ github.run_number }}
