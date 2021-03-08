---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{ title }}
## This site is a work in progress
{% from './_includes/details/_macro.njk' import details %}
{% from './_includes/callout/_macro.njk' import callout%}
{% from './_includes/button/_macro.njk' import button %}
{% from './_includes/card/_macro.njk' import card %}

# Projects
{{ card({ 
    title:"Color set",
    content:"The colors used here",
    link:"/colors",
    linktext:"Color meeeee"
})}}
{{ card({ 
    title:"Components",
    content:"The components used here",
    link:"/components",
    linktext:"Components"
})}}
{{ card({ 
    title:"Resume",
    content:"Work in progress!,
    link:"/resume",
    linktext:"Beware - work in progress"
})}}

{{ callout({ 
    content:"Send me an email!",
    ctalink:"mailto:jeffknaack@gmail.com",
    ctatext:"Reach out!"
})}}

