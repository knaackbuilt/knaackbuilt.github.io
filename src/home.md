---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{ title }}

{% import '_card.njk' as macro %}
{{ macro.card(
    "[title]one",
    "[content]two",
    "[link]https://apple.com",
    "[linktext]our",
    "[imgsource]captain_ahab.jpg",
    "[imgalt]Captain ahab"
)}}




