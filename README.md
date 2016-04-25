<!doctype html>

<!-- Head of the file -->
<head>
    <title>Sprites Example Website</title>
    <link rel="stylesheet" type="text/css" href="sprites.css">
    
</head>


<!-- body of the file-->
<body>
    <!-- this is a wrapper in order to center the buttons as a whole -->
    <div id="wrapper">
    
    <!-- these are the buttons -->
    <button id="home" class="icons"></button>
    <button id="save" class="icons"></button>
    <button id="email" class="icons"></button>
    <button id="comment" class="icons"></button>
    
    </div>

</body>
</html>



/* CSS file */
/* basic body of the page */

body {
	background-color: #274c71;
}

#wrapper {
    margin: 0 auto;
    width: 400px;
    top: 50%;
    
}

/* the sprites images itself */
.icons {
    background: url(sprites.png);
	width: 50px;
    height: 50px;
    border: none;
    outline: none;
    cursor: pointer;
    margin: 20px;
}

/* the placement of the sprites */
#home {background-position: 0px 0px;}
#home:hover {background-position: 0px -50px}
#home:active {background-position: 0px -100px;}

#save{background-position: -50px 0px;}
#save:hover {background-position: -50px -50px;}
#save:active {background-position: -50px -100px;}

#email {background-position:-100px 0px;}
#email:hover {background-position:-100px -50px;}
#email:active {background-position:-100px -100px;}

#comment {background-position: -150px 0px;}
#comment:hover {background-position: -150px -50px;}
#comment:active {background-position: -150px -100px;}
