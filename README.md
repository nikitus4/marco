<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Themed Camera Frames</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            font-family: 'Arial', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
            min-height: 100vh;
        }

        .frame {
            position: relative;
            width: 400px;
            height: 300px;
            border: 8px solid;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .label {
            position: absolute;
            bottom: -25px;
            left: 50%;
            transform: translateX(-50%);
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            font-size: 24px;
            padding: 5px 20px;
            border-radius: 10px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }

        .rocket-league {
            border-color: #ff7300;
            background: url('https://example.com/rocket_league_background.jpg') center/cover;
        }

        .valorant {
            border-color: #ff4655;
            background: url('https://example.com/valorant_background.jpg') center/cover;
        }

        .fortnite {
            border-color: #1e90ff;
            background: url('https://example.com/fortnite_background.jpg') center/cover;
        }

        .camera-view {
            color: white;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="frame rocket-league">
        <div class="camera-view">Your Camera Feed</div>
        <div class="label">Rocket League</div>
    </div>

    <div class="frame valorant">
        <div class="camera-view">Your Camera Feed</div>
        <div class="label">Valorant</div>
    </div>

    <div class="frame fortnite">
        <div class="camera-view">Your Camera Feed</div>
        <div class="label">Fortnite</div>
    </div>
</body>
</html>
