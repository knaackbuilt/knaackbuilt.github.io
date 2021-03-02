---
layout: layout.njk
permalink: "/{{ directory }}/{{ filename }}.html"
title: DIRECTORY TEST
directory: newdirectory
filename: index
---
# {{ title }}


{% import '_callout.njk' as macro %}
{{ macro.callout(
    "[content]I Changed the callout", 
    "[ctatext]Call to Action Button", 
    "[ctalink]https://apple.com"
    )}}
