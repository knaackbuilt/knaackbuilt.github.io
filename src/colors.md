---
layout: layout.njk
title: Colors
---
{% from './_includes/colors/_macro.njk' import colors %}
# {{ title }}
<p class="bg-blue-800"></p>


{{ colors({ 
    colortitle: "Yellow-ish", 
    rgba: "rgba(30, 64, 175, 1)",
    twcolor: "bg-yellow-300",
    rgbahover: "rgba(96, 165, 250, 1)",
    twcolorhover: "bg-yellow-400"
})}}

{{ colors({ 
    colortitle: "Brown-ish", 
    rgba: "rgba(16, 185, 129, 1)",
    twcolor: "bg-yellow-700",
    rgbahover: "rgba(96, 165, 250, 1)",
    twcolorhover: "bg-yellow-800"
})}}

{{ colors({ 
    colortitle: "Blue-ish", 
    rgba: "rgba(55, 65, 81, 1)",
    twcolor: "bg-blue-500",
    rgbahover: "rgba(129, 140, 248, 1)",
    twcolorhover: "bg-blue-700"
})}}

{{ colors({ 
    colortitle: "Indigo-ish", 
    rgba: "rgba(55, 48, 163, 1)",
    twcolor: "bg-indigo-50",
    rgbahover: "rgba(129, 140, 248, 1)",
    twcolorhover: "bg-indigo-300"
})}}

{{ colors({ 
    colortitle: "Gray-ish", 
    rgba: "rgba(55, 65, 81, 1)",
    twcolor: "bg-gray-300",
    rgbahover: "rgba(129, 140, 248, 1)",
    twcolorhover: "bg-gray-700"
})}}

{{ colors({ 
    colortitle: "Gray-ish x2", 
    rgba: "rgba(55, 65, 81, 1)",
    twcolor: "bg-gray-600",
    rgbahover: "rgba(129, 140, 248, 1)",
    twcolorhover: "bg-gray-900"
})}}


