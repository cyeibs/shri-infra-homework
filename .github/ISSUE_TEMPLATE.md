---
title: Release ${{ github.run_number }}
assignees: 
labels: release
---
**Дата:** {{ date }}
**Автор релиза:** {{ payload.sender.login }}
**Номер версии:** ${{ github.run_number }}
**Коммиты:**
{{ payload.commits }}
**Docker образ:**
cr.yandex/crpk6ta1ej2mrcheq6qs/app:${{ github.run_number }}
