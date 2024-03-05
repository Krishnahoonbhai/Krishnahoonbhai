- 👋 Hi, I’m @Krishnahoonbhai
-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apology and Call Request</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e6f7ff; /* Light blue background */
            text-align: center;
            margin: 0;
            padding: 0;
        }

        h1 {
            color: #333;
            margin-top: 50px;
            font-size: 32px; /* Larger font size */
            text-shadow: 2px 2px 4px #a6a6a6; /* Text shadow for emphasis */
        }

        p {
            font-size: 18px;
            color: #555;
            margin-bottom: 30px;
            font-style: italic; /* Italic text */
        }

        strong {
            animation: boldAnim 1s infinite alternate; /* Bold animation */
        }

        @keyframes boldAnim {
            from { font-weight: normal; }
            to { font-weight: bold; }
        }

        button {
            background-color: #66ccff; /* Light blue button color */
            color: white;
            padding: 15px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
            transition: background-color 0.3s ease; /* Smooth transition for button color change */
        }

        button:hover {
            background-color: #4da6ff; /* Darker blue on hover */
        }

        .option {
            display: inline-block;
            margin: 10px;
        }

        .hidden {
            display: none;
        }

        .read-more {
            color: #007bff;
            text-decoration: none;
            cursor: pointer;
        }

        .ellipsis {
            margin-left: 5px;
            font-size: 20px;
        }

        @keyframes shake {
            0% { transform: translate(0, 0); }
            25% { transform: translate(-5px, -5px); }
            50% { transform: translate(5px, 5px); }
            75% { transform: translate(5px, -5px); }
            100% { transform: translate(0, 0); }
        }

        .no-option {
            animation: shake 0.5s;
            animation-iteration-count: 2;
        }
    </style>
</head>
<body>
    <h1>Dear <strong>Mitali</strong>,</h1>
    <p>Reflecting on that day, I realize how much I hurt you when I left you on 'seen'.<br>
    I'm truly sorry, and I want you to know that it was never my intention to make you feel ignored or unimportant.<br>
    You mean everything to me, and I promise to do better in the future.<br>
    Thank you, Mitali.</p>
    <p>Sometimes, you reply late to me. Are you sorry for that?</p>
    <button class="option" onclick="replyLate('yes')">Yes</button>
    <button class="option" onclick="replyLate('no')" disabled>No</button>
    
    <div id="timingMessage" class="hidden">
        <p>See you at <span id="selectedTime"></span></p>
    </div>
    
    <script>
        function replyLate(response) {
            if (response === 'yes') {
                alert("Thank you for understanding, Mitali.");
            } else {
                alert("I know you, dumbass! You never accept your mistake, so I'll take it as a 'Yes'.");
            }
            
            var timingInput = document.getElementById("timingInput").value;
            document.getElementById("selectedTime").textContent = timingInput;
            document.getElementById("timingMessage").classList.remove("hidden");
        }
    </script>
</body>
</html> 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Krishnahoonbhai/Krishnahoonbhai is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
