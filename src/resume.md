---
layout: layout.njk
title: Resume of Jeffrey H.S. Knaack
---
{% from './_includes/details/_macro.njk' import details %}
{% from './_includes/callout/_macro.njk' import callout %}
{% from './_includes/card/_macro.njk' import card %}
{% from './_includes/button/_macro.njk' import button %}
# {{ title }}


Do you want the short version or the long version?

{{ callout({ 
    title:"The Short Version",
    content:"If you want to see the bullet points only, skim this page quick.",
    ctalink:"/resume-short",
    ctatext:"Key Points Resume"
})}}

{{ callout({ 
    title:"The Long Version",
    content:"If you want to see an expanded version of stuff I've done, settle in here.",
    ctalink:"/resume-long",
    ctatext:"The Whole Thing"
})}}
