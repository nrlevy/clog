---
layout: post
title: Final Project in Progress
---

{{ page.title }}
================

<@-moz-keyframes blink {0%{opacity:1;} 50%{opacity:0;} 100%{opacity:1;}} /* Firefox */
@-webkit-keyframes blink {0%{opacity:1;} 50%{opacity:0;} 100%{opacity:1;}} /* Webkit */
@-ms-keyframes blink {0%{opacity:1;} 50%{opacity:0;} 100%{opacity:1;}} /* IE */
@keyframes blink {0%{opacity:1;} 50%{opacity:0;} 100%{opacity:1;}} /* Opera and prob css3 final iteration */
img {
border:1px solid #000;
-moz-transition:all 1s ease-in-out;
-webkit-transition:all 1s ease-in-out;
-o-transition:all 1s ease-in-out;
-ms-transition:all 1s ease-in-out;
transition:all 1s ease-in-out;
/* order: name, direction, duration, iteration-count, timing-function */   
-moz-animation:blink normal 2s infinite ease-in-out; /* Firefox */
-webkit-animation:blink normal 2s infinite ease-in-out; /* Webkit */
-ms-animation:blink normal 2s infinite ease-in-out; /* IE */
animation:blink normal 2s infinite ease-in-out; /* Opera and prob css3 final iteration */
}&#8203;

img {
    animation: 2s ease-in-out 0s normal none infinite blink;
    border: 1px solid #000000;
    transition: all 1s ease-in-out 0s;
}

img.abc {
    animation: none;
    transition: none;
}
