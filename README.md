

<html>
<head>
    <meta charset="UTF-8">
    <title>Birthday Package</title>

    <!-- Handwritten + Elegant Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&family=Dancing+Script:wght@600&family=Caveat:wght@400;700&display=swap" rel="stylesheet">

    <style>
body::before {
    content: "";
    position: fixed;
    inset: 0;
    background: rgba(5, 8, 25, 0.6); /* deep blue night */
    z-index: -1;
}

body::before {
    content: "";
    position: fixed;
    inset: 0;
    background: rgba(10, 12, 30, 0.45); /* darkness layer */
    z-index: -1;
}

        body {
            margin: 0;
            padding: 40px;
            font-family: 'Quicksand', sans-serif;

            background: url("web2.png") no-repeat center fixed;
            background-size: cover;

            color: #e6e6ff;
            overflow-x: hidden;
        }

        /* Example class if you want Caveat in ANY section */
        .caveat-text {
            font-family: 'Caveat', cursive;
        }

        .container {
            max-width: 700px;
            margin: auto;
            padding: 40px;

           background: rgba(10, 12, 30, 0.65);

            backdrop-filter: blur(10px);

            border-radius: 25px;
            box-shadow: 0 0 35px rgba(150, 120, 255, 0.3);

            animation: fadeIn 1.5s ease;
        }

        h1, h2 {
            text-align: center;
            color: #e8e2ff;
            text-shadow: 0 0 6px rgba(170, 150, 255, 0.35);
            font-family: 'Dancing Script', cursive;
        }

        p {
            line-height: 1.7;
            font-size: 1.1em;
        }

        
        /* Twinkling Stars */
        .star {
            position: absolute;
            width: 4px;
            height: 4px;
            background: white;
            border-radius: 50%;
            opacity: 0.8;
            animation: twinkle 3s infinite ease-in-out;
        }

        @keyframes twinkle {
            0% { opacity: 0.2; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.6); }
            100% { opacity: 0.2; transform: scale(1); }
        }

        /* Page fade-in */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0px); }
        }

        /* Section Fade */
        .section {
            margin-top: 40px;
            animation: fadeIn 2s ease;
        }
.glow-box {
    border-radius: 18px;
    padding: 20px;
    background: rgba(20, 22, 45, 0.4);
}
img {
    max-width: 100%;
    border-radius: 15px;
    box-shadow: 0 0 8px rgba(120, 110, 180, 0.15);
}

      
        /* Cursor Sparkle */
        .sparkle {
            position: fixed;
            width: 6px;
            height: 6px;
            background: white;
            border-radius: 50%;
            pointer-events: none;
            opacity: 0.7;
            animation: sparkleFade 0.8s forwards;
        }

        @keyframes sparkleFade {
            from { opacity: 1; transform: scale(1); }
            to { opacity: 0; transform: scale(0.2); }
        }
    </style>
</head>

<body>

    

    <div class="star" style="top: 20px; left: 40px;"></div>
    <div class="star" style="top: 80px; right: 90px;"></div>
    <div class="star" style="bottom: 60px; left: 120px;"></div>
    <div class="star" style="bottom: 100px; right: 150px;"></div>
    <div class="star" style="top: 150px; left: 200px;"></div>
    <div class="star" style="bottom: 200px; right: 220px;"></div>
    <div class="star" style="top: 300px; left: 80px;"></div>
    <div class="star" style="bottom: 300px; right: 100px;"></div>

    <div class="container">
        <h1>✨ Happy Birthday Bestie ✨</h1>

        <div class="glow-box">
            <p class="caveat-text">Guess who's the eager one to be adultin' first huh?? tsk tsk  no more late night conversations huh? i mean i am still a minor hehe (*tucks hair behind ear cheekily*), OH WELL, to a new chapter with same ol' us, Comeback era.✨✨</p>
        </div>

        <div class="section">
            <h2>✨US✨</h2>
            <img src="chibi_drawing.jpeg" alt="Chibi Drawing">
            <p class="caveat-text">The only way we can have a picture together since you went ahead and decided to live on the Bloody pollution filled moon.</p>
        </div>

        <div class="section">
            <h2>Your Little Present✨✨</h2>
            <iframe 
    width="100%" 
    height="300" 
    scrolling="no" 
    frameborder="no" 
    allow="autoplay"
    src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/soundcloud%3Aplaylists%3A2173296008%3Fsecret_token%3Ds-8QSYWhFA5dn&color=%238b7cff&auto_play=false&hide_related=true&show_comments=false&show_user=false&show_reposts=false&show_teaser=false&visual=true">
</iframe>

        </div>

        <div class="section glow-box">
            <p class="caveat-text">Well...i hope you liked it, to coming of age and adulting (*raises a glass*) and most of all to the prettiest, most gorgeous woman i know, Cheerss!!! (*clink*) </p>
        </div>
    </div>

    <script>
        document.addEventListener("mousemove", function(e) {
            const spark = document.createElement("div");
            spark.className = "sparkle";
            spark.style.left = e.pageX + "px";
            spark.style.top = e.pageY + "px";

            document.body.appendChild(spark);
            setTimeout(() => spark.remove(), 800);
        });
    </script>






</body>
</html>
