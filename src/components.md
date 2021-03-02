---
layout: layout.njk
templateEngineOverride: njk,md
title: Component Index
---
# {{ title }}




{% import '_callout.njk' as macro %}
{{ macro.callout(
    "[content]Here is the main text of the callout", 
    "[ctatext]Call to Action Button", 
    "[ctalink]https://apple.com"
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
    "[linktext]our"
)}}
