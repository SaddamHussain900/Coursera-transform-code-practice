# Coursera-transform-code-practice
#HTML
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title></title>
   <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="Line1">
            <div class="d">D</div>
            <div class="o">O</div>
            <div class="n">N</div>
            <div class="t">T</div>
         
         
         </div>
         <div class="Line2">
            <div class="w">W</div>
            <div class="o">O</div>
            <div class="r">R</div>
            <div class="r2">R</div>
            <div class="y">Y</div>
           
         </div>
         <div class="Line3">
            <div class="b">B</div>
            <div class="e">E</div>
         </div>
         <div class="Line4">
            <div class="h">H</div>
            <div class="a">A</div>
            <div class="p">P</div>
            <div class="p2">P</div>
            <div class="y">Y</div>
         </div>
           
    </div>

</body>
#CSS
.container {
    padding-left: 20px;
    padding-top: 20px;
}
/*.d:hover,.n:hover,.w:hover,.r:hover,.y:hover,.b:hover,.h:hover,.p:hover,.y:hover {
    transform: rotateX(100deg);
    transition: 1s;
}
.o:hover,.t:hover,.r2:hover,.e:hover,.a:hover,.p2:hover {
    transform: rotateY(100deg);
    transition: 1s;
}*/
.Line1:hover .d,.Line1:hover .n, .Line2:hover .w,.Line2:hover .r,.Line2:hover .y,.Line3:hover .b,.Line4:hover .h,.Line4:hover .p,.Line4:hover .y
{    transform: rotateX(100deg);
    transition: 1s;
}
.Line1:hover .o,.Line2:hover .o,.Line1:hover .t,.Line2:hover .r2,.Line3:hover .e,.Line4:hover .a,.Line4:hover .p2 {
    transform: rotateY(100deg);
    transition: 1s;
}

.Line1, .Line2, .Line3, .Line4 {
    display: flex;
    
    justify-content: center;
}
.Line1 *, .Line2 *, .Line3 *, .Line4 * {
    color:pink;
    border: rgb(255, 77, 0) solid 1px;
    border-radius: 5px;
    background-color: orange;
    width: 60px;
    height: 60px;
    text-align: center;
    justify-content: center;
    align-content: center;
    font-size: 3rem;
}
