---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->

<div>For full publication list with citations visit my google scholar profile.</div>


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Two Boxes Side by Side Example</title>
    <style>
        /* Define the style for the box */
        .custom-box {
            width: 60px; /* Set the width of the box */
            height: 20px; /* Set the height of the box */
            color: #ffffff; /* Set the text color */
            text-align: center; /* Center the text horizontally */
            line-height: 100px; /* Center the text vertically within the box */
            margin: 5px; /* Add some margin for spacing */
            display: inline-block; /* Set boxes to display inline */
        }
    </style>
</head>
<body>

    <!-- Create the first box with text inside -->
    <div class="custom-box" style="background-color: #00369f;">
        Conference
    </div>

    <!-- Create the second box with text inside -->
    <div class="custom-box" style="background-color: #0066007;">
        Journal
    </div>

    <!-- Create the second box with text inside -->
    <div class="custom-box" style="background-color: #eb9834;">
        Workshop
    </div>

    <!-- Create the second box with text inside -->
    <div class="custom-box" style="background-color: #eb3434;">
        Thesis
    </div>

    <!-- Create the second box with text inside -->
    <div class="custom-box" style="background-color: #a31c9c;">
        Preprint
    </div>

    <!-- Create the second box with text inside -->
    <div class="custom-box" style="background-color: #4d0099;">
        Book
    </div>

</body>


<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
