# Bootstrap Learning Project

In this project, I am learning and experimenting with different Bootstrap features.

To get started, you can install Bootstrap using the following command:
 ```
 npm install bootstrap@5.3.1
 ```
To run the project, I'm using Node.js and the ```http-server package```
- If you haven't installed it yet, you can do so with the following commands: 
```
npm install -g http-server
```
- To start the server, use the following command:
```
http-server
```
- You can also specify a custom port using the -p option, like this (using port 3000 as an example):
```
http-server -p 3000
```

If you prefer the traditional approach, you can include the Bootstrap CSS by placing the `<link>` tag in the `<head>` section of your HTML, and the Bootstrap JavaScript bundle (including Popper for dropdowns, poppers, and tooltips) just before the closing `</body>` tag.


### Note: Bootstrap JavaScript Compatibility!!
Please be aware that Bootstrap JavaScript might not be fully compatible with JavaScript frameworks like React, Vue, and Angular. If you are using these frameworks, consider using framework-specific packages instead, such as(like [React Bootstrap](https://react-bootstrap.github.io/))


## Grid options 
Bootstrap's grid system uses a 12-column layout. If you don't specify a number of columns, the unit takes up 100% of the available space. If you multiply units without specifying a total of 12, they will be automatically spaced.
	xs -<576px, sm - ≥576px, md - ≥768px, lg - ≥992px, xl - ≥1200px, xxl - ≥1400px.
	
example:
``` javascript
<div class="col-md-6 col-xl-3 bg-info"></div>
``` 
 In this example, the column will take up one unit (100% off the screen or 12 columns) on small screens (md and below), medium and up to xl - two units on the page (12 max = 6 one unit + 6 another). xl and up - four units on the page (12=3+3+3+3)