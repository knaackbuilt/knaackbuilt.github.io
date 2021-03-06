---
layout: layout.njk
title: Colors
---
{% from './_includes/colors/_macro.njk' import colors %}
# {{ title }}



{{ colors({ 
    colortitle: "Yellow-ish", 
    rgba: "rgba(252, 211, 77, 1)",
    twcolor: "bg-yellow-300",
    rgbahover: "rgba(251, 191, 36, 1)",
    twcolorhover: "bg-yellow-400"
})}}

{{ colors({ 
    colortitle: "Brown-ish", 
    rgba: "rgba(180, 83, 9, 1)",
    twcolor: "bg-yellow-700",
    rgbahover: "rgba(146, 64, 14, 1)",
    twcolorhover: "bg-yellow-800"
})}}

{{ colors({ 
    colortitle: "Blue-ish", 
    rgba: "rgba(59, 130, 246, 1)",
    twcolor: "bg-blue-500",
    rgbahover: "rgba(29, 78, 216, 1)",
    twcolorhover: "bg-blue-700"
})}}

{{ colors({ 
    colortitle: "Indigo-ish", 
    rgba: "rgba(238, 242, 255, 1)",
    twcolor: "bg-indigo-50",
    rgbahover: "rgba(165, 180, 252, 1)",
    twcolorhover: "bg-indigo-300"
})}}

{{ colors({ 
    colortitle: "Gray-ish", 
    rgba: "rgba(209, 213, 219, 1)",
    twcolor: "bg-gray-300",
    rgbahover: "rgba(55, 65, 81, 1)",
    twcolorhover: "bg-gray-700"
})}}

{{ colors({ 
    colortitle: "Gray-ish x2", 
    rgba: "rgba(75, 85, 99, 1)",
    twcolor: "bg-gray-600",
    rgbahover: "rgba(17, 24, 39, 1)",
    twcolorhover: "bg-gray-900"
})}}
