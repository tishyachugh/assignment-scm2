# WEATHER APP

## 📌 Description
A weather app provides real-time weather updates, forecasts, and alerts, helping users plan their day with accurate information on temperature, humidity, wind speed, and precipitation. It offers easy-to-read visuals and notifications for current and future conditions, ensuring users stay informed and prepared.
## 🎨 Demo Preview (HTML & CSS)
Here is a simple **HTML & CSS** snippet from the project:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App 🌦️</title>
    <style>
        /* General Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #74EBD5, #ACB6E5);
            color: #fff;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            background: rgba(0, 0, 0, 0.6);
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            max-width: 600px;
            width: 90%;
        }

        h1 {
            font-size: 42px;
            margin-bottom: 10px;
            color: #FFD700;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        .btn {
            background: #FF6F61;
            color: #fff;
            padding: 12px 30px;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-size: 18px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #FF4136;
            transform: scale(1.05);
        }

        .collaborators {
            margin-top: 20px;
            font-size: 20px;
            color: #FAD02E;
        }

        .collaborators span {
            font-weight: bold;
            color: #4CAF50;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 32px;
            }
            .btn {
                padding: 10px 25px;
                font-size: 16px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Weather App 🌦️</h1>
    <p>Get real-time weather updates, forecasts, and alerts at your fingertips. Stay informed and prepared!</p>
    
    <button class="btn">Check Weather</button>

    <div class="collaborators">
        <p>👥 <span>Collaborators:</span> Ritika, Riva, Tishya, Yakshi</p>
    </div>
</div>

</body>
</html>

