---
layout: layout.njk
title: Component Index
---
# {{ title }}


{% import '_callout.njk' as macro %}
{{ macro.callout(
    "[content]Here is the main text of the callout", 
    "[ctatext]Call to Action Button", 
    "[ctalink]../documents/tableau-quick-styles.pdf"
    )}}


{% import '_details.njk' as macro %}
{{ macro.details(
    "[title]Detail Title", 
    "[content]Product owners should be multi-disciplinarian representatives of content, design, UX, engineering, and strategy. Effective product owners have experience in all these areas (and more) and are able to blend diverse backgrounds into a well organized framework that models success for the team they work within."
    ) }}


{% import '_card.njk' as macro %}
{{ macro.card(
    "[title]one",
    "[content]two",
    "[link]https://apple.com",
    "[linktext]our",
    "[imgsource]captain_ahab.jpg",
    "[imgalt]Captain ahab"
)}}
{{ macro.card(
    "[title]one",
    "[content]two",
    "[link]https://apple.com",
    "[linktext]our",
    "[imgsource]captain_ahab.jpg",
    "[imgalt]Captain ahab"
)}}
{{ macro.card(
    "[title]one",
    "[content]two",
    "[link]https://apple.com",
    "[linktext]our",
    "[imgsource]captain_ahab.jpg",
    "[imgalt]Captain ahab"
)}}

1. one
2. two
3. three

## and some headings
and some text