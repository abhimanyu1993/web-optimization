# Project 4: Website Performance Optimization


## Part 1: index.html

[Live Demo](https://abhimanyu1993.github.io/web-optimization/)

#### Results

- Mobile : 93/100
- Desktop: 91/100

#### Changes Made

- Change external script loading to async
- Optimize images and remove external image hosting
- Switch font loading to javascript
- Minify js and css
- Inline CSS

## Part 2: pizza.html

[Live Demo](https://abhimanyu1993.github.io/web-optimization/views/pizza.html)

#### Results

- Time to create frames reduced by over 100%
- Time to resize pizzas under 5s

#### Changes Made

- In updatePositions(): calculate expensive math operations once, outside for loop
- In changePizzaSizes(): move dx and newwidth out of the loop, calculate only once

## Resources Used

- [http://cssminifier.com/](http://cssminifier.com/)
- [https://imageoptim.com/](https://imageoptim.com/)
- [http://jscompress.com/](http://jscompress.com/)