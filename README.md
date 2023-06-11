# Ex-03:
## CREATE A WEB-LAYOUT USING FLEXBOX
### AIM:
The aim of this code is to create a web layout using flexbox, which allows for flexible and responsive positioning of elements within the webpage.
### ALGORITHM:
1. Create an HTML document with the necessary structure, including the doctype declaration, title tag, and style tag.
2. Set the CSS box-sizing property to border-box for all elements to include padding and border widths in the total element width.
3. Apply CSS to the nav and aside elements to make them have a fixed width of 20vw (20% of the viewport width) and occupy the remaining space using flex: 0 0 20vw.
4. Style the header, footer, article, nav, and aside elements with background colors and set their padding to 1em.
5. Add content to the header, article, nav, aside, and footer elements as desired.
6. Close the style tag and include the header, main, and footer elements within the body of the HTML document.
### PROGRAM:
```html
<!doctype html>
<title>Example</title>
<style>
  * {
    box-sizing: border-box; 
  }
  body {
    display: flex;
    min-height: 100vh;
    flex-direction: column;
    margin: 0;
  }
  #main {
    display: flex;
    flex: 1;
  }
  #main > article {
    flex: 1;
    order: 1;
  }
  #main > nav, 
  #main > aside {
    flex: 0 0 20vw;
  }
  #main > nav {
    background: #D7E8D4;
    order: 3;
  }
  #main > aside {
    background: beige;
    order: 2;
  }
  header, footer {
    background: yellowgreen;
    height: 20vh;
  }
  header, footer, article, nav, aside {
    padding: 1em;
  }
</style>
<body>
  <header>Header</header>
  <div id="main">
    <article>Article</article>
    <nav>Nav</nav>
    <aside>Aside</aside>
  </div>
  <footer>Footer</footer>
</body>
```
### OUTPUT:
<img width="1280" alt="1" src="https://github.com/KeerthikaNagarajan/WEB-LAYOUT-USING-FLEXBOX/assets/93427089/6f0e6d7a-7a15-4ba0-922b-46327895955c">

### RESULT:
The code to generate a webpage with a flexbox layout was successfully done.
