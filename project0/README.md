# Project 0

Web Programming with Python and JavaScript

## achivements

1. 4 pages
    - about.html
    - contact.html
    - index.html
    - interests.html
2. one list
    - index.html has 2 lists
3. one stylesheet
    - css/style.css is the compiled .css file
4. 5 css properties, 5 selectors (#id at least once, .class at least once)
    - properties in my stylesheets: background-color, color, flex-direction, text-align, content, ...
    - #id selector for #first in index.html
    - .class selector for .green in index.html
    - others:
        - select elements: header
        - select descendants: header h1
        - select direct children: header > p
        - select a pseduo-class: header > p:hover
        - select a attribute: :root body table > thead th\[scope=col\]
5. at least one media query
    - @media screen and (max-width: 576px) which fixes bootstrap navigation bar error
    - @media print which hide all contents from being printed
6. use at least 1 boostrap component, at least 2 columns for layout
    - use .nav and .jumbotron as components
    - use .container .row .col-* in index.html for layout
7. use at least one scss variable
    - $text-once-color
8. README.md
    - this file
    - bootstrap .nav has bug with .flex-*-column class. It should use max-width as breakpoint.
