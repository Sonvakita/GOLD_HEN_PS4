# GOLD_HEN_PS4
LIBERASION PS4 GOLD HEN 
<html manifest="nano.cache">
    
<head>
    <title>Auto GoldHEN Host</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body 
        {
            background-image: url("host.jpg");
            height: 80%;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        .loader 
        {
            position: absolute;
            left: 50%;
            top: 50%;
            margin: -75px 0 0 -75px;
            border: 10px solid #1f1e1e;
            border-radius: 50%;
            border-top: 10px solid #d40606;
            border-left: 10px solid #d40606;
            width: 120px;
            height: 120px;
            animation: spin 1s linear infinite;
        }

        @keyframes spin 
        {
            0% {
                transform: rotate(0deg);
            }

            100% {
                transform: rotate(360deg);
            }
        }

        .info 
        {
            overflow: hidden;
            position: fixed;
            position: absolute;
            top: 50%;
            left: 50%;

            font-size: 45px;
            font-family: sans-serif;
            color: #d40606;

            transform: translate(-50%, -50%);
        }

        .j {
            font-size: 15px;
            color: #d40606;
        }
    </style>
     
     <script>
        window.applicationCache.ondownloading=function(){document.getElementById("progress").innerHTML="Cache de host iniciado!!";};
        window.applicationCache.onprogress=function(a){document.getElementById("progress").innerHTML=(Math.round(100*(a.loaded/a.total)))+"%";};
        window.applicationCache.oncached=function(){document.getElementById("progress").innerHTML="Cache almacenado exitosamente!!";setTimeout(function(){document.getElementById("progress").innerHTML="Apaga el Internet & Abre de nuevo el navegador!!"; }, 1500);};
        window.applicationCache.onnoupdate=function(){setTimeout(webkitExploit,500);};
	    window.applicationCache.onerror=function(){setTimeout(webkitExploit,500);};

        function allset() 
        {
            document.getElementById("loader").style.display = "none";
            document.getElementById("allset").style.display = "block";
        }
    </script>
    <script src="exploit.js"></script>
</head>

<body>
    <h1 id=progress style='font-size:25px;text-align:center;text-shadow: 4px 4px 4px black;color:yellow;'></h1><br>
    <div id="loader" class="loader"></div>
    <div id="allset" class="info" style="display:none;">GOLD HEN ACTIVADO SIERRA EL NAVEGADOR DISFRUTA !</div>
</body>

</html>
