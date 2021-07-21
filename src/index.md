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
        content:"My take on a digital resume that is not even close to complete.",
        link:"/resume",
        linktext:"Read about what I have done"
        },
        {
        title:"Bookmarks",
        content:"Resources I use and would very much like not to forget.",
        link:"/ideas/bookmarks",
        linktext:"Find some useful stuff"
        },
         {
        title:"HTML Journey",
        content:"My Journey to possibly understanding HTML, with a focus on accessibility and good semantics.",
        link:"/html-journey",
        linktext:'See how little I know'
        }
        
        
    ]
    
})}}

<p class="my-8 mx-4">One thing I was inspired to do here is build simply and focus on good semantics. It makes you think more about what you are building and why.</p>

{{ callout({ 
    content:"Send me an email!",
    ctalink:"mailto:jeffknaack@gmail.com",
    ctatext:"Reach out!"
})}}

