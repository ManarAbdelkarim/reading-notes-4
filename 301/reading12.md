# EJS Partials

![ejs image](https://images.g2crowd.com/uploads/product/image/large_detail/large_detail_f9dd821cb48125c63c64b6f5c7552372/ejs.png) 

EJS is templating language that use to generate html files at the end. It used in need to a way to create dynamic content to the web page based on the data coming from the api and OFC we can’t get that goal by static html.

**Partials**
Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file and include it wherever you need it.

**How to Use**
Including a partial in EJS is quite straightforward. 
```
You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.
```
```
Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’, etc…
```