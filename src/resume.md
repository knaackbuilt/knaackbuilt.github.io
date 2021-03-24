---
layout: layout.njk
title: Resume of Jeffrey H.S. Knaack
---
{% from './_includes/components.njk' import details,callout,card,button,jobtitle,sideside,colors %}
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
