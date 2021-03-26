---
layout: layout.njk
title: Colors
---
{% from './_includes/components.njk' import details,callout,card,button,jobtitle,sideside,colors %}
# {{ title }}



{{ colors({ 
    color: [
        {
        colortitle: "Yellow-ish", 
        rgba: "rgba(252, 211, 77, 1)",
        twcolor: "bg-yellow-300",
        rgbahover: "rgba(251, 191, 36, 1)",
        twcolorhover: "bg-yellow-400"
        },
        {colortitle: "Brown-ish", 
        rgba: "rgba(180, 83, 9, 1)",
        twcolor: "bg-yellow-700",
        rgbahover: "rgba(146, 64, 14, 1)",
        twcolorhover: "bg-yellow-800"
        },
        {
        colortitle: "Blue-ish", 
        rgba: "rgba(59, 130, 246, 1)",
        twcolor: "bg-blue-500",
        rgbahover: "rgba(30, 64, 175, 1)",
        twcolorhover: "bg-blue-800"
        },
        {
        colortitle: "Indigo-ish", 
        rgba: "rgba(238, 242, 255, 1)",
        twcolor: "bg-indigo-50",
        rgbahover: "rgba(165, 180, 252, 1)",
        twcolorhover: "bg-indigo-300"
        },
        {
        colortitle: "Gray-ish", 
        rgba: "rgba(209, 213, 219, 1)",
        twcolor: "bg-gray-300",
        rgbahover: "rgba(55, 65, 81, 1)",
        twcolorhover: "bg-gray-700"
        },
        {
        colortitle: "Gray-ish x2", 
        rgba: "rgba(75, 85, 99, 1)",
        twcolor: "bg-gray-600",
        rgbahover: "rgba(17, 24, 39, 1)",
        twcolorhover: "bg-gray-900"
        }
    ]
    
})}}