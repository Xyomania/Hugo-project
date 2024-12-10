---
title: "{{ .Title }}"
date: "{{ .Date }}"
# weight: {{ .Weight }} 
# aliases: ["/{{ .Alias }}"]
tags: [{{ .Tags }}]
author: "{{ .Author }}"
# author: ["{{ .Author1 }}", "{{ .Author2 }}"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "{{ .Description }}"
canonicalURL: "{{ .CanonicalURL }}"
disableHLJS: {{ .DisableHLJS }} # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "{{ .CoverImage }}"
    alt: "{{ .CoverAlt }}" # alt text
    caption: "{{ .CoverCaption }}" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "{{ .EditPostURL }}"
    Text: "{{ .EditPostText }}" # edit text
    appendFilePath: true # to append file path to Edit link
---
