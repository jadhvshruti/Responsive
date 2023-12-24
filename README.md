# Responsive
Website Responsiveness

//-------------------------html-----------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="response.css">
</head>
<body>
    <div class="container">
        <div class="box_1">
          <h1>Div1</h1>  
         </div>

        <div class="box_2">
            <h1>Div2</h1>
         </div>
    </div>
</body>
</html>


//------------------------------------CSS-------------------------------------
.box_1{
    background-color: purple;
     width: 70%;
    float: left;
}

.box_2{
    background-color: yellow;
    float: left;
    width: 30%;
 }

h1{
    font-size: 80px;
}

@media screen and (max-width:820px) {
    .box_1{
        width: 50%;
    }

    .box_2{
        width: 50%;
    }
    
}

@media screen and (max-width:400px) {
    .box_1{
        width: 100%;
        color: green;
        background-color: lightblue;
    }

    .box_2{
        width: 100%;
    }
    
}

 

