# Grid-Work
//Current work on HTML/CSS grids & i've switched to Wijimo since.

//webpage layout html grid
<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>CSS3 Grid layout BP</title>
<style>
body {
    display: -ms-grid;
    -ms-grid-columns: 200px 10px 1fr 10px 200px;
    -ms-grid-rows: 100px 10px 1fr 10px 100px;
    margin: 0px;
    height: 100vh;
    min-width: 900px;
}
body > * { background: #CCC; font-size: 23px; }
header { -ms-grid-column-span: 5; -ms-grid-row: 1; }
nav { -ms-grid-column: 1; -ms-grid-row: 3; }
#content { -ms-grid-column: 3; -ms-grid-row: 3; }
aside { -ms-grid-column: 5; -ms-grid-row: 3; }
footer { -ms-grid-row: 5; -ms-grid-column-span: 5; }
</style>
</head>
<body>
  <header>header</header>
  <nav>navigation</nav>
  <div id="content">page content ...</div>
  <footer>footer</footer>
  <aside>aside</aside>
</body>
</html>

