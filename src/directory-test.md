---
layout: layout.njk
templateEngineOverride: njk,md
permalink: "/{{ directory }}/{{ filename }}.html"

title: Component Index
directory: newdirectory
filename: index
---
# {{ title }}


{% import '_callout.njk' as macro %}
{{ macro.callout(
    "[content]INDEX the callout", 
    "[ctatext]Call to Action Button", 
    "[ctalink]https://apple.com"
    )}}
