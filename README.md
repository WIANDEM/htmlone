<!DOCTYPE html>

<html>
    <head>
        <meta charset="UTF-8">
        <title> Слайд</title>
        
        <link rel = "stylesheet" type="text/css" href="STL.css">
    </head>
    <body>
        <div class="slideshow-container">
            <div class = "mySladefade">
                <div class="numbertext">1 / 3</div>
                <img src = "picture.jpg" style="width: 100%">
                <div class = "text">Первая картинка</div>            
            </div>
            <div class = "mySladefade">
                <div class = "numbertext">2 / 3</div>
                <img src = "picture2.jpg" style = "width: 100%;">
                <div class = "text">Вторая картинка</div>
            </div>
            <div class = "mySladefade">
                <div class = "numbertext">3 / 3</div>
                <img src = "picture3.jpg" style = "width: 100%;">
                <div class = "text">Третья картинка</div>
            </div>
            <a href="prev" onclick="plusSides(-1)"></a>
            <a href="next" onclick="plusSlides(1)"></a>
        </div>

    <script src="java.js"></script>
    </body>
</html>
