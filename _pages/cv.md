---
layout: cv
permalink: /resume/
title: Resume
nav: true
nav_order: 5
cv_pdf: /assets/pdf/Resume_Le-Gia-Khanh-Truong.pdf # you can also use external links here
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
toc:
  sidebar: left
---

<style>
  /* 1. Prevent the left column from collapsing into the timeline dot */
  .cv .timeline > li > .timeline-panel,
  .cv .timeline .col-sm-3,
  .cv .timeline [class*="w-1/4"],
  .cv .timeline [class*="w-32"] {
    min-width: 170px !important;
    padding-left: 20px !important; /* Creates a clean buffer between the dot and the badge */
  }

  /* 2. Permanently delete the map pin icon and the empty space below the year */
  .cv .timeline .location,
  .cv .timeline .fa-location-dot,
  .cv .timeline svg[class*="fa-location"] {
    display: none !important;
  }

  /* 3. Ensure the year badge sits squarely in the middle of the newly fixed column */
  .cv .timeline .badge {
    margin: 0 auto !important;
    display: block !important;
    width: fit-content !important;
  }
</style>
