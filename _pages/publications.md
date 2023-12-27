---
layout: page
permalink: /publications/
title: publications
description: For full publication list with citations visit my google scholar profile.
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colored Box</title>
    <style>
        /* Define the style for the box */
        .colored-box {
            width: 10px; /* Set the width of the box */
            height: 10px; /* Set the height of the box */
            background-color: #ff0000; /* Set the background color of the box (replace #ff0000 with your desired color code) */
            color: #ffffff; /* Set the text color (replace #ffffff with your desired color code) */
            text-align: center; /* Center the text horizontally */
            line-height: 100px; /* Center the text vertically within the box */
        }
    </style>
</head>
<body>

    <!-- Create the box with text inside -->
    <div class="colored-box">
        Thesis
    </div>

</body>
<div>Plain Text</div>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
