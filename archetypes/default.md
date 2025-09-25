+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
author = '{{ .Site.Params.Author.Name }}'
summary = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
