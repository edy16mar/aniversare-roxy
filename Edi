<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aniversare 1 an și 7 luni</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
            overflow-x: hidden;
        }
        h1 {
            font-size: 3em;
            color: #e74c3c;
            margin-top: 20px;
            animation: fadeInText 2s ease-in-out infinite alternate;
        }
        h2 {
            font-size: 2em;
            color: #34495e;
            margin-top: 20px;
        }
        #photo {
            margin-top: 20px;
            max-width: 400px;
            width: 100%;
            height: auto;
            border-radius: 15px;
        }
        p {
            font-size: 1.5em;
            color: #2c3e50;
            margin-top: 20px;
            padding: 0 10px;
        }
        .question {
            margin-top: 30px;
            font-size: 2em;
            color: #2980b9;
            display: none;
        }
        @keyframes fadeInText {
            from {
                opacity: 0.5;
            }
            to {
                opacity: 1;
            }
        }
        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .prompt {
            margin-top: 50px;
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            font-size: 1.5em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            animation: slideIn 1s forwards;
        }
    </style>
</head>
<body>

<h1>La mulți ani, iubita mea!</h1>
<h2>1 an și 7 luni de iubire și fericire</h2>

<img id="photo" src="https://imgur.com/a/USDiqMt" alt="Poză cu noi">

<p>Roxana, te iubesc mai mult decât cuvintele pot exprima. Ești persoana care îmi face viața mai frumoasă în fiecare zi. În fiecare moment petrecut cu tine, mă simt norocos și recunoscător. ❤️</p>

<p>Astăzi sărbătorim 1 an și 7 luni de iubire, iar eu sunt mai fericit ca niciodată să fiu alături de tine. Îți mulțumesc pentru fiecare clipă, pentru fiecare zâmbet și pentru toată dragostea ta. Te iubesc enorm și abia aștept să continuăm acest drum împreună! 🌹</p>

<!-- Scroll-triggered prompt -->
<div class="question" id="question">
    <h2>Vrei să mergem în seara asta la un film? 🎬</h2>
    <button class="prompt" onclick="alert('Super! Abia aștept să mergem! 😊')">Da, sigur!</button>
</div>

<!-- Script for showing prompt on scroll -->
<script>
    window.onscroll = function() {
        var question = document.getElementById("question");
        if (window.scrollY > 300) {
            question.style.display = "block";
            question.style.animation = "slideIn 1s forwards";
        }
    };
</script>

</body>
</html>
