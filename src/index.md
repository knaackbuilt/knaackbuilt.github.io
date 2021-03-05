---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{ title }}

{% from './_includes/details/_macro.njk' import details %}
{% from './_includes/callout/_macro.njk' import callout%}
{% from './_includes/button/_macro.njk' import button %}
{% from './_includes/card/_macro.njk' import card %}

# Projects
{{ card({ 
    title:"The card title",
    content:"the card content",
    link:"https://apple.com",
    linktext:"link text"
})}}
{{ card({ 
    title:"The card title",
    content:"the card content",
    link:"https://apple.com",
    linktext:"link text"
})}}
{{ card({ 
    title:"The card title",
    content:"the card content",
    link:"https://apple.com",
    linktext:"link text"
})}}

{{ callout({ 
    content:"Like what you see? Send me an email!",
    ctalink:"mailto:jeffknaack@gmail.com",
    ctatext:"Reach out!"
})}}

