# lecture-9-js-alerts 

In many cases, when you head to a website, you can navigate to a different web page within the website by changing (or adding) a path in the URL. This is done clicking on a link, or manually typing in the URL into the browser.

For example, you can head to www.example.com, or you can navigate to a different page by adding the "/about" path and going to www.example.com/about (in our case, '/about' doesn't exist on example.com's server, so it won't load).

You can do something similar with Flask too! instead of using `@app.route('/')`, you can return a different page by assigning a different path using `@app.route('/about')` or any path you choose. Try out the paths with the boilerplate code provided!
