<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #ffe4e1;
            font-family: 'Arial', sans-serif;
            overflow: hidden;
        }
        #container { text-align: center; }
        .buttons { margin-top: 20px; }
        button {
            padding: 15px 25px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 10px;
            border: none;
            margin: 10px;
            transition: 0.3s;
        }
        #yesBtn { background-color: #ff4d6d; color: white; }
        #noBtn { background-color: #808080; color: white; position: absolute; }
        img { width: 200px; border-radius: 20px; }
    </style>
</head>
<body>

    <div id="container">
        <img id="mainGif" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHpueGZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1n/c76IJLufpNUMo/giphy.gif" alt="Cute Cat">
        <h1 id="question">Will you be my Valentine? ❤️</h1>
        
        <div class="buttons">
            <button id="yesBtn">Yes!</button>
            <button id="noBtn">No</button>
        </div>
    </div>

    <script>
        const noBtn = document.getElementById("noBtn");
        const yesBtn = document.getElementById("yesBtn");
        const mainGif = document.getElementById("mainGif");
        const question = document.getElementById("question");

        // Make the "No" button move away
        noBtn.addEventListener("mouseover", () => {
            const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
            const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
            noBtn.style.left = `${x}px`;
            noBtn.style.top = `${y}px`;
        });

        // What happens when she clicks "Yes"
        yesBtn.addEventListener("click", () => {
            question.innerHTML = "Yay! See you on the 14th! 🥰";
            mainGif.src = "https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHpueGZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4bmZ4JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1n/KztT2c4u8mYYUiMKdJ/giphy.gif";
            noBtn.style.display = "none";
        });
    </script>
</body>
</html>
