<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CALCULATOR</title>
    <link rel="icon" href="CAL.png">
</head>
<body>
    <style>
        body{
            background-image: url("bgs.jpg");
        }
    </style>
</body>
    <h1 >CALCULATOR</h1>
    
    <form action="" name="clc">
        <input width type="text"name="display" style="width: 380px; height: 60px"><br>
        <input class="btn"type="button" value="1" onclick="clc.display.value +='1'">
        <input class="btn"type="button" value="2" onclick="clc.display.value +='2'">
        <input class="btn"type="button" value="3" onclick="clc.display.value +='3'">
        <input class="btn"type="button" value="+" onclick="clc.display.value +='+'"><br>
        <input class="btn"type="button" value="4" onclick="clc.display.value +='4'">
        <input class="btn"type="button" value="5" onclick="clc.display.value +='5'">
        <input class="btn"type="button" value="6" onclick="clc.display.value +='6'">
        <input class="btn"type="button" value="-" onclick="clc.display.value +='-'"><br>
        <input class="btn"type="button" value="7" onclick="clc.display.value +='7'">
        <input class="btn"type="button" value="8" onclick="clc.display.value +='8'">
        <input class="btn"type="button" value="9" onclick="clc.display.value +='9'">
        <input class="btn"type="button" value="*" onclick="clc.display.value +='*'"><br>
        <input class="btn"type="button" value="Clr" onclick="clc.display.value =''" style="background-color: red;">
        <input class="btn"type="button" value="0" onclick="clc.display.value ='0'">
        <input class="btn"type="button" value="=" onclick="clc.display.value =eval(clc.display.value)">
        <input class="btn"type="button" value="/" onclick="clc.display.value +='/'">
   </form>
</body>
</html>
