---
layout: layout.njk
title: My Journey to HTML (in)competency
---

# {{title}}
{% from '../_includes/components.njk' import details,callout,card %}

{{ card({ 
    cards: [
        {
        title:"Tables and Roles",
        content:'Is <table role="grid"> ok?',
        link:"/html-journey/table-role",
        linktext:"2 minute read"
        }
        
        
    ]
    
})}}