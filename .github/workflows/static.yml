<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARG Entry</title>
    <style>
        /* Black background and centering */
        body {
            background-color: #000;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            font-family: 'Courier New', Courier, monospace;
        }

        .container {
            text-align: center;
        }

        /* Glitchy Text Box Styling */
        .glitch-input {
            background: transparent;
            border: 2px solid #00ff00;
            color: #00ff00;
            font-size: 1.5rem;
            padding: 15px;
            width: 300px;
            outline: none;
            text-transform: uppercase;
            letter-spacing: 2px;
            position: relative;
            animation: glitch-vibrate 0.3s infinite alternate;
            box-shadow: 0 0 10px #00ff00;
        }

        /* The Glitch Vibration Effect */
        @keyframes glitch-vibrate {
            0% { transform: translate(0); text-shadow: 2px 2px #ff00ff; }
            25% { transform: translate(-2px, 2px); }
            50% { transform: translate(2px, -2px); text-shadow: -2px -2px #00ffff; }
            75% { transform: translate(-2px, -2px); }
            100% { transform: translate(2px, 2px); }
        }

        .glitch-input::placeholder {
            color: rgba(0, 255, 0, 0.5);
        }

        /* Hidden submit button triggered by 'Enter' */
        .hidden-submit {
            display: none;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Form configured to send to your email -->
        <form action="https://formsubmit.co" method="POST">
            <!-- Custom Subject Line -->
            <input type="hidden" name="_subject" value="arg important">
            <!-- Disables the FormSubmit confirmation page so it stays on your site -->
            <input type="hidden" name="_next" value="https://yourwebsite.com">
            
            <input type="text" name="message" class="glitch-input" placeholder="ask them something" required>
            <input type="submit" class="hidden-submit">
        </form>
    </div>

</body>
</html>
