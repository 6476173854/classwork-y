<!DOCTYPE html>
<html>
<head>
    <title>document</title>
    <style>
        
        .parent{
            display: flex;
            background-color: aquamarine;
            
        }
        .a{background-color: red;
            height: 100px;
            width: 100px;
            padding: 10px;
            margin: 10px;
            flex-direction: column;
            flex-wrap: wrap;

        }
        .b{
            height: 300px;
            width: 100px;
            background-color: rgb(253, 127, 255);
            justify-content: end;

        }
        .p{
            background-color: rgb(41, 50, 48);
            display: flex;
            
        }
        .n{
            display: flex;
            background-color: green;
        }
    </style>
</head>
<body>
<div class="p">header</div>
    <div class="parent">
        <div class="a">main</div>
        <div class="a">page</div>
        <div class="a">page</div>
        <div class="a">page</div>
        <div class="a">page</div>
        <div class="a">page</div>
        <div class="a">page</div>
    </div>
         

        
        <div class="b">sidebar</div>
        <div class="n">footer</div>

        
   
</body>
</html>
