---
layout: layout.njk
title: Jeffrey H.S. Knaack
---
{% from './_includes/components.njk' import details,callout,card,button,jobtitle,sideside,avatar %}
<h1 class="my-4 py-4 text-center">{{ title }}</h1>

{{ avatar({ 
    src: "/img/avatar.jpg",
    alt: "it's my face and I'm smiling and wearing a baseball cap that says dad and I have an awesome beard and glasses"
})}}

> I build simple and functional digital products while advocating for inclusive, accessible, and open technologies. He/Him. Pronounced Kuh-naa-ck - not a silent "k." (German origin)

For a more detailed and nuanced resume discussion, [please see my gitbook resume](https://app.gitbook.com/@jeffknaack/s/jeffrey-h-s-knaack-resume/)

{{ jobtitle({ 
    jobtitle: "Digital Product Manager & Solutions Architect",
    organization: "New York State Digital Service",
    years: "2020 - present"
})}}
{{ sideside({ 
    lefttitle:"Overview",
    righttitle:"Enthusiastic about:",
    text:"I'm the first Digital Product Manager in NYS ",
    keypoint:"Accessibility, UX & UI, foundational web languages, complex and creative problem solving.  "
})}}
{{ details({ 
    title: "Types of things I collaborated on", 
    content: "Website design, accessibility compliance, user development, information architecture and analysis, maintenance,  "
})}}
{{ details({ 
    title: "What I used", 
    content: "html, css, javascript, AGILE methods, JIRA, Trello, VSCode, git, github, gitbook, all the best communications tools, drupal, 11ty/eleventy, tailwind, the classics like word and excel, Adobe Suite but mainly InDesign, BigCommerce, Oracle, Azure Dev Ops, various cool Microsoft tools in the enterprise platform like forms/lists/planner/power automate/etc. "
})}}



{{ jobtitle({  
    jobtitle: "Digital Communications Manager",
    organization: "New York State Office of General Services",
    years: "2016 - 2020"
})}}

{{ details({ 
    title: "Things I worked on", 
    content: "this is the content"
})}}

{{ sideside({ 
    lefttitle:"The Short Version",
    righttitle:"Key Point",
    text:"This system, its applications and data belong to the State of New York. Access and use is limited to authorized users for authorized purposes. Actual or attempted unauthorized use is not permitted and may be a crime subjecting you to ",
    keypoint:"I have led projects across diverse teams and completed them on time and under budget"
})}}