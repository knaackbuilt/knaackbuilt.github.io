---
layout: layout-homepage.njk
title: Knaackbuilt.dev
---
# {{title}}
{% from './_includes/components.njk' import details,callout,card,button,jobtitle,sideside,colors %}


{{ card({ 
    cards: [
        {
        title:"Resume",
        content:"My take on a digital resume.",
        link:"/resume",
        linktext:"Read about what I have done"
        },
        {
        title:"Bookmarks",
        content:"Resources I Use",
        link:"/ideas/bookmarks",
        linktext:"Find some useful stuff"
        },
        {
        title:"Color set",
        content:"The colors used here",
        link:"/colors",
        linktext:"Color meeeee"
        }
        
        
    ]
    
})}}



{{ callout({ 
    content:"Send me an email!",
    ctalink:"mailto:jeffknaack@gmail.com",
    ctatext:"Reach out!"
})}}

