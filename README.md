## Website Performance Optimization Portfolio Project

Here is Cameron's portfolio website that needed to be optimized.

# Way to run the site.
To run the site, got to https://yashmittal0507.github.io/websiteoptimization-project/.
This url directs to Cameron's portfolio website

To view the pizza.html simply click on the html file in views/pizza.html and run it in any browser of your choice.
# Optimization

Part 1: Optimize PageSpeed Insights score for index.html

1.Optimized the images, reduce the size of pizzaria.jpg and profilepic.jpg
2.Inline css/style.css and css/print.css
3.Made google-analytics script async
4.Made the javascript asynchronous web font loading

Part 2: Optimize Cam's Pizzeria website to run jank-free at 60f/s

Optimized 'for loops' and rendering of pizzas.
1.Made changes to the UpdatePosition function and calculated math operations outside loop.
2.Changed the no of pizzas generated on page load based on the window height(resolution)
3.Changed the querySelector call for selecting movingPizzas1 element to getElementById and saved it to a local variable named as rollingPizzas.
