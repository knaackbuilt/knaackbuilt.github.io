---
layout: layout.njk
title: Component Index
---
{% from './_includes/details/_macro.njk' import details %}
{% from './_includes/callout/_macro.njk' import callout %}
{% from './_includes/card/_macro.njk' import card %}
{% from './_includes/button/_macro.njk' import button %}
# {{ title }}


{{ details({ 
    title: "NUMBER 2", 
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

{{ callout({ 
    content:"huh",
    ctalink:"https://apple.com",
    ctatext:"Applessssss"
})}}

{{ card({ 
    title:"The card title",
    content:"the card content",
    link:"https://apple.com",
    linktext:"link text",
    imgsource:"/img/captain_ahab.jpg",
    imgalt:"captain ahab from moby dick"
})}}

{{ button({ 
    link: "https://apple.com", 
    buttontext: "this is the button",
    arialabel: "a button to something"
})}}

1. one
2. two
3. three

## and some headings
and some text