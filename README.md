# Jiggle-Into-Java
Prework Module
<!DOCTYPE html>
<html>
<head>
    <title>Jiggle Into JavaScript</title>
    <!-- <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script> -->
</head>
<body>

    <p>Press the buttons to change the box!</p>

    <div id="box" style="height:150px; width:150px; background-color:orange; margin:25px"></div>

    <button id="button1">Grow</button>
    <button id="button2">Blue</button>
    <button id="button3">Fade</button>
    <button id="button4">Reset</button>
    <button id="button5">Purple</button>
    <button id="button6">Green</button>

    <script type= "text/javascript">
    
        document.getElementById("button1").addEventListener("click", function(){

            document.getElementById("box").style.height = "250px";
        });

        document.getElementById("button2").addEventListener("click", function(){

            document.getElementById("box").style.backgroundColor ="blue";

        });

        document.getElementById("button3").addEventListener("click", function(){

            document.getElementById("box").style.opacity = "0.25";

        });

        document.getElementById("button4").addEventListener("click", function(){

            document.getElementById("box").style.height ="150px";
            document.getElementById("box").style.backgroundColor ="orange";
            document.getElementById("box").style.opacity = "initial";

        });

        document.getElementById("button5").addEventListener("click", function(){

            document.getElementById("box").style.backgroundColor ="purple";
        });

        document.getElementById("button6").addEventListener("click", function(){

            document.getElementById("box").style.backgroundColor ="green";
        });


    </script>

</body>
</html>
