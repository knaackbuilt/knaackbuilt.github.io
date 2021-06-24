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
        }
        
        
    ]
    
})}}

<p class="my-8 mx-4">One thing I was inspired to do here is build this website using few div's or span's and really try to focus on good semantic html. It makes you think more about what you are building and why.</p>

{{ callout({ 
    content:"Send me an email!",
    ctalink:"mailto:jeffknaack@gmail.com",
    ctatext:"Reach out!"
})}}

