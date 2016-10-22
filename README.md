## Website Performance Optimization:

This project is done as a udacity *Front-End Web Developer* practical project 4.

###Launch the URL 

https://github.com/jayampathiw/frontend-nanodegree-mobile-portfolio/blob/master/index.html


### Optimizations Performed

1. Inline CSS styling:
    - landing-page.html - embedded the style.css file
    - added media="print" for print.css since it is render blocking
2. Optimized images:
    - profilepic.jpg - reduced size, removed metadata
3. Added async attribute for perfmatters.js:
    - added the async attribute so that the script is executed asynchronously as soon as it is available.
4. Minify js
    - perfmatters.js --> http://jscompress.com/