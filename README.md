# EXP 03 - CREATE A WEB-LAYOUT USING FLEXBOX
## Program:
```

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
## Output:
<img width="1280" alt="1" src="https://github.com/KeerthikaNagarajan/WEB-LAYOUT-USING-FLEXBOX/assets/93427089/6f0e6d7a-7a15-4ba0-922b-46327895955c">
