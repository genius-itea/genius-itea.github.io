---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
params:
    # nationality: Germany
    link: https://example.com
    national_coordinator: false
    # logo: logo.png
---
