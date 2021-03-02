---
layout: layout.njk
templateEngineOverride: njk,md
title: Component Index
---
# {{ title }}

{% import '_callout.njk' as macro %}
{{ macro.callout('Here is the main text of the callout', 'Call to Action Button', 'https://apple.com')}}

{% import '_details.njk' as macro %}
{{ macro.details('Detail Title', 'Product owners should be multi-disciplinarian representatives of content, design, UX, engineering, and strategy. Effective product owners have experience in all these areas (and more) and are able to blend diverse backgrounds into a well organized framework that models success for the team they work within. ') }}

{% import '_details.njk' as macro %}
{{ macro.details('Digital Product Manager', 'As a digital product manager for etc etc') }}
