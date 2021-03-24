---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{ title }}
{% from './_includes/components.njk' import details,callout,card,button,jobtitle,sideside,colors %}
## This site is a work in progress
## Projects

{{ card({ 
    cards: [
        {
        title:"Color set",
        content:"The colors used here",
        link:"/colors",
        linktext:"Color meeeee"
        },
        {
        title:"Resume",
        content:"My take on a digital resume.",
        link:"/resume",
        linktext:"Read about what I have done"
        }
    ]
    
})}}



{{ callout({ 
    content:"Send me an email!",
    ctalink:"mailto:jeffknaack@gmail.com",
    ctatext:"Reach out!"
})}}

