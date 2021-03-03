---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{ title }}

{% from './_includes/details/_macro.njk' import details %}
{% from './_includes/callout/_macro.njk' import callout%}
{% from './_includes/button/_macro.njk' import button %}

{{ button({ 
    link: "/components", 
    buttontext: "Component Index",
    arialabel: "a link to component index"
})}}

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