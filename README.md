# Menu HTML and CSS with Animation

![menu](https://user-images.githubusercontent.com/90210126/132254147-13284a2b-0dc5-473c-9c69-ee74a498ce6e.PNG)

<h3>HTML</h3>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENU</title>

<link rel="stylesheet" href="CSS/CSS.css">

</head>
<body>
    
    <nav id="menu">

    <ul>

        <h3>
        <li><a href="#">INÍCIO</a></li>
        <li><a href="#">YOUTUBE</a></li>
        <li><a href="#">BLOG</a></li>
        <li><a href="#">CONTATO</a></li>
        <li><a href="#">ENTRAR</a></li>
    </h3>
    </ul>

    </nav>



</body>
</html>
```

<h3>CSS</h3>

```
* {
    
    margin: 0 auto;
    padding: 0 auto;
    box-sizing: border-box;
    

}

body {
    
background-color: black;

}

#menu ul {
     
    text-align: center;
    background-image: linear-gradient(to right, rgb(75, 170, 233), rgb(2, 45, 100));
    

}

#menu ul h3 li{

    display: inline;
    padding: 10px;

}

#menu ul h3 li a {

    text-decoration: none;
    padding: 20px;
    color: blanchedalmond;
    font-family: 'Courier New', Courier, monospace;
    display: inline-block;
    transition:background  0.7s;

}

#menu ul h3 li:last-child a {

    float: right;

}

#menu ul h3 li a:hover {

    background-color: black;


}




```
