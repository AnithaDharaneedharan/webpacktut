# webpacktut

Understanding Webpack 4 and advantages of webpack over gulp

Webpack is advance build system.

It has loaders and plugins bundled.

1. Watches for file changes and re runs the tasks
2. Run babel transpilation to ES5
3. Run a development web server
4. Users auto prefixes
5. Uses require for CSS 
6. A very powerful feature which is the tree shaking which eliminates dead code- doesnt bundle the code which is not used much
7. Bundle up smaller modules of JavaScript so we are not serving your entire application to every single user that just visits your homepage

Gulp needs packages like run-sequence and plumber to acheive tasks like error catching and running tasks in a particular order.So scaling up of gulp file is needed which can be eliminated with webpack


