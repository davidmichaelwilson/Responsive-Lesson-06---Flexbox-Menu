# Lesson plan
  
---

HTML:
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>replit</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <header class="flexy">
      <div>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Logo_of_Be%C5%9Fikta%C5%9F_JK.svg/640px-Logo_of_Be%C5%9Fikta%C5%9F_JK.svg.png" />
      </div>

      <div class="flexy2">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
        <button>Buy it!</button>
      </div>
    </header>
  </body>
</html>
```



CSS: 
```
body, html {
  margin: 0;
}

.flexy {
  display: flex;
  align-items: center;
}

.flexy > div {
  flex: 1;
}

header {
  background-color: lightgray;
}

header img {
  width: 60px;
  height: 60px;
  padding: 10px;
}

.flexy2 {
  display: flex;
  padding: 20px;
  align-items: center;
}

.flexy2 > * {
  flex: 1;
}

button {
  height: 40px;
  width: 80px;
}
```