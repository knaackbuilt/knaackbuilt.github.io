---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{ title }}

{% from './_includes/details/_macro.njk' import details %}
{% from './_includes/callout/_macro.njk' import callout%}



{{ details({ 
    title: "NUMBER 2", 
    content: "this is the content"
})}}

{{ details({ 
    title: "NUMBER 3", 
    content: "this is the content"
})}}





{{ callout({ 
    content:"huh",
    ctalink:"https://apple.com",
    ctatext:"Applessssss"
})}}

{{ details({ 
    title: "NUMBER 3", 
    content: "this is the content"
})}}
{{ details({ 
    title: "NUMBER 3", 
    content: "this is the content"
})}}
{{ details({ 
    title: "NUMBER 3", 
    content: "this is the content"
})}}