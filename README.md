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
    
    
## Cam's Pizzeria
1. https://github.com/jayampathiw/frontend-nanodegree-mobile-portfolio/blob/master/views/pizza.html
2. Move the slider to change the pizza size (open web inspector console log to check the time it takes to redraw the page)
3. Scrolling the page - Console.log should show 60 frames under 1ms (which means each redraw is higher than 60 fps)

### Optimizations Performed
1. Inline CSS styling:
   - pizza.html - embedded the style.css file
2. Optimized images:
   - pizza.png - reduced size and removed metadata
   - pizzeria.jpg - reduced size and removed metadata
3. main.js file
    - optomized the js file
4. Minify js
    - Minified "main.js" using [Minify JS](http://jscompress.com/)
5. Minify css
    - Minified "bootstrap-grid.css" using [CSS Minifier](http://cssminifier.com/)
 