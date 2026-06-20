<!DOCTYPE html>
<html>
<head>
    <title>Happy Birthday Gowtham</title>

    <style>
        body{
            margin:0;
            overflow:hidden;
            text-align:center;
            font-family:Arial, sans-serif;
            background:linear-gradient(to bottom,#ff9a9e,#fad0c4);
        }

        h1{
            margin-top:180px;
            font-size:55px;
            color:white;
            text-shadow:2px 2px 8px rgba(0,0,0,0.3);
        }

        p{
            font-size:24px;
            color:white;
        }

        /* Fast Balloons */
        .balloon{
            position:absolute;
            bottom:-120px;
            width:60px;
            height:80px;
            border-radius:50%;
            animation:fly 4s linear infinite;
        }

        .balloon::after{
            content:"";
            position:absolute;
            width:2px;
            height:50px;
            background:#555;
            left:50%;
            top:80px;
        }

        .red{left:10%; background:#ff4d4d;}
        .blue{left:30%; background:#4d79ff; animation-delay:1s;}
        .green{left:50%; background:#33cc33; animation-delay:2s;}
        .yellow{left:70%; background:#ffcc00; animation-delay:0.5s;}
        .purple{left:90%; background:#b366ff; animation-delay:1.5s;}

        @keyframes fly{
            from{
                transform:translateY(0);
            }
            to{
                transform:translateY(-130vh);
            }
        }

        /* Corner Poppers */
        .popper{
            position:absolute;
            font-size:55px;
            animation:pop 1s infinite;
        }

        .tl{top:10px;left:10px;}
        .tr{top:10px;right:10px;}
        .bl{bottom:10px;left:10px;}
        .br{bottom:10px;right:10px;}

        @keyframes pop{
            0%{transform:scale(1);}
            50%{transform:scale(1.4);}
            100%{transform:scale(1);}
        }
    </style>
</head>

<body>

    <div class="popper tl">🎉</div>
    <div class="popper tr">🎉</div>
    <div class="popper bl">🎉</div>
    <div class="popper br">🎉</div>

    <div class="balloon red"></div>
    <div class="balloon blue"></div>
    <div class="balloon green"></div>
    <div class="balloon yellow"></div>
    <div class="balloon purple"></div>

    <h1>🎉 Happy Birthday Gowtham! 🎂</h1>
    <p>Wishing you a day filled with happiness, laughter, and success. 🥳</p>

</body>
</html>
