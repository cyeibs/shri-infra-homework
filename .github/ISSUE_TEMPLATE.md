---
title: Release {{ github.run_number }}
labels: release
---
**Дата:** {{ date | date('dddd, MMMM Do') }}
**Автор релиза:** {{ payload.sender.login }}
**Номер версии:** {{ env.RUN_NUMBER }}
**Коммиты:**
{{ github.event.head_commit.message }}
**Docker образ:**
cr.yandex/crpk6ta1ej2mrcheq6qs/app:{{ github.run_number }}
