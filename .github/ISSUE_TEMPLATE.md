---
title: Release {{ env.TAG_NAME }}
labels: RELEASE
date: {{ date | date('dddd, Do MMMM YYYY') }}
---
Changelog:
{{ env.CHANGELOG }}.
