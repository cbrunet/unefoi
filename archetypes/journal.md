+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date.Format "2006-01-02" }}
image = 'images/header.png'
preview = 'images/preview.png'
file = '{{ .Date.Format "2006_01_02" }}.pdf'
draft = true
+++
